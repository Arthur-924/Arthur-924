离心收集 → 超纯水洗涤3次 → 真空干燥(60℃, 12h) → XPS验证Fe⁰含量
| 组别   | 材料    | 用量   | H2O2 | pH   | 取样时间 | 检测指标       |
|--------|---------|--------|-------|------|----------|----------------|
| 空白   | -       | -      | 2mM  | 7    | 0-60min  | SMT浓度、Fe²+  |
| 对照   | 多孔硅  | 10mg  | 2mM  | 7    | 同上     | 同上           |
| 实验组 | Fe-240  | 10mg  | 2mM  | 7    | 同上     | 同上           |
| 实验组 | Fe-241  | 10mg  | 2mM  | 7    | 同上     | 同上           |
| 实验组 | Fe-402  | 10mg  | 2mM  | 7    | 同上     | 同上           |


**试剂**：
- 浓HNO₃（65%，超纯级）
- 浓HF（40%，塑料级）
- H₂O₂（30%）
- 硼酸（饱和溶液）

**步骤**：
1. 准确称取10mg样品于聚四氟乙烯消解罐
2. 加入3mL HNO₃ + 1mL HF，密闭后于微波消解仪中程序升温：
   - 25→150℃（10min）
   - 150℃保持20min
   - 150→200℃（5min）
   - 200℃保持30min
3. 冷却后加入2mL饱和硼酸络合过量F⁻
4. 定容至50mL（超纯水），0.22μm滤膜过滤

**科学依据**：
- HF用于溶解硅基质（Si + 6HF → H₂SiF₆ + 2H₂O）
- HNO₃氧化金属态铁（3Fe⁰ + 8HNO₃ → 3Fe²⁺ + 4H₂O + 8NO↑）

#### **2. 仪器分析（ICP-OES）**
| 参数          | 设置值               |
|---------------|----------------------|
| 分析谱线      | Fe 238.204 nm       |
| RF功率        | 1400 W              |
| 雾化气流速    | 0.70 L/min          |
| 积分时间      | 5 s                 |
| 标准曲线范围  | 0.1-50 mg/L（R²>0.999）|

**质量控制**：
- 加标回收率（85-115%）
- 平行样相对标准偏差（RSD<5%）

---

### **二、铁价态分析方案**

#### **1. X射线光电子能谱（XPS）表面分析**
```markdown
**关键参数**：
- 仪器：Thermo Scientific K-Alpha+
- 激发源：Al Kα（1486.6 eV）
- 能量分辨率：0.5 eV
- 电荷中和：双束（电子+离子）

**数据分析**：
1. Fe 2p谱峰分峰拟合：
   - Fe⁰：706.8±0.2 eV（卫星峰缺失）
   - Fe²⁺：708.5-709.5 eV（伴峰707.5 eV）
   - Fe³⁺：710.5-711.5 eV（伴峰718.5 eV）
2. 定量计算各价态原子百分比

**注意事项**：
- 样品需真空干燥避免氧化
- 深度剖析（Ar⁺溅射）分析体相组成

#### **2. 湿化学法（Fe²⁺/Fe³⁺分离测定）**
**试剂**：
- 1,10-菲啰啉（0.1% w/v）
- 盐酸羟胺（10% w/v）
- 醋酸铵缓冲液（pH=4.5）

**步骤**：
1. **Fe²⁺直接测定**：
   - 取1mL滤液 → 加1mL缓冲液 + 1mL显色剂 → 510nm比色
2. **总铁测定**：
   - 另取1mL滤液 → 加0.5mL盐酸羟胺（沸水浴10min）→ 同步骤1
3. **Fe³⁺计算**：
   ```math
   \text{Fe}^{3+} = \text{总Fe} - \text{Fe}^{2+}
