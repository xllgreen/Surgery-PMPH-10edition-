---
name: Surgery-PMPH-10edition
version: 1.0.0
description: 基于人民卫生出版社《外科学》第10版 — 240 项外科与急危重症临床技能注册表
author: PMPH
categories: 17
skills: 240
categories:
  - 急诊与复苏(15) | 创伤与骨折(28) | 普通外科与腹部急症(25)
  - 肝胆胰脾外科(25) | 胃肠外科(10) | 泌尿外科(26)
  - 血管外科(7) | 烧伤与整形(8) | 肿瘤外科与综合治疗(16)
  - 围手术期管理(20) | 麻醉与疼痛(11) | 内分泌与代谢(6)
  - 感染与免疫(7) | 影像与介入(9) | 康复与功能评估(12)
  - 风湿与脊柱疾病(5) | 其他专科技能(10)
---

# SKILL 核心配置

本文件为所有技能的注册表，每个技能条目包含：
- **name**: 技能标识符（对应同名文件夹）
- **display**: 中文显示名称
- **category**: 所属分类
- **trigger**: 触发条件/使用时机
- **ref**: 详细文档路径

---

## 🚑 急诊与复苏 (15)

- name: cpr-contraindicated-drugs-and-indications
  display: CPR禁忌药物与适应症
  trigger: 存在特定电解质紊乱/心律失常/中毒时评估CPR用药
  ref: cpr-contraindicated-drugs-and-indications/SKILL.md

- name: real-time-cpr-quality-monitoring
  display: 实时CPR质量监测
  trigger: 心搏骤停患者接受胸外按压时
  ref: real-time-cpr-quality-monitoring/SKILL.md

- name: defibrillation-operation-protocol
  display: 电除颤操作规范
  trigger: 心搏骤停出现室颤/无脉性室速时
  ref: defibrillation-operation-protocol/SKILL.md

- name: hemorrhagic-shock-transfusion-guidelines
  display: 失血性休克输血指南
  trigger: 大量失血导致低血容量性休克
  ref: hemorrhagic-shock-transfusion-guidelines/SKILL.md

- name: shock-volume-resuscitation-plasma-substitute
  display: 休克容量复苏与血浆代用品应用
  trigger: 低血容量性/失血性/感染性休克早期
  ref: shock-volume-resuscitation-plasma-substitute/SKILL.md

- name: bp-cvp-guided-fluid-resuscitation
  display: BP/CVP导向液体复苏
  trigger: 休克/低血容量/术后血流动力学不稳定
  ref: bp-cvp-guided-fluid-resuscitation/SKILL.md

- name: shock-microcirculation-staging-analysis
  display: 休克微循环分期分析
  trigger: 出现有效循环血容量锐减和组织灌注不足
  ref: shock-microcirculation-staging-analysis/SKILL.md

- name: damage-control-resuscitation
  display: 损伤控制复苏策略
  trigger: 严重创伤伴大出血/致死三联征风险
  ref: damage-control-resuscitation/SKILL.md

- name: tetanus-comprehensive-treatment
  display: 破伤风综合治疗
  trigger: 外伤后出现张口困难/肌强直/阵发性痉挛
  ref: tetanus-comprehensive-treatment/SKILL.md

- name: hyperkalemia-emergency-management
  display: 高钾血症急救处理
  trigger: 血钾>6.5mmol/L或ECG高钾改变
  ref: hyperkalemia-emergency-management/SKILL.md

- name: hypocalcemia-emergency-management
  display: 低钙血症急救处理
  trigger: 血钙<2.25mmol/L伴手足抽搐/喉痉挛
  ref: hypocalcemia-emergency-management/SKILL.md

- name: metabolic-acidosis-bicarbonate-therapy
  display: 代谢性酸中毒补碱治疗
  trigger: pH<7.2且HCO₃⁻<10mmol/L
  ref: metabolic-acidosis-bicarbonate-therapy/SKILL.md

- name: thyroid-storm-recognition-and-multimodal-treatment
  display: 甲状腺危象识别与治疗
  trigger: 甲亢术后12-36h出现高热/心动过速
  ref: thyroid-storm-recognition-and-multimodal-treatment/SKILL.md

- name: thyroid-postop-airway-emergency-management
  display: 甲状腺术后气道紧急处理
  trigger: 甲状腺术后48h内呼吸困难伴颈部肿胀
  ref: thyroid-postop-airway-emergency-management/SKILL.md

- name: ample-history-taking-in-secondary-trauma-assessment
  display: AMPLE病史采集法则
  trigger: 创伤患者完成初次评估后需系统采集病史
  ref: ample-history-taking-in-secondary-trauma-assessment/SKILL.md

---

## 🦴 创伤与骨折 (28)

- name: crash-plan-systematic-physical-examination
  display: C-R-A-S-H-P-L-A-N系统性查体
  trigger: 创伤患者完成ABCDE初次评估后
  ref: crash-plan-systematic-physical-examination/SKILL.md

- name: abdominal-trauma-classification
  display: 腹部创伤分类
  trigger: 腹部外伤史需明确损伤性质
  ref: abdominal-trauma-classification/SKILL.md

- name: open-fracture-debridement
  display: 开放性骨折清创术
  trigger: Gustilo I-III度开放性骨折伤后24h内
  ref: open-fracture-debridement/SKILL.md

- name: colles-fracture-reduction-and-immobilization
  display: Colles骨折复位与固定
  trigger: 伸直型桡骨远端骨折非手术治疗指征
  ref: colles-fracture-reduction-and-immobilization/SKILL.md

- name: patellar-fracture-management-principles
  display: 髌骨骨折处理原则
  trigger: 确诊髌骨骨折后
  ref: patellar-fracture-management-principles/SKILL.md

- name: pelvic-fracture-classification-and-clinical-features
  display: 骨盆骨折分类与临床特征
  trigger: 高能量暴力致骨盆疼痛/活动受限
  ref: pelvic-fracture-classification-and-clinical-features/SKILL.md

- name: neer-classification-for-proximal-humeral-fractures
  display: 肱骨近端骨折Neer分型
  trigger: 影像学确认肱骨近端骨折
  ref: neer-classification-for-proximal-humeral-fractures/SKILL.md

- name: femoral-neck-fracture-classification-and-prognosis
  display: 股骨颈骨折分型与预后
  trigger: 成人股骨颈骨折确诊后
  ref: femoral-neck-fracture-classification-and-prognosis/SKILL.md

- name: tibial-shaft-fracture-healing-risk-assessment
  display: 胫骨干骨折愈合风险评估
  trigger: 胫骨中下1/3骨折
  ref: tibial-shaft-fracture-healing-risk-assessment/SKILL.md

- name: femoral-shaft-fracture-neurovascular-risk
  display: 股骨干骨折移位与神经血管风险评估
  trigger: 确诊股骨干骨折
  ref: femoral-shaft-fracture-neurovascular-risk/SKILL.md

- name: cervical-spine-fracture-classification
  display: 颈椎骨折分类
  trigger: 颈部外伤史影像提示颈椎异常
  ref: cervical-spine-fracture-classification/SKILL.md

- name: lumbar-disc-herniation-typing-and-treatment
  display: 腰椎间盘突出分型与治疗
  trigger: 腰腿痛伴影像证实椎间盘突出
  ref: lumbar-disc-herniation-typing-and-treatment/SKILL.md

