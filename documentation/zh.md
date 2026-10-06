<!-- ELUCENIA technical documentation · escala-lanss · zh · no clinical/professional/rights approval -->

# LANSS 疼痛量表

[条件、来源与许可](https://elucenia.org/zh/tools/escala-lanss)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 疼痛是否像皮肤上奇怪而不愉快的感觉（针刺、麻刺、电击）？

`a1`

### 疼痛是否使患部皮肤与正常不同（斑驳、发红或粉红）？

`a2`

### 疼痛是否使皮肤异常敏感（轻触或紧身衣物引起不适）？

`a3`

### 静止时是否无明显原因突然发作疼痛（电击、刺痛）？

`a4`

### 疼痛是否使您感觉皮肤温度改变（热感、烧灼）？

`a5`

### 检查：触诱发痛（与正常区域比较，棉花轻触痛区时引发疼痛或不适）

`b6`

### 检查：针刺阈值改变（23G 针刺在痛区感觉不同：更强或更弱）

`b7`

## 方法版本

LANSS/Bennett 2001：5症状+2体征，总分0–24，界值≥12；巴西葡语Schestatsky 2011

## 已记录的公式

A部分（问卷）：各项5、5、3、2、1分。B部分（感觉检查）：触诱发痛5分；针刺阈值改变3分。总分0至24；界值≥12。

## 限制与适用人群

LANSS结合症状与感觉检查所获得的体征，以探查慢性疼痛是否主要由神经病理性机制引起。检查项目不能被当作单纯的自我报告。所引用的巴西验证研究并不认证本地实现或新翻译。

## 参考文献

- [Bennett M. The LANSS Pain Scale: the Leeds assessment of neuropathic symptoms and signs. Pain, 2001.](https://doi.org/10.1016/S0304-3959(00)00482-6)

- [Schestatsky P et al. Brazilian Portuguese validation of the Leeds Assessment of Neuropathic Symptoms and Signs for patients with chronic pain. Pain Med, 2011.](https://doi.org/10.1111/j.1526-4637.2011.01221.x)

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

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

神经病理性机制不太可能（< 12 分）

疼痛可能为伤害感受性；如情况变化，请重新评估。


### 2

可能为神经病理性疼痛机制（≥ 12 分）

考虑针对神经病理性疼痛的治疗，并调查躯体感觉系统的损伤或疾病。


### 3

可能为神经病理性疼痛机制（≥ 12 分）

考虑针对神经病理性疼痛的治疗，并调查躯体感觉系统的损伤或疾病。


### 4

可能为神经病理性疼痛机制（≥ 12 分）

考虑针对神经病理性疼痛的治疗，并调查躯体感觉系统的损伤或疾病。

