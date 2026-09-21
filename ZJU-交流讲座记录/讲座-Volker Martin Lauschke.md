---
type: 未分类
title: 简介
created: 2026-07-09
modified: 2026-07-09
domain: 我的思考·讲座·视频
topics:
  - ZJU讲座
tags:
  - 炎症
  - 机器学习
  - 负熵
  - 线粒体
  - 生物熵
share: True
---



==代谢炎症相关，多评价指标可以详细看，很相关
系统性靶点发现的文章可以详细看





# 简介

[![- Karolinska Institutet](https://images.openai.com/static-rsc-4/L6qSEiyXRrWFCrBVgDr3XD-EjVOyGVKpZ-AAPoTv6PGr6_Y9abj_mO3pvbny5up98JnxI8sfKFMnjIdf7JsdkyxZOpv_kZNFL5emCoFEIxpfb1c2yELbftqEvLEmRWiByAAY_XG_9-XX8-eTo0aZg5LeKOsZnBE_w7svRb_1Gbk?purpose=inline)](https://mediabank.ki.se/detail/34247?utm_source=chatgpt.com)

下面按“教授本人—研究方向—3D primary human liver spheroids 技术线—代表论文/应用价值”来介绍。

## 1. 教授基本信息

**Volker Martin Lauschke** 是瑞典 **Karolinska Institutet，卡罗林斯卡医学院/KI** 的 **Translational Pharmacology 转化药理学教授**，隶属于 Department of Physiology and Pharmacology。他同时是 KI **Biofabrication and Tissue Engineering Facility** 的主任，并任德国斯图加特 **Margarete Fischer-Bosch Institute of Clinical Pharmacology** 副所长；KI 官方页面还列出他在中南大学和兰州大学担任客座教授。([ki.se](https://ki.se/en/people/volker-lauschke "Volker Martin Lauschke | Karolinska Institutet"))

他的研究组名为 **Personalized Medicine and Drug Development – Lauschke-lab**，核心方向是把 **原代人源细胞 3D 培养、微流控、组学分析、群体药物基因组学和机器学习** 结合起来，用于药物安全性评价、疾病机制研究和个体化用药。KI 官方介绍中明确提到其研究面向 NASH/MASH、COVID-19、出血热、2 型糖尿病等炎症、感染和代谢性疾病。([ki.se](https://ki.se/en/research/research-areas-centres-and-networks/research-groups/personalized-medicine-and-drug-development-lauschke-lab "Personalized Medicine and Drug Development – Lauschke-lab | Karolinska Institutet"))

从学术履历看，他本科和硕士阶段在海德堡大学等机构学习分子与细胞生物学，博士阶段在 EMBL Heidelberg，2014 年加入 Karolinska Institutet，2017 年建立自己的研究组，2018 年成为 docent 并担任 Biofab 主任，2023 年 3 月被任命为 KI 转化药理学教授。([news.ki.se](https://news.ki.se/creating-3d-models-for-drug-development "Creating 3D models for drug development | Karolinska Institutet"))

## 2. 他的研究特点

Lauschke 教授的研究可以概括为两条主线：

**第一条是“人源 3D 组织模型 + 药物开发”。** 他的团队开发长期稳定的 3D 人源组织模型，包括肝脏、胰腺、脂肪组织和骨骼肌；KI 研究组页面特别强调他们使用的是 **patient-derived cells**，也就是来源于患者/供体的原代细胞，而不是细胞系或干细胞，并通过组织学、转录组、蛋白组和代谢组验证模型具有较成熟的表型。([ki.se](https://ki.se/en/research/research-areas-centres-and-networks/research-groups/personalized-medicine-and-drug-development-lauschke-lab "Personalized Medicine and Drug Development – Lauschke-lab | Karolinska Institutet"))

**第二条是“药物基因组学 + 个体化医学”。** 他的团队利用群体遗传学和机器学习研究药物吸收、分布、代谢、排泄相关基因，以及药物靶点基因在不同人群中的变异，尤其关注罕见变异对药物疗效和毒性的影响。([ki.se](https://ki.se/en/people/volker-lauschke "Volker Martin Lauschke | Karolinska Institutet"))

## 3. 什么是 3D primary human liver spheroids？

这里的 **3D primary human liver spheroids** 通常指由 **primary human hepatocytes，PHH，原代人肝细胞** 自组装形成的三维肝细胞球/肝微组织。有时模型中也会加入非实质细胞，例如 Kupffer 细胞、星状细胞、胆管细胞等，以更接近真实肝脏微环境。它和普通 2D 单层肝细胞培养的关键差别在于：3D 球体能更好维持细胞-细胞接触、极性、代谢功能和长期稳定性。Lauschke 参与的 2016 年 Scientific Reports 论文指出，传统 2D PHH 会快速去分化，而他们建立的 3D PHH spheroid 系统在化学成分明确、无血清条件下可用于长期功能和毒理研究。([Nature](https://www.nature.com/articles/srep25187 "Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease | Scientific Reports"))

该模型的一个经典参数是：以约 **1,500 个细胞/孔** 接种后形成约 **200 μm** 直径的 spheroid，这样有利于氧气和营养物质扩散；论文显示这些 PHH spheroids 至少可稳定维持 **5 周/35 天**，保留形态、活性和肝细胞特异功能，并且在蛋白组水平上比 2D 培养更接近体内肝组织。([Nature](https://www.nature.com/articles/srep25187 "Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease | Scientific Reports"))

## 4. 这个模型为什么重要？

它的价值主要在于 **长期、慢性、接近临床暴露水平的药物毒性和代谢研究**。很多药物性肝损伤不是短时间急性毒性，而是在长期反复暴露后出现；传统 2D 肝细胞培养很快丧失肝功能，难以模拟这一过程。Lauschke 等人的 2016 年研究显示，该 3D PHH spheroid 模型能在慢性暴露条件下检测到一些更接近临床浓度的肝毒性，包括经典案例 **fialuridine/FIAU** 的慢性毒性，而这类毒性曾难以被传统体外模型有效预测。([Nature](https://www.nature.com/articles/srep25187 "Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease | Scientific Reports"))

它还可以用于模拟肝脏疾病。2016 年论文中展示了胆汁淤积、脂肪变性和病毒性肝炎等疾病状态的概念验证；2018 年 Scientific Reports 论文进一步用人源 3D hepatic spheroids 建立脂肪变性和胰岛素抵抗模型，证明通过游离脂肪酸、糖和胰岛素诱导可形成可逆性肝脂肪变，并可用于抗脂肪变药物筛选。([Nature](https://www.nature.com/articles/srep25187 "Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease | Scientific Reports"))

## 5. 与 Lauschke 教授相关的典型应用方向

|方向|具体用途|意义|
|---|---|---|
|**DILI 药物性肝损伤预测**|长期重复给药、慢性毒性、线粒体/胆汁淤积/代谢相关毒性|比短期 2D 模型更适合发现慢性肝毒性|
|**ADME / 药物代谢**|CYP 酶、转运体、药物清除率、代谢物形成|用于临床前药物开发和药代动力学评价|
|**CYP 诱导研究**|如 CYP3A4、CYP2B6、CYP1A2 等诱导风险|有助于预测药物-药物相互作用；2023 年相关研究评估了 3D spheroid PHH 对 CYP 和转运体诱导研究的适用性。([ascpt.onlinelibrary.wiley.com](https://ascpt.onlinelibrary.wiley.com/doi/10.1002/cpt.2887?utm_source=chatgpt.com "3D Spheroid Primary Human Hepatocytes for Prediction of ..."))|
|**脂肪肝/NASH/MASH 模型**|脂肪变、胰岛素抵抗、炎症/纤维化相关变化|用于代谢性肝病机制和药物筛选|
|**感染病与药物再利用**|COVID-19 相关研究中使用 primary liver spheroids 验证 baricitinib 对 SARS-CoV-2 感染性的影响|说明该平台不仅限于传统肝毒性，也可扩展到感染与炎症药理学。([PubMed](https://pubmed.ncbi.nlm.nih.gov/32473600/?utm_source=chatgpt.com "Mechanism of baricitinib supports artificial intelligence ..."))|
|**器官芯片 / 多组织互作**|肝脏 spheroid 与脂肪、胰腺、肌肉等组织模型组合|用于研究代谢病中器官间互作；KI 新闻中提到其团队将不同 spheroids 放入灌流微流控芯片中研究器官互作。([news.ki.se](https://news.ki.se/creating-3d-models-for-drug-development "Creating 3D models for drug development \| Karolinska Institutet"))|

## 6. 代表性论文线索

比较核心的几篇可以这样看：

1. **Bell et al., Scientific Reports, 2016**  
    _Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease_。这是该 3D PHH spheroid 技术线的基础性论文之一，系统展示了模型的长期稳定性、体内相似性、供体差异保留、DILI 预测和疾病模拟能力。([Nature](https://www.nature.com/articles/srep25187 "Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease | Scientific Reports"))
    
2. **Lauschke et al., Chemical Research in Toxicology, 2016**  
    _Novel 3D Culture Systems for Studies of Human Liver Function and Assessments of the Hepatotoxicity of Drugs and Drug Candidates_。这篇综述/观点文章梳理了 3D 肝培养、spheroid、microfluidic liver/biochip 等模型在肝功能和肝毒性评价中的意义。([PubMed](https://pubmed.ncbi.nlm.nih.gov/27661221/?utm_source=chatgpt.com "Novel 3D Culture Systems for Studies of Human Liver ..."))
    
3. **Kozyra et al., Scientific Reports, 2018**  
    _Human hepatic 3D spheroids as a model for steatosis and insulin resistance_。该文把 3D hepatic spheroids 用于 NAFLD/脂肪变和胰岛素抵抗建模，展示其疾病模型和药物筛选价值。([Nature](https://www.nature.com/articles/s41598-018-32722-6 "Human hepatic 3D spheroids as a model for steatosis and insulin resistance | Scientific Reports"))
    
4. **Ingelman-Sundberg et al., 2022**  
    _3D human liver spheroids for translational pharmacology and toxicology_。该文总结人肝 spheroids 在转化药理学和毒理学中的应用，强调其能维持患者/供体特异性表型和多周功能。([PubMed](https://pubmed.ncbi.nlm.nih.gov/33872466/?utm_source=chatgpt.com "3D human liver spheroids for translational pharmacology ..."))
    
5. **Järvinen et al., Clinical Pharmacology & Therapeutics, 2023**  
    _3D Spheroid Primary Human Hepatocytes for Prediction of Cytochrome P450 and Transporter Induction_。该研究进一步把 3D spheroid PHH 用于 CYP 和转运体诱导预测，服务于药物相互作用风险评估。([ascpt.onlinelibrary.wiley.com](https://ascpt.onlinelibrary.wiley.com/doi/10.1002/cpt.2887?utm_source=chatgpt.com "3D Spheroid Primary Human Hepatocytes for Prediction of ..."))
    

## 7. 产业转化信息

Lauschke 教授也是 **HepaPredict AB** 的联合创始人兼 CEO。HepaPredict 官网介绍其为专注药物代谢、毒性和肝病药物开发的 CRO，使用先进的 **3D primary human liver culture platform**；其服务包括慢性毒性研究、长期代谢分析、药物清除率评估、酶诱导研究、靶点验证、MASLD/MASH、纤维化和胆汁淤积模型等。因为这是公司官网信息，应用效果的宣传性表述应与同行评议论文一起综合判断。([ki.se](https://ki.se/en/people/volker-lauschke "Volker Martin Lauschke | Karolinska Institutet"))

## 8. 总体评价

Volker Lauschke 教授的特色不是单纯做“肝细胞培养”，而是把 **原代人源 3D 肝模型** 做成一个面向药物研发的转化平台：既能用于基础机制研究，也能用于 DILI、CYP 诱导、ADME、脂肪肝/NASH、感染病和器官芯片研究。它的优势是人源性强、长期稳定、可保留供体差异、适合慢性暴露；局限是原代肝细胞来源、批次差异、成本、供体可得性和不同实验室间标准化仍然是关键挑战。






# 3D primary human liver spheroids

**核心原理一句话：**  
3D 肝细胞球不是“外加东西把细胞粘成球”，而是利用**低黏附培养环境**让细胞不能贴在培养皿底部，于是细胞之间的**细胞-细胞黏附力**逐渐超过细胞-基底黏附力，最终自发聚集、压实，形成接近球形的三维微组织。

## 1. 3D 球体是怎么制备出来的？

以 **3D primary human hepatocyte spheroids，原代人肝细胞球** 为例，常见流程是：

1. **取原代人肝细胞 PHH**  
    可以是新鲜分离的，也可以是冻存复苏后的原代人肝细胞。
    
2. **接种到低黏附培养板**  
    常用 **ultra-low attachment round-bottom plate**、U 底板、微孔板或 hanging drop。  
    这些表面经过处理，细胞很难像普通 2D 培养那样铺展开贴壁。
    
3. **细胞沉降到孔底中心**  
    因为 U 型底或微孔结构，细胞会在重力作用下集中到一个小区域。
    
4. **形成松散细胞团**  
    初期只是细胞互相接触，结构还比较松。
    
5. **细胞间黏附增强，逐渐压实**  
    随着 E-cadherin、integrin、细胞外基质 ECM 等作用增强，细胞团逐渐变紧，形成边界清楚的 spheroid。
    
6. **成熟为功能性 3D 肝细胞球**  
    Lauschke 相关的 Bell 等 2016 年研究中，PHH spheroid 通常约 **7 天完成聚集**，接种 **1,500 cells/well** 可形成约 **200 μm** 直径的球体，这个尺寸有利于氧气和营养物质向球体内部扩散。该模型可在无血清、化学成分明确条件下稳定维持至少 5 周。([Nature](https://www.nature.com/articles/srep25187 "Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease | Scientific Reports"))
    

## 2. 为什么细胞会聚集？

主要有 **外部环境原因** 和 **细胞自身原因**。

### 外部原因：不让细胞贴底

普通 2D 培养中，细胞更容易和培养皿表面结合，所以它们会铺展开来。  
而 3D spheroid 制备时用的是低黏附表面，细胞不能稳定贴在塑料表面，于是只能选择彼此接触。

可以理解为：

> 2D 培养：细胞更愿意“趴在地板上”。  
> 3D 低黏附培养：地板很滑，趴不住，只能彼此抱团。

所以，低黏附表面本身不是让细胞聚集的“胶水”，而是**减少细胞-培养板黏附**，把细胞-细胞黏附凸显出来。2024 年 Lauschke 参与的一项研究也说明，ultra-low attachment plate 的选择会显著影响 PHH 和犬原代肝细胞 spheroid 的形成、表型和功能。([PubMed](https://pubmed.ncbi.nlm.nih.gov/38403411/?utm_source=chatgpt.com "The choice of ultra-low attachment plates impacts primary ..."))

### 细胞自身原因：细胞本来就有黏附分子

肝细胞不是惰性小珠子，它们表面有很多黏附分子，尤其是：

|分子/结构|作用|
|---|---|
|**E-cadherin**|介导同类细胞之间的黏附，是肝细胞球压实的重要因素|
|**integrin**|介导细胞与 ECM 的相互作用，也参与早期聚集|
|**ECM 细胞外基质**|细胞分泌的“支架/胶质环境”，帮助细胞团稳定|
|**actin cytoskeleton 肌动蛋白骨架**|产生收缩力，使细胞团进一步压实|
|**tight junction / gap junction**|帮助形成更接近肝组织的细胞连接和极性|

其中 **E-cadherin** 很关键。Lauschke 相关 2016 年 PHH spheroid 研究观察到，球体尺寸缩小、结构变紧与 **E-cadherin 表达增加**相伴，并指出 E-cadherin 已被证明可以促进 spheroid compaction。([Nature](https://www.nature.com/articles/srep25187 "Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease | Scientific Reports")) 早期关于原代肝细胞 spheroid 的研究也显示，抑制 E-cadherin 会阻止肝细胞之间的黏附和 spheroid 形成，说明 E-cadherin 对肝细胞球形成非常重要。([PubMed](https://pubmed.ncbi.nlm.nih.gov/20003757/?utm_source=chatgpt.com "E-cadherin protects primary hepatocyte spheroids from cell ..."))

## 3. 为什么最后是“球形”？

这是因为细胞团会趋向于**降低表面能/界面能**。  
当细胞彼此黏在一起后，外围暴露在培养液中的细胞表面积越小，整体结构越稳定。在相同体积下，**球体的表面积最小**，所以细胞团会逐渐圆化。

这和液滴有点像：水滴悬浮时也倾向于变成圆形，因为球形能量最低。  
但细胞球不是纯液滴，它还有细胞骨架、黏附连接、ECM 和细胞活性调控，所以更准确地说是一个**具有组织样力学行为的活细胞聚集体**。

## 4. 聚集过程可以分成三个阶段

### 第一阶段：沉降和初始接触

细胞被接种到 U 底或低黏附板后，在重力作用下集中到孔底中心。  
这一步主要是物理过程。

### 第二阶段：松散聚集

细胞之间开始接触，integrin-ECM 作用和初步细胞间黏附让细胞形成松散团块。  
此时 spheroid 还不够圆，边界也可能不清楚。

### 第三阶段：黏附增强和压实

E-cadherin 等细胞间黏附增强，细胞骨架收缩，ECM 重塑，细胞团逐渐变小、变圆、边界清晰。  
到这个阶段，才是真正成熟的 spheroid。

## 5. 为什么 3D 肝细胞球比 2D 更接近体内肝脏？

因为肝脏本来就是三维组织，肝细胞在体内依赖大量 **细胞-细胞接触** 和 **细胞-基质接触** 来维持功能。普通 2D 培养会让 PHH 很快去分化，丢失很多肝特异功能；而 Lauschke 相关研究显示，3D PHH spheroids 的蛋白组特征更接近体内肝组织，并且能较长时间保持 albumin、urea、CYP 代谢活性等功能。([Nature](https://www.nature.com/articles/srep25187 "Characterization of primary human hepatocyte spheroids as a model system for drug-induced liver injury, liver function and disease | Scientific Reports"))

也就是说，3D 球体的意义不是“形状好看”，而是它恢复了一部分肝细胞在体内需要的微环境：

|2D 单层培养|3D spheroid|
|---|---|
|细胞铺在平面上|细胞互相包绕|
|细胞-细胞接触少|细胞-细胞接触多|
|肝细胞容易去分化|表型更稳定|
|难做长期毒性实验|适合慢性 DILI 研究|
|极性和胆小管结构较弱|更容易形成组织样极性和胆小管样结构|

## 6. 但不是所有细胞都能顺利成球

能否形成质量好的 spheroid，取决于很多因素：

1. **细胞活性**：复苏后死亡率高，成球会差。
    
2. **细胞批次/供体差异**：不同 PHH donor 的聚集能力不同。
    
3. **接种密度**：太少不易成球，太多会造成中心缺氧坏死。
    
4. **培养板类型**：不同 ULA 板的表面性质会影响成球速度和形态。
    
5. **培养基成分**：Ca²⁺、激素、血清/无血清体系都会影响黏附和功能。
    
6. **球体尺寸**：太大时氧气和营养扩散不足，中心容易坏死。
    

所以制备 3D 肝细胞球时，关键不是单纯“让它聚起来”，而是要控制成球的**大小、圆整度、紧密度、存活率和功能稳定性**。

## 7. 最简单的理解

你可以这样理解 3D spheroid 的形成：

> 低黏附培养板让细胞不能贴壁，U 底结构让细胞集中到一起；肝细胞表面的 E-cadherin、integrin 和 ECM 让细胞彼此黏附；随后细胞骨架收缩和组织重塑使细胞团压实；由于表面能最低原则，细胞团最终趋向形成球形。

所以它的本质是：

**“物理聚集 + 生物黏附 + 细胞主动重塑”共同形成的三维微组织。**


# **comprehensive hepatotoxicity screen**

**综合肝毒性筛选 / 全面肝毒性筛查 / 综合性 DILI 风险筛选**  
其中 **DILI = drug-induced liver injury，药物性肝损伤**。

结合 **Volker Lauschke 教授的 3D primary human liver spheroids** 方向，它通常不是单一指标实验，而是一套基于 **3D 原代人肝细胞球模型** 的多终点、多时间尺度肝毒性评价体系。

## 1. 它筛查什么？

Comprehensive hepatotoxicity screen 主要用于判断候选药物、化合物或制剂是否存在以下肝毒性风险：

|类型|关注点|
|---|---|
|**急性肝毒性**|短时间暴露后细胞活性下降、膜损伤、ATP 下降等|
|**慢性 DILI**|长期重复给药后才出现的毒性，这是 3D PHH spheroid 的强项|
|**线粒体毒性**|ATP 下降、氧化磷酸化受损、ROS 升高|
|**胆汁淤积毒性**|BSEP/胆汁酸转运异常、胆汁酸共暴露增强毒性|
|**代谢依赖性毒性**|药物经 CYP 代谢后产生毒性代谢物|
|**脂肪变性/脂毒性**|肝细胞脂滴积累、脂代谢异常|
|**炎症相关毒性**|若加入 Kupffer cell 等非实质细胞，可观察炎症因子变化|
|**纤维化倾向**|若加入 hepatic stellate cells，可检测 ECM、胶原、α-SMA 等指标|

Lauschke 相关的 3D PHH spheroid 模型优势在于：相比传统 2D 单层肝细胞，3D spheroid 可在多周内维持较稳定的形态、表型和代谢功能，更适合做长期重复暴露和慢性 DILI 预测。HepaPredict 官网也明确把这类系统用于短期毒性筛查、长期重复给药毒性筛查、代谢分析、CYP 诱导、胆汁淤积、MASLD/MASH 和纤维化模型等服务。([HepaPredict AB](https://www.hepapredict.com/services-1 "Our Services — HepaPredict AB"))

## 2. 在 Lauschke 体系中，它大概怎么做？

一个典型设计可以理解为：

**候选化合物 → 3D primary human hepatocyte spheroids → 多剂量、多时间点暴露 → 多指标检测 → 判断 DILI 风险和机制。**

常见实验框架如下：

|模块|设计|
|---|---|
|**模型**|primary human hepatocyte spheroids；可做单培养，也可加入非实质细胞 NPCs|
|**暴露时间**|短期：24–72 h；长期：7–14 天甚至更久|
|**浓度设计**|通常围绕临床 Cmax 或预期暴露浓度设置多个倍数，例如 1×、5×、10×、20× Cmax|
|**给药方式**|重复给药，定期换液，以模拟慢性暴露|
|**阳性对照**|acetaminophen、troglitazone、diclofenac、fialuridine、cyclosporine A 等，视机制而定|
|**阴性对照**|已知低肝毒性药物或溶剂对照|
|**主要终点**|ATP/viability、LDH、albumin、urea、CYP 活性、ROS、GSH/GSSG、胆汁酸毒性、转录组/蛋白组/代谢组等|

Bell 等人在 2016 年的 Scientific Reports 论文中指出，PHH spheroids 可用于研究长期 DILI、肝功能和疾病模型，并展示了胆汁淤积、脂肪变性和病毒性肝炎等应用场景。([Nature](https://www.nature.com/articles/srep25187?utm_source=chatgpt.com "Characterization of primary human hepatocyte spheroids ..."))

## 3. 为什么叫 comprehensive？

因为它不是只看一个 **cell viability**。只看细胞活性下降，容易漏掉早期或机制性毒性。更全面的 screen 应该至少覆盖四类指标：

### A. 细胞损伤指标

包括 ATP、cell viability、LDH release、caspase activation、细胞形态、高内涵成像等。  
作用是判断化合物是否直接造成细胞死亡、膜损伤或凋亡。

### B. 肝功能指标

包括 albumin secretion、urea production、CYP enzyme activity、drug transporter expression。  
这些指标能反映肝细胞是否仍保持成熟功能。Lauschke/HepaPredict 体系强调 3D spheroids 能多周保持 phase I/phase II 代谢酶和药物转运体表达，因此适合长期代谢和清除率研究。([HepaPredict AB](https://www.hepapredict.com/services-1 "Our Services — HepaPredict AB"))

### C. 机制性毒性指标

包括 mitochondrial dysfunction、ROS、GSH/GSSG、ER stress、bile acid transporter inhibition、脂滴累积、炎症因子等。  
这类指标用于判断毒性机制，而不只是判断“毒/不毒”。

### D. 转化相关指标

包括与临床 Cmax 的比较、EC50/IC50、安全窗、重复暴露后毒性是否累积、不同供体之间是否存在敏感性差异。  
HepaPredict 官网提到其系统在两周暴露中，在不高于 20× human Cmax 条件下识别了部分导致撤市或黑框警告的肝毒性药物；不过这是公司服务页面表述，最好结合对应同行评议论文一起判断。([HepaPredict AB](https://www.hepapredict.com/services-1 "Our Services — HepaPredict AB"))

## 4. 它和普通 HepG2/HepaRG 筛选有什么不同？

|模型|优点|局限|
|---|---|---|
|**HepG2**|便宜、易操作、适合初筛|CYP/转运体功能弱，代谢型毒性预测差|
|**HepaRG**|比 HepG2 更接近肝细胞，较稳定|仍是细胞系，不完全代表原代人肝细胞|
|**2D PHH**|人源原代细胞，代谢相关性好|很快去分化，长期实验能力弱|
|**3D PHH spheroids**|人源性强，长期稳定，适合慢性 DILI 和代谢毒性|成本高、供体差异大、标准化要求高|

2025 年 Scientific Reports 一篇肝类器官研究也指出，传统 HepG2、HepaRG 等单培养模型存在功能和实验窗口限制，而更复杂的人源肝类器官/共培养模型可通过氧化应激、炎症因子、ALT/AST 等多因素分析提高 DILI 预测能力。([Nature](https://www.nature.com/articles/s41598-025-95071-1 "Hepatotoxicity evaluation method through multiple-factor analysis using human pluripotent stem cell derived hepatic organoids | Scientific Reports"))

## 5. 如果你要在论文/课题中描述，可以这样写

**英文表述：**

> A comprehensive hepatotoxicity screen based on 3D primary human liver spheroids enables the assessment of both acute and chronic drug-induced liver injury by integrating cell viability, liver-specific function, metabolic competence, mitochondrial toxicity, oxidative stress, cholestatic liability, and mechanistic biomarker readouts under repeated-dose exposure conditions.

**中文解释：**

> 基于 3D 原代人肝细胞球的综合肝毒性筛选，可在重复给药条件下同时评价急性和慢性药物性肝损伤风险。该体系不仅检测细胞活性下降，还综合分析肝特异功能、药物代谢能力、线粒体损伤、氧化应激、胆汁淤积风险以及机制性生物标志物，因此比传统二维肝细胞模型更适合预测临床相关的慢性 DILI。

## 6. 最适合怎么理解它？

在 Lauschke 教授的研究体系里，**comprehensive hepatotoxicity screen** 可以理解为：

> **利用长期稳定的 3D 原代人肝细胞 spheroid 平台，对候选药物进行多剂量、多时间点、多终点的肝毒性风险和机制筛查。**

它的核心价值不是简单判断“细胞死没死”，而是尽量回答：

1. 这个化合物有没有肝毒性？
    
2. 毒性是否出现在临床相关浓度附近？
    
3. 是急性毒性还是长期重复暴露后才出现？
    
4. 毒性机制是线粒体损伤、胆汁淤积、氧化应激、代谢活化，还是炎症/纤维化相关？
    
5. 不同人源供体之间是否存在明显敏感性差异？
    

如果你是在读 HepaPredict 或 Lauschke 相关材料，看到这个词，基本就可以把它理解为 **3D PHH spheroid-based DILI risk assessment platform**，即 **基于 3D 原代人肝细胞球的药物性肝损伤综合评价平台**。



# 3D 肝细胞球可以区分经典和非经典 CYP 诱导机制

**3D spheroids distinguish canonical and noncanonical CYP induction.**  

这里的 **CYP induction** 指药物或化合物使肝细胞中 **CYP450 药物代谢酶表达/活性升高**，从而可能改变药物清除率，引起药物-药物相互作用。

## 1. Canonical CYP induction：经典 CYP 诱导

**经典诱导**通常是指化合物直接或间接激活肝细胞中的外源物感受核受体，例如：

|受体|典型诱导 CYP|
|---|---|
|**PXR**|CYP3A4、CYP2C 系列|
|**CAR**|CYP2B6、部分 CYP3A/2C|
|**AhR**|CYP1A1、CYP1A2|

例如 **rifampicin** 激活 PXR，诱导 **CYP3A4**；**phenobarbital/carbamazepine** 相关 CAR 通路；**omeprazole/β-naphthoflavone** 可诱导 AhR-CYP1A 通路。FDA/ICH 药物相互作用框架也把 CYP3A4、CYP2B6、CYP1A2 作为 PXR/CAR/AhR 介导诱导的主要标志物。([U.S. Food and Drug Administration](https://www.fda.gov/media/161199/download?utm_source=chatgpt.com "M12 Drug Interaction Studies"))

所以，**canonical CYP induction** 的逻辑是：

> 化合物 → 激活 PXR/CAR/AhR 等经典外源物感受通路 → CYP 基因转录升高 → CYP 蛋白和酶活性升高。

## 2. Noncanonical CYP induction：非经典 CYP 诱导

**非经典诱导**不是通过 PXR/CAR/AhR 这些传统通路直接激活 CYP，而是由其他细胞状态变化间接导致 CYP 表达升高。

Lauschke 相关的一篇 2023 年 Biochemical Pharmacology 论文研究了 **YAP/TEAD inhibitors** 在 2D 单层 PHH 和 3D PHH spheroids 中对 CYP 的影响。结果发现：YAP/TEAD 抑制剂在 **2D 单层培养**中导致广泛 CYP 上调，但在 **3D spheroid** 中几乎没有或只有很弱的 CYP 诱导。作者认为，这种 2D 中观察到的 CYP 上调不是经典 PXR/CAR/AhR 直接激活，而是与 2D 培养下 YAP/TEAD 信号异常、机械感受改变和肝细胞去分化状态有关。([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0006295223003465?utm_source=chatgpt.com "Comparative analysis of YAP/TEAD inhibitors in 2D and 3D ..."))

所以，**noncanonical CYP induction** 可以理解为：

> 化合物不直接激活传统核受体，而是改变肝细胞分化状态、力学感知、YAP/TEAD 信号或细胞功能成熟度，间接造成 CYP 表达变化。

## 3. 为什么 3D spheroids 能“识别”这种差异？

关键在于 **2D 和 3D 肝细胞状态不同**。

2D PHH 单层培养中，肝细胞很容易去分化，细胞极性、细胞-细胞连接、组织结构和机械环境都与体内差别较大。因此有些药物在 2D 中看起来“诱导 CYP”，但这可能是由于细胞状态被改变，而不是真正具有临床意义的药物代谢酶诱导。

3D PHH spheroids 更接近体内肝组织结构，能维持较稳定的肝细胞功能。Järvinen 等 2023 年研究显示，3D spheroid PHH 可用于检测 CYP1A1、CYP1A2、CYP2B6、CYP2C8、CYP2C9、CYP2C19、CYP2D6、CYP3A4 以及多种转运体的 mRNA、蛋白和部分酶活诱导；其中 rifampicin 对 CYP3A4 的 mRNA/蛋白诱导与临床观察较吻合。([Syddansk Universitet](https://portal.findresearcher.sdu.dk/en/publications/3d-spheroid-primary-human-hepatocytes-for-prediction-of-cytochrom/?utm_source=chatgpt.com "3D Spheroid Primary Human Hepatocytes for Prediction of ..."))

因此，3D spheroids 的价值在于：

> 如果一个化合物在 2D 中强烈诱导 CYP，但在更接近体内状态的 3D spheroid 中不诱导或弱诱导，那么这个“诱导”很可能是 2D 培养伪影或非经典机制，而不是可靠的临床 DDI 风险信号。

## 4. 放到 Lauschke 研究中的核心意思

这句话真正想表达的不是“3D 球体会产生 CYP 诱导”，而是：

**3D primary human hepatocyte spheroids 可以更准确地区分两类 CYP 诱导：**

1. **真正由 PXR/CAR/AhR 等经典药物感受通路介导的诱导**，例如 rifampicin-CYP3A4；
    
2. **由 2D 培养条件、YAP/TEAD 异常、机械环境改变或去分化状态造成的非经典 CYP 表达升高**。
    

更准确的中文表述可以写成：

> 3D 原代人肝细胞球模型能够区分经典和非经典 CYP 诱导机制。经典 CYP 诱导通常由 PXR、CAR 或 AhR 等外源物感受核受体介导，具有较明确的药物相互作用意义；而非经典 CYP 诱导可能源于细胞培养状态、YAP/TEAD 信号异常、机械感受改变或肝细胞去分化/再分化过程。与 2D 单层培养相比，3D spheroids 更能维持肝细胞成熟表型，因此有助于排除 2D 培养伪影，提高 CYP 诱导和临床药物相互作用风险预测的相关性。




# pathophysiological disease models

**利用 3D 原代人肝细胞球建立更接近人体肝脏病理生理状态的体外疾病模型，用于疾病机制研究、药物筛选和毒性评价。**
## 1. 这个词是什么意思？

**Pathophysiology = 病理生理学**，指疾病发生发展过程中，机体功能、细胞状态、代谢通路、炎症反应、组织结构等发生了什么异常变化。

所以 **pathophysiological disease models** 不是简单说“疾病模型”，而是强调这个模型能够模拟疾病中的关键病理生理过程。

也就是说，它不只是让细胞“生病”或“死亡”，而是要模拟疾病真正发生时的机制变化。

## 2. 放在 3D liver spheroids 里是什么意思？

在 **3D primary human liver spheroids** 语境中，pathophysiological disease models 通常指用 3D 原代人肝细胞球模拟真实肝脏疾病状态，例如：

|疾病模型|模拟的病理生理变化|
|---|---|
|**Steatosis / 脂肪变性**|肝细胞内脂滴积累、脂质代谢异常|
|**MASLD / NAFLD 脂肪肝**|游离脂肪酸诱导脂质沉积、胰岛素抵抗|
|**MASH / NASH 脂肪性肝炎**|脂肪变性 + 炎症 + 氧化应激 + 细胞损伤|
|**Cholestasis 胆汁淤积**|胆汁酸积累、胆汁酸转运异常、BSEP/MRP 等转运体相关损伤|
|**Fibrosis 纤维化**|星状细胞激活、胶原沉积、α-SMA、ECM 重塑|
|**Viral hepatitis 病毒性肝炎**|病毒感染、抗病毒反应、炎症通路激活|
|**Drug-induced liver injury, DILI**|药物导致的线粒体损伤、氧化应激、胆汁淤积、细胞死亡等|

所以这类模型的重点是：  
**让 3D spheroid 呈现出和真实疾病相似的功能异常、分子通路变化和组织样表型。**

## 3. 为什么 3D spheroids 适合做这种模型？

因为很多肝病不是短时间细胞死亡，而是一个长期过程，例如脂肪积累、慢性炎症、纤维化、代谢异常、胆汁酸毒性等。

普通 2D 肝细胞培养有几个问题：

|2D 模型问题|对疾病模拟的影响|
|---|---|
|细胞容易去分化|肝脏代谢功能很快下降|
|培养时间短|难以模拟慢性疾病|
|细胞-细胞连接少|缺少组织样结构|
|CYP 和转运体表达不稳定|药物代谢和胆汁淤积模型不可靠|
|缺少三维微环境|疾病表型不够接近体内|

而 3D spheroids 可以长期维持较成熟的肝细胞功能，因此更适合模拟慢性和复杂疾病状态。

## 4. 举个例子：MASH模型

**MASH model**  
中文一般译为：**MASH 模型 / 代谢功能障碍相关脂肪性肝炎模型**。

其中 **MASH = metabolic dysfunction-associated steatohepatitis**，即 **代谢功能障碍相关脂肪性肝炎**。它是过去 **NASH，non-alcoholic steatohepatitis，非酒精性脂肪性肝炎** 的新命名；2023 年多学会共识将 NAFLD 改称 MASLD，将 NASH 改称 MASH，以更强调代谢异常背景并减少旧名称中的污名化表述。([aasld.org](https://www.aasld.org/new-masld-nomenclature?utm_source=chatgpt.com "New MASLD Nomenclature"))

### 1. MASH model 是什么？

在 3D liver spheroids 语境中，**MASH model** 指用体外 3D 肝组织模型模拟 MASH 的关键病理特征：

| MASH 关键特征                    | 体外模型中对应表现                          |
| ---------------------------- | ---------------------------------- |
| **Steatosis 脂肪变性**           | 肝细胞内脂滴积累、甘油三酯升高                    |
| **Inflammation 炎症**          | TNF-α、IL-6、IL-1β、CCL2 等炎症因子升高      |
| **Hepatocyte injury 肝细胞损伤**  | ATP 下降、LDH 释放、ALT/AST 或细胞死亡指标升高    |
| **Oxidative stress 氧化应激**    | ROS 增加、GSH/GSSG 失衡、线粒体功能下降         |
| **Insulin resistance 胰岛素抵抗** | 胰岛素信号受损，如 AKT 磷酸化响应降低              |
| **Fibrosis tendency 纤维化倾向**  | 星状细胞激活、α-SMA、COL1A1、TGF-β、ECM 沉积增加 |

所以，**MASH model 不是单纯“脂肪肝模型”**。  
如果只是让肝细胞堆积脂滴，更准确叫 **steatosis model**；如果还出现炎症、损伤和纤维化相关变化，才更接近 **MASH model**。

### 2. 在 3D spheroids 中怎么建立？

常见做法是对 3D 肝细胞球施加 **MASH-inducing cocktail，MASH 诱导混合物**，通常包括：

1. **游离脂肪酸 FFA**：如 oleic acid / palmitic acid，诱导脂滴积累和脂毒性。
    
2. **高糖/果糖/胰岛素**：模拟代谢综合征、高胰岛素血症和胰岛素抵抗环境。
    
3. **炎症刺激物**：如 LPS、TNF-α、IL-1β 等，用于诱导炎症反应。
    
4. **纤维化刺激物**：如 TGF-β，尤其在模型包含肝星状细胞时用于诱导 ECM 沉积。
    
5. **多细胞共培养**：更完整的 MASH 模型通常不只含肝细胞，还会加入 Kupffer cells、hepatic stellate cells、liver sinusoidal endothelial cells 等非实质细胞，因为真实 MASH 涉及肝细胞、免疫细胞、星状细胞和内皮细胞共同作用。2026 年一篇 3D liver spheroid 研究也强调，MASLD/MASH 的特征不只涉及 hepatocytes，还包括 Kupffer cells、LSECs 和 HSCs。([The Company of Biologists](https://journals.biologists.com/bio/article/15/6/bio062552/371875/Glimpse-into-the-role-of-Kupffer-cells-in-a?utm_source=chatgpt.com "Glimpse into the role of Kupffer cells in a spheroid model ..."))
    

### 3. Lauschke 相关 3D 肝球体系中怎么理解？

Lauschke 相关研究中，较早的经典工作是 **human hepatic 3D spheroids as a model for steatosis and insulin resistance**。这篇研究用游离脂肪酸、糖和胰岛素处理 3D human hepatic spheroids，观察到脂滴积累和胰岛素抵抗样变化，并说明该体系可用于模拟可逆性脂肪变状态和筛选抗脂肪变药物。([PubMed](https://pubmed.ncbi.nlm.nih.gov/30250238/?utm_source=chatgpt.com "Human Hepatic 3D Spheroids as a Model for Steatosis and ..."))

这类模型更偏向 **MASLD/steatosis + insulin resistance model**。如果要称为完整 **MASH model**，通常还需要进一步证明炎症、肝细胞损伤和纤维化相关终点，而不只是脂肪堆积。

### 4. MASH model 的评价指标

一个比较完整的 3D MASH model，通常至少要检测这些指标：

|模块|常用检测|
|---|---|
|**脂肪变性**|Oil Red O、BODIPY、Nile Red、细胞内甘油三酯|
|**肝细胞损伤**|ATP、LDH、caspase 3/7、ALT/AST、细胞形态|
|**炎症反应**|TNF-α、IL-6、IL-1β、CCL2、NF-κB 通路|
|**氧化/线粒体应激**|ROS、GSH/GSSG、线粒体膜电位、OCR|
|**胰岛素抵抗**|p-AKT/AKT、IRS1、胰岛素刺激后的葡萄糖/脂代谢响应|
|**纤维化**|α-SMA、COL1A1、COL3A1、TGF-β、TIMP1、ECM 染色|
|**肝功能保持**|albumin、urea、CYP 活性、药物转运体表达|

### 5. 为什么 3D spheroid 适合做 MASH model？

因为 MASH 是慢性、复杂、多细胞参与的疾病。2D 单层肝细胞通常很难长期维持成熟肝功能，也难以模拟慢性脂毒性、炎症和纤维化过程。3D liver spheroids 能提供更稳定的细胞-细胞接触、组织样结构和较长培养窗口，因此更适合做长期疾病建模。2024 年的人肝 spheroid protocol 也强调，这类 3D liver spheroids 可包含多种肝细胞类型，并可用于诱导代谢性或酒精相关肝脏脂肪变、炎症和纤维化。([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC11179098/?utm_source=chatgpt.com "Protocol to generate human liver spheroids to study ... - PMC"))

### 6. 可以这样写进汇报

**英文：**

> A MASH model is an in vitro disease model designed to recapitulate key features of metabolic dysfunction-associated steatohepatitis, including hepatic steatosis, inflammation, hepatocellular injury, oxidative stress, insulin resistance, and fibrosis-related responses. In 3D liver spheroids, MASH-like phenotypes can be induced by exposing multicellular spheroids to free fatty acids, high glucose/insulin, inflammatory stimuli, and profibrotic factors.

**中文：**

> MASH 模型是用于模拟代谢功能障碍相关脂肪性肝炎的体外疾病模型，其核心特征不仅包括肝细胞脂肪变性，还包括炎症反应、肝细胞损伤、氧化应激、胰岛素抵抗以及纤维化相关改变。在 3D 肝细胞球体系中，通常通过游离脂肪酸、高糖/高胰岛素、炎症刺激和促纤维化因子诱导 MASH 样病理表型。

### 7. 最简单的理解

**MASH model = 比普通脂肪肝模型更进一步的“脂肪性肝炎模型”。**

它不是只看脂滴，而是要模拟：

**脂肪堆积 → 代谢应激 → 炎症 → 肝细胞损伤 → 纤维化倾向。**



# patient-derived models

在 Lauschke 教授相关的 **3D liver spheroids** 体系里，patient-derived models 可以理解为：

> 利用来自不同人类供体或患者的原代肝细胞，构建 3D 肝细胞球，从而保留个体间差异，用于药物代谢、肝毒性、疾病建模和个体化用药研究。

例如，不同供体的肝细胞可能具有不同的：

|个体差异|对实验的影响|
|---|---|
|**CYP 基因型不同**|药物代谢速度不同|
|**转运体表达不同**|药物摄取和外排不同|
|**疾病状态不同**|对药物或毒物敏感性不同|
|**脂肪肝/炎症背景不同**|DILI 风险不同|
|**年龄、性别、遗传背景不同**|药物反应不同|

所以 patient-derived 3D liver spheroids 的价值在于，它们不是平均化的“标准细胞”，而是可以反映不同患者之间的真实生物学差异。

它和普通细胞系模型有什么区别？

|模型|来源|优点|局限|
|---|---|---|---|
|**HepG2**|肝癌细胞系|便宜、稳定、易培养|药物代谢功能弱，不能代表真实肝脏|
|**HepaRG**|肝癌来源分化细胞系|比 HepG2 更像肝细胞|仍然是细胞系，个体差异有限|
|**2D PHH**|原代人肝细胞|人源性强|很快去分化，长期实验差|
|**3D patient-derived PHH spheroids**|患者/供体来源原代肝细胞|保留人源性、个体差异和长期功能|成本高，供体差异大，标准化难|




# MASH 肝细胞球模型在药物开发中的应用：近期案例

**systematic target identification via chemogenomics**  
中文：**通过化学基因组学进行系统性靶点识别 / 基于化学基因组学的系统性靶点发现**

## 1. 这句话是什么意思？

它指的是：  
**不是先假设一个靶点再去验证，而是用一组“已知作用靶点的小分子工具化合物”系统处理疾病模型，然后根据疾病表型是否被改善，反推出哪些靶点可能参与疾病调控。**

在 MASH spheroids 语境中，就是：

> 用带有明确靶点注释的小分子库处理 3D MASH 肝细胞球，观察哪些化合物能改善脂肪变性、炎症、肝细胞损伤或纤维化，再根据这些化合物的已知靶点推断潜在治疗靶点。

## 2. Chemogenomics 是什么？

**Chemogenomics / chemical genomics，化学基因组学** 可以理解为把“小分子化合物”和“基因/蛋白靶点”系统关联起来的一类方法。它常用于药物发现中的靶点识别、靶点验证和作用机制研究。综述文献中也把 chemogenomic methods 描述为通过药物-靶点相互作用信息来揭示潜在药物靶点的策略。([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC8844939/?utm_source=chatgpt.com "Chemogenomic Approaches for Revealing Drug Target ... - PMC"))

它和普通药筛的区别是：

|普通 phenotypic screen|Chemogenomic screen|
|---|---|
|只看哪个化合物有效|还要追踪有效化合物背后的靶点|
|得到 hit compounds|得到 candidate targets + hit compounds|
|机制可能不清楚|更容易推断作用机制|
|适合找药|适合找药 + 找靶点|

## 3. 在 MASH spheroids 中的基本流程

可以理解为这条路线：

**3D MASH spheroids → 加入靶点注释小分子库 → 检测疾病表型 → 找到能改善表型的化合物 → 根据化合物靶点反推候选靶点 → 再做验证。**

具体步骤如下：

| 步骤           | 内容                                             |
| ------------ | ---------------------------------------------- |
| **1. 建立模型**  | 构建能模拟 MASH 表型的 3D spheroids，例如脂肪变性、炎症、氧化应激、纤维化 |
| **2. 化合物筛选** | 使用已知靶点的小分子库处理 spheroids                        |
| **3. 表型检测**  | 观察脂滴、TG、LDH、ATP、ROS、炎症因子、collagen、α-SMA 等指标    |
| **4. 命中筛选**  | 找出能显著改善 MASH 表型且不明显毒杀细胞的化合物                    |
| **5. 靶点反推**  | 根据这些化合物的已知靶点，推断哪些蛋白/通路可能是疾病调控靶点                |
| **6. 正交验证**  | 用第二种结构不同的化合物、siRNA/CRISPR、过表达、通路标志物等验证靶点真实性    |

## 4. 为什么叫 systematic target identification？

因为它是**系统性**的，不是单个靶点、单个药物、单个假设。

例如传统思路可能是：

> 我怀疑 TGF-β 参与纤维化，所以测试 TGF-β 抑制剂。

而 systematic target identification 的思路是：

> 我不预设唯一靶点，而是用覆盖 GPCR、激酶、离子通道、核受体、表观遗传调控因子等多个靶点家族的小分子库，在疾病模型中系统筛选，最后从表型改善结果中发现新的候选靶点。

这在 MASH 这种复杂疾病中特别重要，因为 MASH 涉及脂代谢、炎症、线粒体应激、细胞死亡、免疫细胞、肝星状细胞和纤维化等多个病理过程，不太可能只由单一通路解释。

## 5. 近期 MASH spheroids 相关案例

Lauschke 团队相关的一项 **Advanced Science** 研究使用 **patient-derived 3D fatty liver disease / MASH model** 进行 chemogenomic screening，并报道该模型在分子和功能层面模拟 MASH 关键疾病特征；研究进一步识别出 **CHRM1–TRPM8 axis** 作为一个具有抗纤维化作用的新调控模块。([Wiley Online Library](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202407572?utm_source=chatgpt.com "Chemogenomic Screening in a Patient‐Derived 3D Fatty Liver ..."))

这个案例可以这样理解：

> 他们不是只测试某个已知抗 MASH 药，而是用患者来源 3D MASH 模型进行系统性化学扰动，通过疾病表型变化反推出新的可药物化靶点模块。

其中：

|发现|含义|
|---|---|
|**CHRM1**|muscarinic acetylcholine receptor M1，毒蕈碱型乙酰胆碱受体 M1|
|**TRPM8**|transient receptor potential melastatin 8，瞬时受体电位通道 M8|
|**CHRM1–TRPM8 axis**|一个与 MASH 纤维化调控相关的新候选通路|
|**anti-fibrotic effects**|提示该通路可能影响星状细胞激活或 ECM/胶原沉积相关过程|

## 6. 这类方法在药物开发中的价值

**systematic target identification via chemogenomics** 对 MASH 药物开发的价值主要有四点：

1. **发现新靶点**  
    可以找到传统假设驱动研究不容易想到的靶点，例如 GPCR、离子通道或代谢调控因子。
    
2. **连接疾病表型和药物作用机制**  
    不只是知道“这个化合物有效”，还能推断“它为什么有效”。
    
3. **提高人体相关性**  
    如果筛选是在 patient-derived 3D MASH spheroids 中进行，结果比单纯细胞系或动物模型更接近人类疾病背景。
    
4. **帮助后续药物开发决策**  
    候选靶点可以进一步用于 hit-to-lead、靶点验证、生物标志物开发和患者分层。
    

## 7. 可用于汇报的英文表达

> **Systematic target identification via chemogenomics enables unbiased discovery of disease-relevant and druggable targets. In MASH spheroids, annotated small-molecule libraries are screened against disease-associated phenotypes such as steatosis, inflammation, hepatocellular injury, and fibrosis. By linking phenotypic rescue to known compound–target relationships, candidate therapeutic targets can be prioritized and subsequently validated using orthogonal pharmacological and genetic approaches.**

中文对应：

> **基于化学基因组学的系统性靶点识别能够以相对无偏的方式发现与疾病相关且具有可药物化潜力的靶点。在 MASH 肝细胞球模型中，可利用带有靶点注释的小分子库筛选脂肪变性、炎症、肝细胞损伤和纤维化等疾病表型。通过将表型改善结果与化合物-靶点关系相连接，可以优先筛选候选治疗靶点，并进一步通过药理学和遗传学方法进行验证。**

最简单地说，这句话的意思就是：

**用一批“知道靶点的小分子”去系统扰动 MASH 3D 疾病模型，看哪些扰动能改善疾病表型，再倒推出哪些靶点值得开发成药。**


# 用于非侵入性、高分辨率体内肝细胞功能监测的眼内肝细胞球模型


你这句大概率是在指这篇文章/概念：

**Intraocular liver spheroids for non-invasive high-resolution in vivo monitoring of liver cell function**

中文可译为：

**用于非侵入性、高分辨率体内肝细胞功能监测的眼内肝细胞球模型**

你原句可以改成：

**Spheroids for non-invasive high-resolution in vivo monitoring of liver cell function.**

或者更完整：

**Intraocular liver spheroids enable non-invasive, high-resolution in vivo monitoring of liver cell function.**

## 1. 这是什么意思？

这不是普通的体外 3D spheroids，而是把 **liver spheroids，肝细胞球** 移植到小鼠眼睛的 **anterior chamber，眼前房** 中。因为角膜透明，研究人员可以通过显微成像直接观察这些肝细胞球在体内的状态。2024 年 Nature Communications 这篇研究说明，移植后的 liver spheroids 可以在虹膜上存活、血管化、神经化，并保持肝细胞特异性和肝样功能。([Nature](https://www.nature.com/articles/s41467-024-45122-4?utm_source=chatgpt.com "Intraocular liver spheroids for non-invasive high-resolution ..."))

简单说就是：

> 把肝细胞球放到小鼠眼睛里，利用眼睛作为“体内观察窗口”，长期、非侵入式、高分辨率地观察肝细胞功能。

## 2. 为什么要放到眼睛里？

因为肝脏在体内很难直接高分辨率观察。传统体内肝功能研究常常需要取血、活检、处死动物取组织，难以连续追踪同一批细胞的动态变化。该研究指出，体内肝功能的长期监测受限于缺乏高分辨率、非侵入式成像技术；眼前房提供了一个透明窗口，可以用 **in vivo confocal microscopy，体内共聚焦显微镜** 观察肝细胞球。([Nature](https://www.nature.com/articles/s41467-024-45122-4?utm_source=chatgpt.com "Intraocular liver spheroids for non-invasive high-resolution ..."))

也就是说，它解决的是：

|问题|眼内 liver spheroids 的优势|
|---|---|
|肝脏深在体内，不易直接观察|角膜透明，可直接成像|
|传统动物实验常需终点取样|可长期追踪同一个 spheroid|
|活检/取组织有创|非侵入式重复观察|
|难看细胞级别变化|可达到细胞分辨率成像|

## 3. 和 Volker Lauschke 有什么关系？

这篇研究的作者中包括 **Volker M. Lauschke**。它延续了他长期研究的 3D liver spheroids 技术路线，但把应用场景从 **in vitro 体外药理/毒理模型** 扩展到了 **in vivo 体内动态监测平台**。KI 新闻也介绍，这种方法利用小鼠眼睛作为窗口来研究肝功能和疾病，而不需要传统侵入性操作。([news.ki.se](https://news.ki.se/researchers-use-the-eye-as-a-window-to-study-liver-health?utm_source=chatgpt.com "Researchers use the eye as a window to study liver health"))

## 4. 它和普通 3D liver spheroids 的区别

普通 3D liver spheroids 多数是在培养板里做：

**in vitro spheroids：**  
用于药物筛选、DILI、CYP induction、MASH model、疾病建模。

这篇说的是：

**intraocular liver spheroids：**  
把 spheroids 移植进小鼠眼前房，在活体动物内观察它们的功能变化。

所以它更像一个桥梁：

> **体外 3D 肝模型 + 活体成像平台 = 可长期观察的 in vivo liver spheroid model**

## 5. 可以用于什么研究？

这个平台的潜在用途包括：

1. **长期监测肝细胞功能**  
    例如观察肝细胞存活、形态、代谢功能和功能衰退。
    
2. **研究药物反应**  
    给动物用药后，观察移植的肝细胞球如何响应药物刺激。
    
3. **研究肝病过程**  
    可用于追踪脂肪变性、炎症、毒性损伤或代谢异常等动态变化。
    
4. **减少动物终点取样**  
    因为可以在同一只动物上反复成像，减少不同时间点处死动物取样的需求。
    
5. **连接 in vitro 和 in vivo**  
    普通培养板中的 spheroids 缺少血管、神经和系统性环境；移植到眼前房后，spheroids 可以获得血管化和体内环境支持。([Nature](https://www.nature.com/articles/s41467-024-45122-4?utm_source=chatgpt.com "Intraocular liver spheroids for non-invasive high-resolution ..."))
    

## 6. 这句话可以怎么放进汇报？

Intraocular liver spheroids provide a platform for non-invasive, high-resolution in vivo monitoring of liver cell function. By transplanting liver spheroids into the anterior chamber of the mouse eye, the transparent cornea can be used as an optical window for longitudinal confocal imaging. This approach enables repeated observation of the same liver spheroids at cellular resolution, while the transplanted spheroids can engraft, become vascularized, and retain hepatocyte-specific features in vivo.

中文可写成：

眼内肝细胞球模型为非侵入性、高分辨率体内肝细胞功能监测提供了新平台。通过将肝细胞球移植到小鼠眼前房，研究人员可以利用透明角膜作为体内成像窗口，对同一肝细胞球进行长期、重复的共聚焦显微观察。该方法使移植后的肝细胞球能够在体内环境中存活、血管化，并保留一定肝细胞特异性功能。

## 7. 最简单的理解

这句话的核心是：

> **把 liver spheroids 移植到小鼠眼睛里，用眼睛透明的特点实现对肝细胞功能的长期、非侵入、高分辨率活体观察。**

它不是单纯的 3D 体外培养模型，而是把 spheroid 技术推进到 **in vivo monitoring，体内动态监测**。






# 与生物熵的关联

我理解你的想法是：  
**蒋建东提出的“生物熵/负熵机制”和“头雁分子”，本质上不是传统意义上“一个蛋白=一个靶点”的线性靶点，而更像是能牵引整个病理系统从失序状态回到有序状态的关键控制节点或靶点组合。** 这个理解是有启发性的，而且确实可以借鉴 Lauschke 教授那类 **patient-derived 3D disease model + chemogenomic screening + multi-omics validation** 的系统性靶点发现思路。

但我会加一句判断：**可以借鉴方法论，不能直接等同概念。** Lauschke 的优势是把“系统性靶点发现”落到了可测量、可验证、可重复的实验体系里；“生物熵/头雁分子”目前更偏宏观理论框架，需要进一步被实验指标化、模型化。

## 1. 我对“生物熵—头雁分子”的理解

根据 2025 年相关论文的表述，蒋建东团队提出慢性病的深层问题可以理解为机体内“熵增”或失序增加，而药物真正应靶向的是机体内在的 **neg-entropic mechanisms，负熵机制**，例如代谢稳态、免疫稳态、自我修复等；其中少数对负熵功能起决定性作用的分子被称为 **head goose molecules，HGMs，头雁分子**。他们还提出 **“HGMs–neg-entropy–dCloud” axis**，即通过干预头雁分子，激活负熵机制，产生系统性药物云效应，从而重塑疾病过程。([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2211383525007762?utm_source=chatgpt.com "Neg-entropy is the true drug target for chronic diseases"))

这个概念的关键不在“熵”这个词本身，而在于它把药物作用从：

> 单靶点阻断某一条病理通路

提升为：

> 调控关键系统节点，使疾病网络整体从混乱、炎症、代谢紊乱、纤维化等状态，转向稳态、自修复和功能恢复。

所以你说“头雁分子也是一个靶点或者靶点组合”，我认为基本方向是对的。但更准确地说，它应该是：

**具有系统牵引能力的疾病状态转换靶点。**

它不是普通靶点，而是类似：

- 系统网络中的关键控制节点；
    
- disease-modifying node，疾病修饰节点；
    
- network hub / bottleneck / master regulator；
    
- 能让多个病理表型同时改善的上游调节因子；
    
- 或者多个节点组成的“头雁靶点组合”。
    

## 2. Lauschke 教授的案例为什么值得借鉴？

Lauschke 团队在 MASH 方向的一个近期案例非常接近你想要的“系统性发现靶点”。他们建立了 **patient-derived 3D fatty liver disease / MASH model**，这个模型能反映脂肪变、炎症和纤维化等疾病终点，并且多组学结果与 **306 名 MASH 患者和 77 名对照的活检数据**有良好对应；随后他们结合高内涵成像、生化检测和 chemogenomic screening，发现了多个具有抗脂肪变、抗炎、抗纤维化作用的新靶点，其中 **CHRM1 激活和 TRPM8 抑制**表现出较强抗纤维化效应，并通过遗传学方法进一步验证。([ResearchGate](https://www.researchgate.net/publication/386212098_Chemogenomic_Screening_in_a_Patient-Derived_3D_Fatty_Liver_Disease_Model_Reveals_the_CHRM1-TRPM8_Axis_as_a_Novel_Module_for_Targeted_Intervention?utm_source=chatgpt.com "Chemogenomic Screening in a Patient‐Derived 3D Fatty Liver ..."))

这个案例的价值在于，它不是先假设“某个靶点重要”，而是从疾病模型的系统表型出发：

> 疾病模型 → 多维表型读数 → 带靶点注释的小分子库筛选 → 找到能系统性改善表型的扰动 → 反推出关键靶点 → 再做机制和遗传验证。

这和“寻找头雁分子”的思路非常相似。

## 3. 二者可以如何对接？

我认为可以这样对应：

|蒋建东理论框架|Lauschke 方法学对应物|
|---|---|
|生物熵增加|疾病模型中多维病理表型恶化，如脂肪变、炎症、纤维化、功能下降|
|负熵机制|表型被系统性逆转，如脂滴减少、炎症下降、胶原减少、肝功能恢复|
|头雁分子|能牵引多个病理终点同时改善的关键靶点或靶点组合|
|dCloud 药物云效应|多通路、多终点、多组学层面的网络重编程效应|
|系统改善|从单一 readout 改善，升级为多表型、多组学、一致性改善|

也就是说，你可以把“生物熵/头雁分子”作为**理论解释框架**，把 Lauschke 的 **3D 疾病模型 + 化学基因组学筛选**作为**实验发现框架**。

## 4. 可以借鉴的具体路线

我建议你不要直接说“我要测生物熵”，因为这个词容易被质疑为抽象。可以把它转化为一个可操作的研究路线：

**第一步：定义疾病系统失序表型。**  
例如在 MASH 中，可以把脂肪变、炎症、氧化应激、肝细胞损伤、纤维化、CYP 功能下降、白蛋白/尿素合成下降等作为“系统失序”的多维指标。

**第二步：建立能保留疾病系统性的模型。**  
这就是 Lauschke 值得借鉴的地方。普通 2D 单细胞模型太简化，难以体现系统性。3D patient-derived spheroids、类器官、多细胞共培养或器官芯片更适合寻找“头雁分子”。

**第三步：做 phenotypic chemogenomic screening。**  
不是只筛一个指标，而是用带靶点注释的小分子库，观察哪些化合物能同时改善多个疾病 readouts。

**第四步：计算“系统改善评分”。**  
例如某个候选靶点如果同时降低脂滴、炎症因子、ROS、胶原沉积，并恢复肝功能，而不是只改善一个指标，就更接近“头雁分子”。

**第五步：反推候选头雁分子。**  
如果多个不同结构的小分子指向同一靶点，且该靶点扰动能跨供体、跨批次、跨模型改善疾病表型，就可以把它列为候选 HGM。

**第六步：正交验证。**  
必须用 siRNA、CRISPR、过表达、拮抗剂/激动剂、第二类化合物、救援实验、多组学回归分析验证。Lauschke 的 CHRM1–TRPM8 案例之所以有说服力，就是因为不仅有筛选结果，还有遗传学和功能机制验证。([ResearchGate](https://www.researchgate.net/publication/386212098_Chemogenomic_Screening_in_a_Patient-Derived_3D_Fatty_Liver_Disease_Model_Reveals_the_CHRM1-TRPM8_Axis_as_a_Novel_Module_for_Targeted_Intervention?utm_source=chatgpt.com "Chemogenomic Screening in a Patient‐Derived 3D Fatty Liver ..."))

## 5. 这种借鉴的优点

**第一，符合慢性病的复杂性。**  
慢性病往往不是单一靶点疾病。MASH、糖尿病、动脉粥样硬化、神经退行性疾病、肿瘤微环境等，都涉及代谢、炎症、免疫、组织重塑和细胞死亡等多层过程。用“系统性靶点”比“单一通路靶点”更合理。

**第二，可以把中医药/天然药物的多成分、多靶点特点讲清楚。**  
蒋建东的负熵机制文章也特别强调天然药物可能通过激活一种或多种负熵机制促进机体自我修复。([工程网](https://www.engineering.org.cn/engi/EN/10.1016/j.eng.2024.05.007?utm_source=chatgpt.com "Neg-Entropy Mechanism as a Target for Natural Medicines")) 如果你研究天然产物或复方，这个框架会比传统“一药一靶点”更适配。

**第三，可以避免盲目网络药理学。**  
很多网络药理学停留在数据库预测，容易被批评为“画网络图”。如果你借鉴 Lauschke 的方法，用真实 3D 疾病模型和多终点 readouts 来筛选，再反推靶点，可信度会高很多。

**第四，有助于发现真正 disease-modifying targets。**  
头雁分子不一定是疾病中表达变化最大的分子，而可能是能改变系统状态的控制节点。Lauschke 的 CHRM1–TRPM8 案例就说明，一些并非传统 MASH 核心靶点的 GPCR/离子通道模块，也可能成为系统性干预节点。([Wiley Online Library](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202407572?utm_source=chatgpt.com "Chemogenomic Screening in a Patient‐Derived 3D Fatty Liver ..."))

**第五，有利于提出新颖课题。**  
“负熵机制 + 3D 疾病模型 + 化学基因组学 + 多组学验证”是一个比较有创新性的组合，尤其适合慢病、代谢病、炎症病、纤维化疾病。

## 6. 主要缺点和风险

**第一，“生物熵”容易被认为概念过大。**  
熵在热力学、信息论、生物学中含义不同。如果不定义清楚，审稿人可能会质疑：你测的到底是什么熵？是热力学熵、信息熵、网络熵、转录组熵，还是病理状态复杂度？所以论文里最好少用抽象口号，多用可测量指标。

**第二，“头雁分子”目前还不是国际通用术语。**  
Head goose molecules 是蒋建东团队提出的概念，有启发性，但国际审稿语境下可能需要翻译成更通用的说法，例如 **master regulators、disease-modifying targets、network control nodes、system-level therapeutic targets**。否则别人可能觉得概念化太强。

**第三，系统性改善不等于因果靶点。**  
一个化合物能改善多个表型，可能是因为它毒性降低了细胞活性、改变了代谢状态，或者存在 off-target effects。要证明它对应“头雁分子”，必须有遗传学验证和多化合物一致性证据。

**第四，3D 模型也不是完整人体。**  
Lauschke 的模型虽然比 2D 强，但仍然缺少完整免疫系统、肠-肝轴、内分泌系统、血流动力学、神经调控和长期组织重塑。因此 3D spheroids 适合发现和验证候选靶点，但不能直接证明临床有效。

**第五，筛选成本和数据分析难度高。**  
多细胞 3D 模型、患者来源样本、高内涵成像、多组学和 chemogenomic library 都需要较高实验平台和统计能力。若条件不足，容易变成“小样本、多指标、解释过度”。

**第六，容易混淆“多靶点”与“好靶点”。**  
不是作用越多越好。系统性靶点必须满足：疗效窗口足够、安全性可控、作用方向明确、跨模型可重复、与疾病机制相关。否则“多靶点”也可能意味着副作用复杂。

## 7. 我建议你采用的表达方式

不要直接写：

> 生物熵就是靶点，头雁分子就是药物靶点。

这样容易被质疑。

更稳妥的写法是：

> 蒋建东提出的生物熵/负熵机制和头雁分子概念，为慢性复杂疾病的系统性药物发现提供了理论框架。其核心思想是，慢性病治疗不应仅局限于阻断单一病理通路，而应识别能够牵引代谢、炎症、免疫和组织修复等多维网络整体改善的关键调控节点。Lauschke 教授团队基于患者来源 3D MASH 模型的化学基因组学筛选，为这一思路提供了可借鉴的方法学路径：通过疾病相关多终点表型筛选、靶点注释小分子扰动、多组学比对和遗传学验证，系统识别具有疾病修饰作用的候选靶点或靶点组合。

## 8. 我的总判断

我认为你这个联想是有价值的。  
**Lauschke 的工作可以作为“如何把系统性靶点发现做实”的方法学参考；蒋建东的生物熵和头雁分子概念可以作为“为什么要找系统性靶点”的理论框架。**

但真正写课题或论文时，关键是要完成一次“概念降维”：

> 把“生物熵”降维成可测量的多维疾病失序指标；  
> 把“负熵机制”降维成可验证的表型逆转和网络重编程；  
> 把“头雁分子”降维成可药物化、可遗传验证、可跨模型重复的系统控制靶点。

这样就既保留了蒋建东理论的高度，又避免停留在哲学化表述；同时也能借鉴 Lauschke 的技术路线，让你的研究更容易被现代药理学、系统生物学和药物开发领域接受。

---

## 关联笔记（AI 自动标注，供网络图可视化）
- [[2026.7.26-细胞稳态与衰老北京研究中心年中工作会议-打勾讲者整理与课题启发]]（共享主题：AI4S、ODE建模、T2DM、多组学）
- [[复杂性科学与涌现的模拟——细胞建模课题的困惑与解答]]（共享主题：AI4S、ODE建模、多组学、多靶点）
- [[药研视界｜从“数字细胞”到AI虚拟细胞： 虚拟细胞的研究进展与未来应用]]（共享主题：AI4S、ODE建模、多组学、多靶点）
- [[00-毕设工作交接汇报-2026-09-18]]（共享主题：ODE建模、T2DM、多组学、多靶点）
- [[干实验记录汇总]]（共享主题：ODE建模、T2DM、多组学、多靶点）
- [[毕设课题方案]]（共享主题：ODE建模、T2DM、多组学、多靶点）
- [[玻尔对于我的课题的建议]]（共享主题：ODE建模、T2DM、多组学、多靶点）
- [[答辩讲稿]]（共享主题：ODE建模、T2DM、多组学、多靶点）
- [[05-批注处理-2026-09-16]]（共享主题：AI4S、ODE建模、复杂系统、多组学）
- [[多组学驱动建模与干湿闭环设计蓝图]]（共享主题：AI4S、ODE建模、复杂系统、多组学）
- [[00-我的思考]]（共享主题：AI4S、ODE建模、复杂系统、多组学）