- name: compartment-syndrome-diagnosis-emergency
  display: 骨筋膜室综合征诊断与紧急处理
  trigger: 肱骨髁上/胫骨上1/3骨折高危因素
  ref: compartment-syndrome-diagnosis-emergency/SKILL.md

- name: supracondylar-fracture-compartment-syndrome
  display: 肱骨髁上骨折并发骨筋膜室综合征
  trigger: 儿童肱骨髁上骨折后骨筋膜室高压征象
  ref: supracondylar-fracture-compartment-syndrome/SKILL.md

- name: ponseti-method-for-clubfoot
  display: Ponseti马蹄内翻足矫形法
  trigger: ≤9月龄先天性马蹄内翻足婴儿
  ref: ponseti-method-for-clubfoot/SKILL.md

- name: adolescent-idiopathic-scoliosis-bracing-protocol
  display: 青少年特发性脊柱侧凸支具治疗
  trigger: Cobb角25°-40°骨骼未成熟者
  ref: adolescent-idiopathic-scoliosis-bracing-protocol/SKILL.md

- name: congenital-muscular-torticollis-nonsurgical-management
  display: 先天性肌性斜颈非手术管理
  trigger: 1岁以内先天性肌性斜颈婴儿
  ref: congenital-muscular-torticollis-nonsurgical-management/SKILL.md

- name: ddh-radiographic-diagnosis
  display: 发育性髋关节脱位影像诊断
  trigger: ≥3个月婴幼儿疑似DDH
  ref: ddh-radiographic-diagnosis/SKILL.md

- name: young-burgess-pelvic-fracture-classification
  display: Young-Burgess骨盆骨折分型
  trigger: 急性骨盆骨折急诊评估
  ref: young-burgess-pelvic-fracture-classification/SKILL.md

- name: tlics-score-based-thoracolumbar-fracture-management
  display: TLICS评分胸腰椎骨折决策
  trigger: 需评估胸腰椎骨折手术指征
  ref: tlics-score-based-thoracolumbar-fracture-management/SKILL.md

- name: seddon-peripheral-nerve-injury-classification
  display: Seddon周围神经损伤分类
  trigger: 肢体感觉运动障碍怀疑神经损伤
  ref: seddon-peripheral-nerve-injury-classification/SKILL.md

- name: common-peroneal-nerve-injury-management
  display: 腓总神经损伤管理
  trigger: 腓骨近端骨折/压迫史伴足下垂
  ref: common-peroneal-nerve-injury-management/SKILL.md

- name: peripheral-nerve-compression-syndrome-diagnosis
  display: 周围神经卡压综合征诊断
  trigger: 无外伤史的慢性神经症状
  ref: peripheral-nerve-compression-syndrome-diagnosis/SKILL.md

- name: peripheral-nerve-block-techniques-and-complication-management
  display: 外周神经阻滞与并发症管理
  trigger: 需较大范围局麻且不宜全麻
  ref: peripheral-nerve-block-techniques-and-complication-management/SKILL.md

- name: cervical-spine-anatomy-and-mobility-analysis
  display: 颈椎解剖与活动度分析
  trigger: 颈肩痛需评估颈椎生物力学负荷
  ref: cervical-spine-anatomy-and-mobility-analysis/SKILL.md

- name: spinal-cord-injury-classification-and-prognosis
  display: 脊髓损伤分类与预后
  trigger: 脊柱外伤伴神经功能障碍
  ref: spinal-cord-injury-classification-and-prognosis/SKILL.md

- name: fracture-specific-signs-diagnosis
  display: 骨折特有体征诊断
  trigger: 疑似骨折出现畸形/异常活动/骨擦音
  ref: fracture-specific-signs-diagnosis/SKILL.md

- name: knee-ligament-injury-diagnosis
  display: 膝关节韧带损伤诊断
  trigger: 膝关节外伤史伴肿胀/疼痛/不稳定
  ref: knee-ligament-injury-diagnosis/SKILL.md

---

## 🩺 普通外科与腹部急症 (25)

- name: acute-appendicitis-in-special-populations
  display: 特殊人群急性阑尾炎
  trigger: 新生儿/小儿/孕妇/老年/HIV患者疑似阑尾炎
  ref: acute-appendicitis-in-special-populations/SKILL.md

- name: acute-appendicitis-pathological-classification-and-prognosis
  display: 急性阑尾炎病理分型与转归
  trigger: 确诊急性阑尾炎需病理分型
  ref: acute-appendicitis-pathological-classification-and-prognosis/SKILL.md

- name: appendix-anatomical-variants
  display: 阑尾解剖变异与症状定位
  trigger: 腹痛位置不典型需推断阑尾方位
  ref: appendix-anatomical-variants/SKILL.md

- name: appendectomy-stump-management
  display: 阑尾切除术残端处理
  trigger: 处理阑尾残端及系膜时
  ref: appendectomy-stump-management/SKILL.md

- name: strangulated-bowel-obstruction-emergency
  display: 绞窄性肠梗阻识别与急诊处置
  trigger: 持续剧痛/早期休克/血性呕吐物
  ref: strangulated-bowel-obstruction-emergency/SKILL.md

- name: adhesive-small-bowel-obstruction-prevention-and-surgical-management
  display: 粘连性小肠梗阻预防与手术
  trigger: 腹部手术史出现机械性肠梗阻
  ref: adhesive-small-bowel-obstruction-prevention-and-surgical-management/SKILL.md

- name: intussusception-enema-reduction
  display: 肠套叠灌肠复位
  trigger: 阵发性哭闹/果酱样便/病程<48h
  ref: intussusception-enema-reduction/SKILL.md

- name: volvulus-three-factor-risk-assessment
  display: 肠扭转三要素风险评估
  trigger: 闭袢性肠梗阻高危背景伴急性腹痛
  ref: volvulus-three-factor-risk-assessment/SKILL.md

- name: external-hernia-classification-emergency
  display: 腹外疝临床分型与紧急处理
  trigger: 疝块回纳困难/持续疼痛
  ref: external-hernia-classification-emergency/SKILL.md

- name: femoral-hernia-emergency-surgery
  display: 股疝诊断与紧急手术
  trigger: 确诊股疝
  ref: femoral-hernia-emergency-surgery/SKILL.md

- name: incarcerated-inguinal-hernia-manual-reduction
  display: 嵌顿性腹股沟疝手法复位
  trigger: 嵌顿≤4h无腹膜刺激征
  ref: incarcerated-inguinal-hernia-manual-reduction/SKILL.md

- name: inguinal-hernia-differential-diagnosis
  display: 腹股沟疝鉴别诊断
  trigger: 腹股沟区可复性肿块
  ref: inguinal-hernia-differential-diagnosis/SKILL.md

- name: external-hernia-etiology-risk
  display: 腹外疝病因风险评估
  trigger: 腹壁包块/术后切口异常/高腹压
  ref: external-hernia-etiology-risk/SKILL.md

- name: postoperative-wound-dehiscence-emergency
  display: 术后切口裂开应急处理
  trigger: 术后切口突然松开/液体溢出
  ref: postoperative-wound-dehiscence-emergency/SKILL.md

- name: postoperative-fever-differential-diagnosis
  display: 术后发热鉴别诊断
  trigger: 术后体温≥37℃
  ref: postoperative-fever-differential-diagnosis/SKILL.md

- name: secondary-peritonitis-etiology-and-pathogens
  display: 继发性腹膜炎病因与病原菌
  trigger: 空腔脏器穿孔/外伤/术后污染
  ref: secondary-peritonitis-etiology-and-pathogens/SKILL.md

