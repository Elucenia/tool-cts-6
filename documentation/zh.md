<!-- ELUCENIA technical documentation · cts-6 · zh · no clinical/professional/rights approval -->

# CTS-6（腕管综合征）

[条件、来源与许可](https://elucenia.org/zh/tools/cts-6)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 麻木主要或仅限于正中神经分布区

`dorm`

### 夜间麻木

`noturna`

### 鱼际肌萎缩和/或无力

`atrofia`

### Phalen 试验阳性

`phalen`

### 两点辨别能力下降（\> 6 mm）

`dpp`

### 腕管处 Tinel 征阳性

`tinel`

## 方法版本

CTS-6/Graham 2006：6项加权腕管标准；临床检查

## 已记录的公式

相加存在的项目：正中神经分布区麻木3.5；夜间麻木4；鱼际萎缩/无力5；Phalen阳性5；两点辨别丧失4.5；Tinel阳性4。总分0–26。

## 限制与适用人群

Graham 2006的开发采用专家共识和结合临床标准的病例叙述；摘要所述的验证将模型预测概率与另一个专家组的判断进行了比较。这一设计本身并不能确立该方法在每种临床人群中相对于电生理检查的表现。六项评分、阈值及适用年龄范围应核对完整方法。

## 参考文献

- [Graham B et al. Development and validation of diagnostic criteria for carpal tunnel syndrome. J Hand Surg Am, 2006.](https://doi.org/10.1016/j.jhsa.2006.03.005)

- [Graham B. The value added by electrodiagnostic testing in the diagnosis of carpal tunnel syndrome. J Bone Joint Surg Am, 2008.](https://doi.org/10.2106/JBJS.G.01362)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