- name: primary-peritonitis-risk-assessment
  display: 原发性腹膜炎风险评估
  trigger: 无腹腔原发病灶但出现腹膜炎
  ref: primary-peritonitis-risk-assessment/SKILL.md

- name: interintestinal-abscess-diagnosis
  display: 肠间脓肿诊断与治疗
  trigger: 发热/腹痛/影像示肠壁间距增宽
  ref: interintestinal-abscess-diagnosis/SKILL.md

- name: intra-abdominal-abscess-drainage
  display: 腹腔脓肿分类诊断与引流
  trigger: 持续发热/腹痛/腹腔占位
  ref: intra-abdominal-abscess-drainage/SKILL.md

- name: abdominal-compartment-syndrome-diagnosis-and-management
  display: 腹腔间隔室综合征诊断与管理
  trigger: 腹内压≥20mmHg伴器官功能障碍
  ref: abdominal-compartment-syndrome-diagnosis-and-management/SKILL.md

- name: diagnostic-peritoneal-lavage-and-paracentesis
  display: 诊断性腹腔穿刺与灌洗
  trigger: 闭合性腹部损伤需明确有无内脏损伤
  ref: diagnostic-peritoneal-lavage-and-paracentesis/SKILL.md

- name: short-bowel-syndrome-staged-management
  display: 短肠综合征分阶段管理
  trigger: 广泛小肠切除术后
  ref: short-bowel-syndrome-staged-management/SKILL.md

- name: crohns-disease-surgical-management
  display: 克罗恩病外科管理
  trigger: 克罗恩病并发症出现
  ref: crohns-disease-surgical-management/SKILL.md

- name: breast-abscess-incision-and-drainage
  display: 乳腺脓肿切开引流
  trigger: 抗生素治疗无效的乳房脓肿
  ref: breast-abscess-incision-and-drainage/SKILL.md

- name: shang-shi-xing-yu-kong-qiang-zang-qi-sun-shang-jian-bie
  display: 实质性与空腔脏器损伤鉴别
  trigger: 腹部创伤出现腹痛/休克/腹膜刺激征
  ref: shang-shi-xing-yu-kong-qiang-zang-qi-sun-shang-jian-bie/SKILL.md

---

## 🫁 肝胆胰脾外科 (25)

- name: extrahepatic-bile-duct-stone-diagnosis-strategy
  display: 肝外胆管结石诊断策略
  trigger: 腹痛/寒战高热/黄疸疑似胆道梗阻
  ref: extrahepatic-bile-duct-stone-diagnosis-strategy/SKILL.md

- name: common-bile-duct-exploration-t-drainage
  display: 胆总管切开取石与T管引流
  trigger: 胆总管结石满足手术条件
  ref: common-bile-duct-exploration-t-drainage/SKILL.md

- name: gallbladder-cancer-risk-assessment
  display: 胆囊癌风险评估
  trigger: 胆囊结石/息肉/胆道疾病史
  ref: gallbladder-cancer-risk-assessment/SKILL.md

- name: gallbladder-cancer-staging-guided-surgery
  display: 胆囊癌分期指导手术
  trigger: 明确AJCC分期且可耐受手术
  ref: gallbladder-cancer-staging-guided-surgery/SKILL.md

- name: cholesterol-gallstone-formation-mechanism
  display: 胆固醇结石形成机制
  trigger: 分析胆石病风险/预防策略
  ref: cholesterol-gallstone-formation-mechanism/SKILL.md

- name: iatrogenic-bile-duct-injury-prevention
  display: 预防医源性胆管损伤
  trigger: 胆道区域手术时
  ref: iatrogenic-bile-duct-injury-prevention/SKILL.md

- name: hepatic-echinococcosis-imaging-classification
  display: 肝棘球蚴病诊断与影像分型
  trigger: 畜牧区居住史伴肝占位
  ref: hepatic-echinococcosis-imaging-classification/SKILL.md

- name: pulmonary-echinococcosis-diagnosis-and-surgery
  display: 肺棘球蚴病诊断与手术
  trigger: 流行区/家畜接触史伴典型囊肿
  ref: pulmonary-echinococcosis-diagnosis-and-surgery/SKILL.md

- name: gan-ji-qiu-you-bing-bing-yin-yu-bing-li-te-zheng
  display: 肝棘球蚴病病因与病理特征
  trigger: 来自畜牧区有犬羊接触史
  ref: gan-ji-qiu-you-bing-bing-yin-yu-bing-li-te-zheng/SKILL.md

- name: liver-trauma-nonoperative-interventional
  display: 肝外伤非手术与介入治疗
  trigger: 血流动力学稳定/无腹膜炎
  ref: liver-trauma-nonoperative-interventional/SKILL.md

- name: gan-waishang-shoushu-zhixue-yu-tancha
  display: 肝外伤手术止血与探查
  trigger: 肝外伤活动性出血血流动力学不稳定
  ref: gan-waishang-shoushu-zhixue-yu-tancha/SKILL.md

- name: gan-wai-shang-qing-chuang-feng-he-shu
  display: 肝外伤清创缝合术
  trigger: 肝裂伤不深/出血不多/血流动力学稳定
  ref: gan-wai-shang-qing-chuang-feng-he-shu/SKILL.md

- name: aosc-emergency-management
  display: 急性梗阻性化脓性胆管炎急诊管理
  trigger: Reynolds五联征/胆道压力>25cmH₂O
  ref: aosc-emergency-management/SKILL.md

- name: acute-pancreatitis-diagnosis-triad
  display: 急性胰腺炎诊断三联征
  trigger: 急性上腹痛+酶学+影像三项中两项
  ref: acute-pancreatitis-diagnosis-triad/SKILL.md

- name: acute-pancreatitis-severity-classification
  display: 急性胰腺炎严重程度分级
  trigger: 确诊急性胰腺炎后
  ref: acute-pancreatitis-severity-classification/SKILL.md

- name: mods-in-acute-pancreatitis-clinical-correlation
  display: 急性胰腺炎MODS临床关联
  trigger: 重症胰腺炎出现多器官功能障碍
  ref: mods-in-acute-pancreatitis-clinical-correlation/SKILL.md

- name: pancreatic-pseudocyst-management
  display: 胰腺假性囊肿管理
  trigger: 提及胰腺假性囊肿/PPC
  ref: pancreatic-pseudocyst-management/SKILL.md

- name: whipple-triad-diagnosis-for-insulinoma
  display: Whipple三联征诊断胰岛素瘤
  trigger: 空腹/运动后低血糖症状
  ref: whipple-triad-diagnosis-for-insulinoma/SKILL.md

- name: insulinoma-localization-diagnosis
  display: 胰岛素瘤定位诊断
  trigger: 定性诊断完成需制定手术方案
  ref: insulinoma-localization-diagnosis/SKILL.md

- name: roux-en-y-biliary-enteric-anastomosis
  display: Roux-en-Y胆肠吻合术
  trigger: 胆总管远端梗阻无法解除
  ref: roux-en-y-biliary-enteric-anastomosis/SKILL.md

- name: congenital-bile-duct-dilation-classification
  display: 先天性胆管扩张症分型
  trigger: 腹痛/黄疸/腹部肿块影像示胆管扩张
  ref: congenital-bile-duct-dilation-classification/SKILL.md

- name: biliary-atresia-diagnosis-and-differential
  display: 胆道闭锁诊断与鉴别
  trigger: 新生儿持续性黄疸/陶土便
  ref: biliary-atresia-diagnosis-and-differential/SKILL.md

- name: psc-pharmacotherapy-guideline
  display: 原发性硬化性胆管炎药物治疗
  trigger: 确诊PSC需启动药物治疗
  ref: psc-pharmacotherapy-guideline/SKILL.md

- name: non-surgical-treatment-of-ascariasis-cholangiopathy
  display: 胆道蛔虫病非手术治疗
  trigger: 确诊胆道蛔虫病无严重并发症
  ref: non-surgical-treatment-of-ascariasis-cholangiopathy/SKILL.md

- name: ganshijiuqiaobing-shoushu-zhiliao-yu-shushi-xuanze
  display: 肝棘球蚴病手术术式选择
  trigger: 肝包虫病囊肿巨大/出现并发症
  ref: ganshijiuqiaobing-shoushu-zhiliao-yu-shushi-xuanze/SKILL.md

---

## 🩻 胃肠外科 (10)

- name: early-gastric-cancer-endoscopic-treatment-indications
  display: 早期胃癌内镜治疗指征
  trigger: 评估早期胃癌行EMR/ESD
  ref: early-gastric-cancer-endoscopic-treatment-indications/SKILL.md

- name: gastric-cancer-tnm-staging-8th-edition
  display: 胃癌TNM第八版分期
  trigger: 胃癌组织学确诊需完整分期
  ref: gastric-cancer-tnm-staging-8th-edition/SKILL.md

- name: gastric-cancer-lymph-node-metastasis-pathway-and-grouping
  display: 胃癌淋巴结转移途径与分组
  trigger: 胃癌淋巴结转移评估/手术规划
  ref: gastric-cancer-lymph-node-metastasis-pathway-and-grouping/SKILL.md

- name: colorectal-cancer-tnm-staging-prognosis
  display: 结直肠癌TNM分期与预后
  trigger: 结直肠癌确诊需分期评估
  ref: colorectal-cancer-tnm-staging-prognosis/SKILL.md

- name: gerd-diagnostic-criteria
  display: GERD诊断标准
  trigger: 烧心/反流症状需明确诊断
  ref: gerd-diagnostic-criteria/SKILL.md

- name: gerd-surgical-indications-assessment
  display: GERD手术指征评估
  trigger: 药物治疗失败/严重并发症
  ref: gerd-surgical-indications-assessment/SKILL.md

- name: heller-shou-shu-zhi-liao-ben-men-shi-chi-huan-zheng
  display: Heller手术治疗贲门失弛缓症
  trigger: 确诊贲门失弛缓症非手术无效
  ref: heller-shou-shu-zhi-liao-ben-men-shi-chi-huan-zheng/SKILL.md

- name: duodenal-stasis-imaging-diagnosis
  display: 十二指肠淤滞症影像诊断
  trigger: 餐后呕吐含胆汁胃内容物
  ref: duodenal-stasis-imaging-diagnosis/SKILL.md

- name: chu-kou-geng-zu-xing-bian-mi-wai-ke-chu-li
  display: 出口梗阻型便秘外科处理
  trigger: 慢性便秘明确出口梗阻保守无效
  ref: chu-kou-geng-zu-xing-bian-mi-wai-ke-chu-li/SKILL.md

- name: zhi-chang-zhi-zhen-biao-zhun-cao-zuo
  display: 直肠指诊标准操作
  trigger: 便血/排便习惯改变/肛门疼痛
  ref: zhi-chang-zhi-zhen-biao-zhun-cao-zuo/SKILL.md

---

## 🫘 泌尿外科 (26)

- name: renal-cell-carcinoma-surgical-selection-criteria
  display: 肾细胞癌手术方式选择
  trigger: 肾癌TNM分期完成需决定术式
  ref: renal-cell-carcinoma-surgical-selection-criteria/SKILL.md

- name: renal-aml-diagnosis-and-treatment-threshold
  display: 肾AML诊断与治疗阈值
  trigger: 肾脏良性肿瘤含脂肪成分
  ref: renal-aml-diagnosis-and-treatment-threshold/SKILL.md

- name: renal-cortical-abscess-diagnosis-and-treatment
  display: 肾皮质脓肿诊断与治疗
  trigger: 畏寒发热/腰痛/肋脊角叩痛
  ref: renal-cortical-abscess-diagnosis-and-treatment/SKILL.md

- name: renal-injury-imaging-indications
  display: 肾损伤影像学检查指征
  trigger: 腹部/背部创伤伴血尿
  ref: renal-injury-imaging-indications/SKILL.md

- name: cystourethroscopy-indications-contraindications
  display: 膀胱尿道镜检查评估
  trigger: 需直接可视化检查尿道/膀胱
  ref: cystourethroscopy-indications-contraindications/SKILL.md

- name: urinary-stone-composition-and-imaging-characteristics
  display: 尿路结石成分与影像特征
  trigger: 诊断为泌尿系统结石
  ref: urinary-stone-composition-and-imaging-characteristics/SKILL.md

- name: upper-urinary-tract-stone-diagnosis-workflow
  display: 上尿路结石诊断流程
  trigger: 活动相关腰痛/血尿/肾绞痛
  ref: upper-urinary-tract-stone-diagnosis-workflow/SKILL.md

- name: urinary-stone-individualized-treatment
  display: 尿路结石个体化治疗
  trigger: 完成结石诊断评估后
  ref: urinary-stone-individualized-treatment/SKILL.md

- name: shang-niao-lu-geng-zu-shen-nei-an-quan-fa-ji-zhi
  display: 上尿路梗阻肾内安全阀机制
  trigger: 急性尿路梗阻肾盂压力升高
  ref: shang-niao-lu-geng-zu-shen-nei-an-quan-fa-ji-zhi/SKILL.md

- name: wu-chuang-zhen-duan-niao-lu-shang-pi-zhong-liu
  display: 无创诊断尿路上皮肿瘤
  trigger: 中老年人无痛性血尿
  ref: wu-chuang-zhen-duan-niao-lu-shang-pi-zhong-liu/SKILL.md

- name: qian-niao-dao-shang-sun-zhen-duan
  display: 前尿道损伤诊断
  trigger: 尿道滴血/排尿困难/会阴血肿
  ref: qian-niao-dao-shang-sun-zhen-duan/SKILL.md

- name: anterior-urethral-injury-classification-and-prognosis
  display: 前尿道损伤分类与预后
  trigger: 骑跨伤/器械操作史尿道出血
  ref: anterior-urethral-injury-classification-and-prognosis/SKILL.md

- name: bladder-cancer-recurrence-and-metastasis-patterns
  display: 膀胱癌复发与转移模式
  trigger: 非肌层浸润性膀胱癌术后
  ref: bladder-cancer-recurrence-and-metastasis-patterns/SKILL.md

- name: prostate-cancer-gleason-grading-and-risk-stratification
  display: 前列腺癌Gleason分级与风险分层
  trigger: 穿刺确诊前列腺腺泡腺癌
  ref: prostate-cancer-gleason-grading-and-risk-stratification/SKILL.md

- name: acute-bacterial-cystitis-management
  display: 急性细菌性膀胱炎管理
  trigger: 女性突发尿频尿急尿痛终末血尿
  ref: acute-bacterial-cystitis-management/SKILL.md

- name: urinary-tract-infection-bacterial-culture-diagnosis
  display: 尿路感染细菌培养诊断
  trigger: 膀胱刺激症状需留取尿标本
  ref: urinary-tract-infection-bacterial-culture-diagnosis/SKILL.md

- name: gonococcal-vs-nongonococcal-urethritis-differentiation
  display: 淋菌性与非淋菌性尿道炎鉴别
  trigger: 不洁性行为史尿道分泌物
  ref: gonococcal-vs-nongonococcal-urethritis-differentiation/SKILL.md

- name: luts-classification-and-clinical-interpretation
  display: 下尿路症状分类与解读
  trigger: 排尿频率增加/尿急/排尿困难
  ref: luts-classification-and-clinical-interpretation/SKILL.md

- name: urinary-pain-classification-and-localization
  display: 泌尿系统疼痛分类与定位
  trigger: 泌尿/男生殖系统区域疼痛
  ref: urinary-pain-classification-and-localization/SKILL.md

- name: anal-abscess-etiology-and-pathogenesis
  display: 肛周脓肿病因与发病机制
  trigger: 肛门局部红肿热痛
  ref: anal-abscess-etiology-and-pathogenesis/SKILL.md

- name: perianal-abscess-classification-and-surgical-planning
  display: 肛周脓肿分类与手术规划
  trigger: 临床确认肛周脓肿
  ref: perianal-abscess-classification-and-surgical-planning/SKILL.md

- name: perianal-abscess-surgical-management
  display: 肛周脓肿手术管理
  trigger: 已形成肛周脓肿需手术
  ref: perianal-abscess-surgical-management/SKILL.md

- name: anal-lesion-clock-positioning
  display: 肛门病变时钟定位法
  trigger: 肛门视诊/指诊发现病变
  ref: anal-lesion-clock-positioning/SKILL.md

- name: rectal-prolapse-classification-and-pathogenesis
  display: 直肠脱垂分类与发病机制
  trigger: 排便时直肠脱出
  ref: rectal-prolapse-classification-and-pathogenesis/SKILL.md

- name: rectal-prolapse-surgical-strategy
  display: 直肠脱垂手术策略
  trigger: 成人完全性直肠脱垂非手术无效
  ref: rectal-prolapse-surgical-strategy/SKILL.md

- name: penile-cancer-clinical-classification-and-metastasis-patterns
  display: 阴茎癌临床分型与转移特征
  trigger: 确诊阴茎原发性上皮源性恶性肿瘤
  ref: penile-cancer-clinical-classification-and-metastasis-patterns/SKILL.md

---

## 🩸 血管外科 (7)

- name: deep-vein-thrombosis-clinical-classification
  display: 下肢深静脉血栓临床分型
  trigger: 单侧肢体肿胀/疼痛/浅静脉扩张
  ref: deep-vein-thrombosis-clinical-classification/SKILL.md

- name: virchow-san-yao-su-ping-gu-shen-jing-mai-xue-shuan
  display: Virchow三要素DVT风险评估
  trigger: 静脉壁损伤/制动/高凝状态
  ref: virchow-san-yao-su-ping-gu-shen-jing-mai-xue-shuan/SKILL.md

- name: yuan-fa-xing-xia-zhi-jing-mai-qu-zhang-bing-yin-ji-zhi
  display: 原发性下肢静脉曲张病因机制
  trigger: 下肢浅静脉扩张迂曲无DVT史
  ref: yuan-fa-xing-xia-zhi-jing-mai-qu-zhang-bing-yin-ji-zhi/SKILL.md

- name: xia-zhi-jing-mai-hui-liu-ji-zhi
  display: 下肢静脉回流机制
  trigger: 需理解下肢静脉回流生理
  ref: xia-zhi-jing-mai-hui-liu-ji-zhi/SKILL.md

- name: shen-jing-mai-xue-shuan-zhi-liao-ce-lve
  display: 深静脉血栓治疗策略
  trigger: 确诊DVT无绝对禁忌
  ref: shen-jing-mai-xue-shuan-zhi-liao-ce-lve/SKILL.md

- name: peripheral-vascular-injury-repair
  display: 周围血管损伤修复
  trigger: 确诊主干血管损伤可耐受手术
  ref: peripheral-vascular-injury-repair/SKILL.md

- name: ankle-brachial-index-diagnosis-for-arteriosclerosis-obliterans
  display: ABI诊断动脉硬化性闭塞症
  trigger: 年龄>45岁肢体慢性缺血症状
  ref: ankle-brachial-index-diagnosis-for-arteriosclerosis-obliterans/SKILL.md

---

## 🔥 烧伤与整形 (8)

- name: burn-area-estimation
  display: 烧伤面积估算
  trigger: 需快速评估烧伤严重程度/补液计算
  ref: burn-area-estimation/SKILL.md

- name: burn-wound-depth-classification
  display: 烧伤创面深度分类
  trigger: 烧伤创面伤后72h内动态评估
  ref: burn-wound-depth-classification/SKILL.md

- name: adult-burn-shock-fluid-resuscitation
  display: 成人烧伤休克液体复苏
  trigger: 成人Ⅱ/Ⅲ度烧伤面积≥10%TBSA伤后24h内
  ref: adult-burn-shock-fluid-resuscitation/SKILL.md

- name: burn-induced-acute-kidney-injury-prevention
  display: 烧伤致AKI预防
  trigger: 严重烧伤未进展至终末期肾病
  ref: burn-induced-acute-kidney-injury-prevention/SKILL.md

- name: burn-stress-ulcer-identification-and-management
  display: 烧伤应激性溃疡识别与管理
  trigger: 严重烧伤/休克出现不明原因腹痛/黑便
  ref: burn-stress-ulcer-identification-and-management/SKILL.md

- name: shen-du-shao-shang-chuang-mian-zhi-pi-ce-lue
  display: 深度烧伤创面植皮策略
  trigger: 深Ⅱ度/Ⅲ度烧伤需制定植皮方案
  ref: shen-du-shao-shang-chuang-mian-zhi-pi-ce-lue/SKILL.md

- name: assess-skin-viability-in-hand-trauma
  display: 手部创伤皮肤活力评估
  trigger: 手部创伤评估受损皮肤去留
  ref: assess-skin-viability-in-hand-trauma/SKILL.md

- name: determine-debridement-and-repair-timing-for-hand-trauma
  display: 手部创伤清创与修复时机
  trigger: 急性开放手创伤
  ref: determine-debridement-and-repair-timing-for-hand-trauma/SKILL.md

---

## 🧬 肿瘤外科与综合治疗 (16)

- name: malignant-bone-tumor-limb-salvage-surgery-criteria
  display: 恶性骨肿瘤保肢手术标准
  trigger: 骨肉瘤/尤因肉瘤需决定是否保肢
  ref: malignant-bone-tumor-limb-salvage-surgery-criteria/SKILL.md

- name: radiotherapy-sensitivity-assessment-for-malignant-bone-tumors
  display: 恶性骨肿瘤放疗敏感性评估
  trigger: 考虑将放疗纳入骨肿瘤治疗方案
  ref: radiotherapy-sensitivity-assessment-for-malignant-bone-tumors/SKILL.md

- name: neoadjuvant-chemotherapy-response-evaluation-for-bone-tumors
  display: 骨肿瘤新辅助化疗反应评估
  trigger: 骨肉瘤/尤因肉瘤标准化疗后
  ref: neoadjuvant-chemotherapy-response-evaluation-for-bone-tumors/SKILL.md

- name: tumor-surgical-principles
  display: 肿瘤手术原则
  trigger: 可切除实体恶性肿瘤根治手术
  ref: tumor-surgical-principles/SKILL.md

- name: malignant-tumor-surgical-resection-with-adjuvant-radiotherapy
  display: 恶性肿瘤手术联合辅助放疗
  trigger: 肿瘤弥漫性切除边缘残留
  ref: malignant-tumor-surgical-resection-with-adjuvant-radiotherapy/SKILL.md

- name: limb-salvage-tumor-resection-margins
  display: 保肢手术切除边界
  trigger: 确诊恶性骨肿瘤决定保肢
  ref: limb-salvage-tumor-resection-margins/SKILL.md

- name: cancer-three-tier-prevention-system
  display: 癌症三级预防体系
  trigger: 制定/解释癌症预防策略
  ref: cancer-three-tier-prevention-system/SKILL.md

- name: breast-cancer-pathological-classification
  display: 乳腺癌病理分类
  trigger: 病理报告示乳腺上皮异常增生
  ref: breast-cancer-pathological-classification/SKILL.md

- name: breast-cancer-molecular-subtyping-and-treatment-strategy
  display: 乳腺癌分子分型与治疗策略
  trigger: 确诊浸润性乳腺癌完成四项标志物检测
  ref: breast-cancer-molecular-subtyping-and-treatment-strategy/SKILL.md

- name: breast-cancer-tnm-staging
  display: 乳腺癌TNM分期
  trigger: 完成影像和病理检查明确T/N/M
  ref: breast-cancer-tnm-staging/SKILL.md

- name: lung-cancer-surgical-indications-and-contraindications
  display: 肺癌手术适应证与禁忌证
  trigger: NSCLC I-II期或筛选后III期
  ref: lung-cancer-surgical-indications-and-contraindications/SKILL.md

- name: lung-cancer-tnm-staging-8th-edition
  display: 肺癌TNM第八版分期
  trigger: 肺癌确诊需制定治疗策略
  ref: lung-cancer-tnm-staging-8th-edition/SKILL.md

- name: fei-zhuan-yi-liu-shou-shu-zhi-zheng-yu-yu-hou-ping-gu
  display: 肺转移瘤手术指征与预后
  trigger: 肺转移能否手术决策
  ref: fei-zhuan-yi-liu-shou-shu-zhi-zheng-yu-yu-hou-ping-gu/SKILL.md

- name: ipfi-surgical-indications-and-perioperative-management
  display: 侵袭性肺真菌感染手术与围术期管理
  trigger: IPFI抗真菌治疗无效或病情进展
  ref: ipfi-surgical-indications-and-perioperative-management/SKILL.md

- name: radiotherapy-surgery-comprehensive-treatment
  display: 放疗-手术综合治疗规范
  trigger: 肿瘤局部进展高复发风险
  ref: radiotherapy-surgery-comprehensive-treatment/SKILL.md

- name: radiotherapy-indication-classification
  display: 放疗适应症分类
  trigger: 确诊恶性肿瘤属射线敏感类型
  ref: radiotherapy-indication-classification/SKILL.md

---

## 📋 围手术期管理 (20)

- name: preoperative-pathophysiological-optimization
  display: 术前病理生理状态优化
  trigger: 拟行择期手术存在合并症
  ref: preoperative-pathophysiological-optimization/SKILL.md

- name: perioperative-prophylactic-antibiotics
  display: 围手术期预防性抗生素使用
  trigger: 患者接受外科手术需评估抗感染策略
  ref: perioperative-prophylactic-antibiotics/SKILL.md

- name: antibiotic-regimen-design-principles
  display: 抗菌治疗方案设计原则
  trigger: 需为感染性疾病启动抗菌治疗
  ref: antibiotic-regimen-design-principles/SKILL.md

- name: antibiotic-dosing-in-special-populations
  display: 特殊人群抗生素剂量调整
  trigger: 特殊人群需使用抗菌药物
  ref: antibiotic-dosing-in-special-populations/SKILL.md

- name: perioperative-blood-glucose-management-for-diabetic-patients
  display: 糖尿病患者围术期血糖管理
  trigger: 糖尿病患者需手术
  ref: perioperative-blood-glucose-management-for-diabetic-patients/SKILL.md

- name: surgical-wound-infection-management
  display: 手术切口感染管理
  trigger: 术后切口局部炎症或感染
  ref: surgical-wound-infection-management/SKILL.md

- name: surgical-stress-energy-requirement-calculation
  display: 外科应激能量需求计算
  trigger: 需为外科患者制定营养方案
  ref: surgical-stress-energy-requirement-calculation/SKILL.md

- name: parenteral-nutrition-macronutrient-ratio
  display: 肠外营养宏量营养素配比
  trigger: 无法经胃肠道摄食需启动PN
  ref: parenteral-nutrition-macronutrient-ratio/SKILL.md

- name: nitrogen-balance-calculation-and-clinical-interpretation
  display: 氮平衡计算与临床解读
  trigger: 需评估蛋白质代谢状态
  ref: nitrogen-balance-calculation-and-clinical-interpretation/SKILL.md

- name: laparoscopic-surgery-basic-procedures
  display: 腹腔镜手术基本操作
  trigger: 需行腹盆腔手术符合微创指征
  ref: laparoscopic-surgery-basic-procedures/SKILL.md

- name: high-pressure-steam-sterilization-procedure
  display: 高压蒸汽灭菌操作规范
  trigger: 需确保医疗物品无菌状态
  ref: high-pressure-steam-sterilization-procedure/SKILL.md

- name: autologous-blood-transfusion-selection
  display: 自体输血选择
  trigger: 择期手术/稀有血型/预计大出血
  ref: autologous-blood-transfusion-selection/SKILL.md

- name: xue-jiang-dan-bai-zhi-biao-xuan-ze
  display: 血浆蛋白指标选择
  trigger: 需评估住院病人营养状态
  ref: xue-jiang-dan-bai-zhi-biao-xuan-ze/SKILL.md

- name: shu-xue-bu-liang-fan-ying-chu-li
  display: 输血不良反应处理
  trigger: 输血过程中或后出现溶血反应
  ref: shu-xue-bu-liang-fan-ying-chu-li/SKILL.md

- name: hyperacute-rejection-prevention
  display: 超急性排斥反应识别与预防
  trigger: 器官移植后数分钟至数小时移植物肿胀
  ref: hyperacute-rejection-prevention/SKILL.md

- name: organ-cold-preservation-time-limit
  display: 器官冷保存时限与灌洗液选择
  trigger: 器官切取完成准备运输
  ref: organ-cold-preservation-time-limit/SKILL.md

- name: acute-rejection-diagnosis-rescue
  display: 急性排斥反应诊断与挽救治疗
  trigger: 移植受体不明原因发热/移植区胀痛
  ref: acute-rejection-diagnosis-rescue/SKILL.md

- name: jing-lin-ba-jie-jie-he-ju-bu-zhi-liao
  display: 颈淋巴结结核局部治疗
  trigger: 确诊颈淋巴结结核已启动抗结核治疗
  ref: jing-lin-ba-jie-jie-he-ju-bu-zhi-liao/SKILL.md

- name: postoperative-urinary-retention
  display: 术后尿潴留评估与处理
  trigger: 老年/盆腔会阴手术/蛛网膜下腔麻醉后排尿异常
  ref: postoperative-urinary-retention/SKILL.md

- name: postoperative-intra-abdominal-infection-management
  display: 术后腹腔感染诊断与处理
  trigger: 术后患者发热/腹痛/白细胞增多
  ref: postoperative-intra-abdominal-infection-management/SKILL.md

---

## 💉 麻醉与疼痛 (11)

- name: laryngeal-mask-airway-indications-and-contraindications
  display: 喉罩气道适应证与禁忌证
  trigger: 需快速建立气道张口度≥2cm
  ref: laryngeal-mask-airway-indications-and-contraindications/SKILL.md

- name: endotracheal-intubation-indications
  display: 气管内插管适应症与位置确认
  trigger: 全麻/气道梗阻/心肺复苏
  ref: endotracheal-intubation-indications/SKILL.md

- name: subarachnoid-anesthesia-level-adjustment
  display: 蛛网膜下腔麻醉平面调节
  trigger: 腰麻后需根据手术部位调节阻滞范围
  ref: subarachnoid-anesthesia-level-adjustment/SKILL.md

- name: subarachnoid-anesthesia-local-anesthetic-dosing
  display: 蛛网膜下腔麻醉局麻药剂量
  trigger: 需行2-3h下腹部/盆腔/下肢手术
  ref: subarachnoid-anesthesia-local-anesthetic-dosing/SKILL.md

- name: topical-anesthesia-application
  display: 表面麻醉应用
  trigger: 操作部位为可穿透黏膜或皮肤
  ref: topical-anesthesia-application/SKILL.md

- name: local-infiltration-and-regional-block-anesthesia
  display: 局部浸润与区域阻滞麻醉
  trigger: 手术区域为非实质脏器
  ref: local-infiltration-and-regional-block-anesthesia/SKILL.md

- name: inhaled-anesthetic-selection-and-application
  display: 吸入麻醉药选择与应用
  trigger: 计划使用吸入麻醉具备麻醉机
  ref: inhaled-anesthetic-selection-and-application/SKILL.md

- name: anesthesia-reflux-aspiration-prevention-and-management
  display: 麻醉反流误吸预防与管理
  trigger: 全麻存在饱胃/胃排空障碍
  ref: anesthesia-reflux-aspiration-prevention-and-management/SKILL.md

- name: allis-reduction-for-posterior-hip-dislocation
  display: Allis法复位髋关节后脱位
  trigger: 髋关节后脱位Ⅰ型伤后48h内
  ref: allis-reduction-for-posterior-hip-dislocation/SKILL.md

- name: rib-fracture-pain-management
  display: 肋骨骨折疼痛管理
  trigger: 临床确认肋骨骨折
  ref: rib-fracture-pain-management/SKILL.md

- name: pre-anesthesia-gastrointestinal-preparation
  display: 麻醉前胃肠道准备
  trigger: 全麻/椎管内麻醉择期手术需禁食方案
  ref: pre-anesthesia-gastrointestinal-preparation/SKILL.md

---

## ⚖️ 内分泌与代谢 (6)

- name: secondary-hyperparathyroidism-surgical-indication
  display: 继发性甲旁亢手术指征
  trigger: PTH持续升高内科治疗无效
  ref: secondary-hyperparathyroidism-surgical-indication/SKILL.md

- name: laryngeal-nerve-injury-classification-and-prognosis
  display: 喉返神经损伤分类与预后
  trigger: 甲状腺/头颈外科术后声音嘶哑
  ref: laryngeal-nerve-injury-classification-and-prognosis/SKILL.md

- name: hypercalcemia-calcium-lowering-therapy
  display: 高钙血症降钙治疗
  trigger: 血钙>2.75mmol/L伴神经/心脏症状
  ref: hypercalcemia-calcium-lowering-therapy/SKILL.md

- name: hypotonic-dehydration-classification
  display: 低渗性脱水分类诊断
  trigger: 大量含钠体液丢失伴乏力/头晕
  ref: hypotonic-dehydration-classification/SKILL.md

- name: hypotonic-dehydration-sodium-replacement
  display: 低渗性脱水补钠计算与输液
  trigger: 确诊低渗性脱水血流动力学稳定
  ref: hypotonic-dehydration-sodium-replacement/SKILL.md

- name: hyperosmolar-dehydration-fluid-resuscitation
  display: 高渗性脱水液体复苏
  trigger: 血清Na>150mmol/L血浆渗透压>310mOsm
  ref: hyperosmolar-dehydration-fluid-resuscitation/SKILL.md

---

## 🦠 感染与免疫 (7)

- name: jie-he-gan-ran-shai-cha-jie-du
  display: 结核感染筛查解读
  trigger: TST/IGRA检测后需区分自然感染与卡介苗反应
  ref: jie-he-gan-ran-shai-cha-jie-du/SKILL.md

- name: bone-and-joint-tuberculosis-diagnosis
  display: 骨与关节结核诊断
  trigger: 局部疼痛/寒性脓肿/午后低热
  ref: bone-and-joint-tuberculosis-diagnosis/SKILL.md

- name: bone-joint-tuberculosis-staging
  display: 骨与关节结核病理分期
  trigger: 临床怀疑或确诊骨与关节结核
  ref: bone-joint-tuberculosis-staging/SKILL.md

- name: bone-joint-tuberculosis-drug-treatment
  display: 骨与关节结核药物治疗
  trigger: 确诊或高度疑似骨与关节结核
  ref: bone-joint-tuberculosis-drug-treatment/SKILL.md

- name: facial-danger-triangle-infection-cavernous-sinus-thrombosis-risk-assessment
  display: 面部危险三角感染评估
  trigger: 鼻/上唇感染有挤压史
  ref: facial-danger-triangle-infection-cavernous-sinus-thrombosis-risk-assessment/SKILL.md

- name: sepsis-and-septic-shock-diagnosis
  display: 脓毒症与脓毒症休克诊断
  trigger: 存在感染且qSOFA≥2分
  ref: sepsis-and-septic-shock-diagnosis/SKILL.md

- name: pdp-h-headache-prevention-and-treatment
  display: 腰麻后头痛预防与治疗
  trigger: 腰麻后2-7天体位性头痛
  ref: pdp-h-headache-prevention-and-treatment/SKILL.md

---

## 📡 影像与介入 (9)

- name: x-ray-contrast-imaging-classification-and-application
  display: X线造影分类与应用
  trigger: 需对腔道/血管系统影像学评估
  ref: x-ray-contrast-imaging-classification-and-application/SKILL.md

- name: interventional-radiology-core-techniques-and-clinical-applications
  display: 介入放射学核心技术
  trigger: 疾病适合微创介入影像引导可行
  ref: interventional-radiology-core-techniques-and-clinical-applications/SKILL.md

- name: digestive-endoscopy-techniques-selection-and-application
  display: 消化内镜技术选择与应用
  trigger: 消化道局限性病变需内镜诊疗
  ref: digestive-endoscopy-techniques-selection-and-application/SKILL.md

- name: kai-fang-xing-qi-xiong-jiu-zhi
  display: 开放性气胸救治
  trigger: 吸吮性伤口
  ref: kai-fang-xing-qi-xiong-jiu-zhi/SKILL.md

- name: progressive-hemothorax-diagnosis
  display: 进行性血胸诊断
  trigger: 胸部创伤后血流动力学不稳定
  ref: progressive-hemothorax-diagnosis/SKILL.md

- name: pulmonary-resection-indications-contraindications-for-tb
  display: 肺结核肺切除术指征
  trigger: 肺结核结构性病变抗结核无效
  ref: pulmonary-resection-indications-contraindications-for-tb/SKILL.md

- name: men-jing-mai-gao-ya-ce-zhi-xun-huan-ping-gu
  display: 门静脉高压侧支循环评估
  trigger: 门静脉高压伴上消化道出血
  ref: men-jing-mai-gao-ya-ce-zhi-xun-huan-ping-gu/SKILL.md

- name: portal-hypertension-diagnosis-thresholds
  display: 门静脉高压诊断阈值
  trigger: 需评估肝硬化患者门静脉高压
  ref: portal-hypertension-diagnosis-thresholds/SKILL.md

- name: portal-hypertension-surgery-tips
  display: 门静脉高压手术与TIPS决策
  trigger: 食管胃底静脉曲张出血药物/内镜无效
  ref: portal-hypertension-surgery-tips/SKILL.md

---

## 🏋️ 康复与功能评估 (12)

- name: fracture-rehabilitation-three-phases
  display: 骨折康复三阶段治疗
  trigger: 四肢骨折后特定时间窗
  ref: fracture-rehabilitation-three-phases/SKILL.md

- name: fracture-healing-stages-and-clinical-union-criteria
  display: 骨折愈合分期与临床愈合标准
  trigger: 询问骨折愈合时间进程
  ref: fracture-healing-stages-and-clinical-union-criteria/SKILL.md

- name: shou-bu-xiu-xi-wei-yu-gong-neng-wei-ping-gu
  display: 手部休息位与功能位评估
  trigger: 肌腱损伤筛查/术后固定位置决策
  ref: shou-bu-xiu-xi-wei-yu-gong-neng-wei-ping-gu/SKILL.md

- name: stenosing-tenosynovitis-diagnosis
  display: 狭窄性腱鞘炎诊断与处理
  trigger: 长期重复手部活动伴晨僵/弹响
  ref: stenosing-tenosynovitis-diagnosis/SKILL.md

- name: shi-gao-beng-dai-gu-ding-zhi-zheng-yu-zhu-yi-shi-xiang
  display: 石膏绷带固定指征与注意事项
  trigger: 符合特定临床指征无禁忌证
  ref: shi-gao-beng-dai-gu-ding-zhi-zheng-yu-zhu-yi-shi-xiang/SKILL.md

- name: xia-zhi-shen-jing-zu-cheng-yu-fen-bu
  display: 下肢神经组成与分布
  trigger: 小腿内侧麻木/足下垂/钩状足
  ref: xia-zhi-shen-jing-zu-cheng-yu-fen-bu/SKILL.md

- name: meniscus-tear-treatment-by-vascular-zone
  display: 半月板撕裂血供分区治疗
  trigger: 确诊半月板撕裂明确血供分区
  ref: meniscus-tear-treatment-by-vascular-zone/SKILL.md

- name: zhang-yingze-hou-zhiyong-tibiofibular-fracture-pattern
  display: 张英泽-侯志勇胫腓骨骨折模式
  trigger: 胫骨下1/3螺旋形骨折
  ref: zhang-yingze-hou-zhiyong-tibiofibular-fracture-pattern/SKILL.md

- name: tibiofibular-shaft-fracture-classification-and-treatment
  display: 胫腓骨干骨折分类与治疗
  trigger: 确诊完成X线检查
  ref: tibiofibular-shaft-fracture-classification-and-treatment/SKILL.md

- name: forearm-dual-fracture-reduction-priority
  display: 前臂双骨折复位优先级
  trigger: 非手术治疗手法复位
  ref: forearm-dual-fracture-reduction-priority/SKILL.md

- name: stress-fracture-recognition
  display: 应力性骨折识别
  trigger: 渐进性骨痛活动量增加X线阴性
  ref: stress-fracture-recognition/SKILL.md

- name: flexible-flatfoot-nonsurgical-management
  display: 柔韧性平足非手术管理
  trigger: 负重时足弓塌陷伴足部不适
  ref: flexible-flatfoot-nonsurgical-management/SKILL.md

---

## 🦿 风湿与脊柱疾病 (5)

- name: ankylosing-spondylitis-diagnostic-criteria
  display: 强直性脊柱炎诊断标准
  trigger: 需判断是否符合修订纽约标准
  ref: ankylosing-spondylitis-diagnostic-criteria/SKILL.md

- name: ankylosing-spondylitis-imaging-staging
  display: 强直性脊柱炎影像分期
  trigger: 临床怀疑AS需影像评估
  ref: ankylosing-spondylitis-imaging-staging/SKILL.md

- name: ankylosing-spondylitis-vs-rheumatoid-arthritis-differentiation
  display: 强直性脊柱炎与类风湿关节炎鉴别
  trigger: 慢性脊柱炎症需排除RA
  ref: ankylosing-spondylitis-vs-rheumatoid-arthritis-differentiation/SKILL.md

- name: cervical-myelopathy-surgical-indications
  display: 脊髓型颈椎病手术指征
  trigger: 明显脊髓压迫症状
  ref: cervical-myelopathy-surgical-indications/SKILL.md

- name: lumbar-spinal-stenosis-diagnosis-and-typing
  display: 腰椎管狭窄症诊断与分型
  trigger: 中老年行走后下肢痛麻休息缓解
  ref: lumbar-spinal-stenosis-diagnosis-and-typing/SKILL.md

---

## 🔧 其他专科技能 (10)

- name: qiang-xin-yao-shi-yong-zhi-zheng
  display: 强心药使用指征
  trigger: 充分液体复苏后动脉压仍低
  ref: qiang-xin-yao-shi-yong-zhi-zheng/SKILL.md

- name: yong-qie-kai-yin-liu-caozuo
  display: 痈切开引流操作
  trigger: 痈出现脓点/皮肤紫褐色
  ref: yong-qie-kai-yin-liu-caozuo/SKILL.md

- name: hu-nong-xing-zhi-tou-yan-qie-kai-yin-liu
  display: 脓性指头炎切开引流
  trigger: 剧烈跳痛/肿胀/皮肤红转白
  ref: hu-nong-xing-zhi-tou-yan-qie-kai-yin-liu/SKILL.md

- name: zuzhi-guanzhu-yu-yanghe-zhuangtai-jiance
  display: 组织灌注与氧合状态监测
  trigger: 外科重症/休克状态
  ref: zuzhi-guanzhu-yu-yanghe-zhuangtai-jiance/SKILL.md

- name: cheng-ren-chu-bu-xin-fei-fu-su
  display: 成人初步心肺复苏
  trigger: 成人无反应无呼吸
  ref: cheng-ren-chu-bu-xin-fei-fu-su/SKILL.md

- name: ards-diagnosis-berlin-definition
  display: ARDS柏林定义诊断
  trigger: ICU患者急性呼吸困难/低氧血症
  ref: ards-diagnosis-berlin-definition/SKILL.md

- name: oliguric-phase-fluid-management-in-aki
  display: AKI少尿期液体管理
  trigger: 纠正液体缺失后仍少尿
  ref: oliguric-phase-fluid-management-in-aki/SKILL.md

- name: aki-diagnosis-and-urine-differentiation
  display: AKI诊断与尿液鉴别
  trigger: 少尿/肌酐快速升高
  ref: aki-diagnosis-and-urine-differentiation/SKILL.md

- name: xue-niao-hun-zhuo-niao-jian-bie-zhen-duan
  display: 血尿与混浊尿鉴别诊断
  trigger: 尿液红色/混浊/含气体异常外观
  ref: xue-niao-hun-zhuo-niao-jian-bie-zhen-duan/SKILL.md

- name: tnm-tumor-staging
  display: TNM肿瘤分期系统
  trigger: 需基于影像/病理对实体瘤分期
  ref: tnm-tumor-staging/SKILL.md
