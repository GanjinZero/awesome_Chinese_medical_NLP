# awesome_Chinese_medical_NLP
中文医学NLP公开资源整理：术语集/语料库/词向量/预训练模型/知识图谱/命名实体识别/QA/信息抽取/etc

# Benchmark

- [中文医疗信息处理挑战榜CBLUE数据集](<https://tianchi.aliyun.com/specials/promotion/2021chinesemedicalnlpleaderboardchallenge>) [Baseline](<https://github.com/CBLUEbenchmark/CBLUE>) 中文医疗信息处理挑战榜CBLUE(Chinese Biomedical Language Understanding Evaluation)是中国中文信息学会医疗健康与生物信息处理专业委员会在合法开放共享的理念下发起，由阿里云天池平台承办，并由医渡云（北京）技术有限公司、平安医疗科技、北京大学、郑州大学、鹏城实验室、哈尔滨工业大学(深圳）、同济大学、夸克、阿里巴巴达摩院等开展智慧医疗研究的单位共同协办，旨在推动中文医学NLP技术和社区的发展。

# 术语集/语料库

- [medical-news](<https://github.com/flyyang/medical-news>) 中文医学新闻爬虫
- [medical-books](<https://github.com/scienceasdf/medical-books>) 中文LaTex开源医学书籍
- [THUOCL](<https://github.com/thunlp/THUOCL>) 清华大学thunlp组医学词汇
- [ICD9](<https://athena.ohdsi.org/search-terms/terms?vocabulary=ICD9ProcCN&page=1&pageSize=15&query=>)  ICD-9中文对应
- [ICD10](<https://github.com/chaseliu/ICD-10-CN>) ICD-10中文对应
- [ICD11](<https://icd.who.int/browse11/l-m/zh>) ICD-11中文对应
- [OMAHA七巧板医学术语集样例数据](<http://openkg.cn/dataset/omaha-data>) 
- [中文糖尿病标注数据集](<https://tianchi.aliyun.com/dataset/dataDetail?dataId=22288>) 包含实体标注和关系标注


# 词向量/预训练模型

- [ChineseEHRBert](<https://github.com/GanjinZero/ChineseEHRBert>) 中文电子病历预训练Bert；用Bert测试命名实体识别，问答模型，关系提取任务
- [MC-BERT](<https://github.com/alibaba-research/ChineseBLUE>)ChineseBLUE数据集和模型
- [bertcner](<https://github.com/lxy444/bertcner>) 用于命名实体识别的预训练的中文医学Bert模型
- [PCL-MedBERT](<https://code.ihub.org.cn/projects/1775/repository/mindspore_pretrain_bert>) 鹏城医疗BERT预训练模型
- [medbert](<https://github.com/trueto/medbert>) BERT模型在中文临床自然语言处理中的应用探索与研究
- [Chinese-Word2vec-Medicine](<https://github.com/WENGSYX/Chinese-Word2vec-Medicine>) 中文生物医学领域词向量
# 分词

- [PKUSEG](<https://github.com/lancopku/pkuseg-python>) PKUSEG分词工具，模型支持选择医学
- [cmekg医学分词工具](<https://zstp.pcl.ac.cn:8002/download/mws>) cmekg医学分词


# 知识图谱 / 关系提取

- [cMeKG](<http://zstp.pcl.ac.cn:8002/>) Chinese Medical Knowledge Graph
- [瑞金医院人工智能辅助构建知识图谱大赛](<https://tianchi.aliyun.com/competition/entrance/231687/introduction>) 糖尿病相关的学术论文以及糖尿病临床指南的实体标注和抽取实体关系任务
- [OMAHA知识图谱（药品适应症）](<http://openkg.cn/dataset/omaha-kg>) 开放医疗与健康联盟（Open Medical and Healthcare Alliance，OMAHA）构建的药品与药品适应证的知识图谱数据
- [医疗知识图谱数据](<http://openkg.cn/dataset/medical>) 医疗知识图谱数据（ownthink）
- [病人事件图谱数据集](<http://openkg.cn/dataset/peg>) 病人事件图谱是一种新的基于RDF的医疗观察性数据表示模型，可以清晰地表示临床检查、诊断、治疗等多种事件类型以及事件的时序关系。使用三家上海三甲医院的电子病历数据，构建了包括3个专科、173395个医疗事件、501335个事件时序关系以及与5313个知识库概念链接的医疗数据集。
- [中文症状库](<http://openkg.cn/dataset/symptom-in-chinese>) 这是一个包含症状实体和症状相关三元组的数据集。中文症状库的数据来自8个主流的健康咨询网站、3个中文百科网站和电子病历。它还包含了中文症状与UMLS中概念的链接结果。
- [中医医案知识图谱](<http://openkg.cn/dataset/tcm-cases>) 从医案中抽取临床知识构建知识图谱，帮助用户了解中医特色疗法，以及疾病（如“慢性胃炎”）的临床表现、相关疗法、相关养生保健方法等
- [herbnet](<http://openkg.cn/dataset/herb-net>) 面向中药研究，根据中药领域模型的特点，构建了一个包括中医疾病，方剂，中药， 中药化学成分，药理作用，中药实验，化学实验方法在内的中药本体。 进而，基于本体实现了一系列数据库的集成，从而构建了一个中药知识图谱。
- [CHIP2020](<http://cips-chip.org.cn/2020/eval2>) 中文医学文本实体关系抽取
- [CCKS2020](<http://sigkg.cn/ccks2020/?page_id=516>) 新冠知识图谱构建与问答
- [cmekg医学关系提取工具](<https://zstp.pcl.ac.cn:8002/download/mre>) cmekg医学关系提取


# 命名实体识别

- [CCKS2017](<https://www.biendata.com/competition/CCKS2017_2/>) 面向中文电子病历的医疗实体识别及属性抽取数据集
- [CCKS2018](<https://www.biendata.com/competition/CCKS2018_1/>) 面向中文电子病历的医疗实体识别及属性抽取数据集
- [CCKS2019](<https://www.biendata.com/competition/CCKS2019_1/>) [数据下载](<http://openkg.cn/dataset/yidu-s4k>) 面向中文电子病历的医疗实体识别及属性抽取数据集
- [CHIP2020](<http://cips-chip.org.cn/2020/eval1>) 中文医学文本命名实体识别
- [CHIP2020](<http://cips-chip.org.cn/2020/eval6>) 中药说明书实体识别
- [CCKS2020](<http://sigkg.cn/ccks2020/?page_id=516>) 面向中文电子病历的医疗实体及事件抽取
- [cmekg医学ner工具](<https://zstp.pcl.ac.cn:8002/download/ner>) cmekg医学ner
- [CCKS2021](<http://sigkg.cn/ccks2021/?page_id=27>) 面向中文电子病历的医疗实体及事件抽取

# QA

- [CCIR2019](<https://www.biendata.com/competition/ccir2019/>) CCIR 2019 基于电子病历的数据查询类问答
- [cMedQA](<https://github.com/zhangsheng93/cMedQA>) 中文医学QA数据集
- [cMedQA2](<https://github.com/zhangsheng93/cMedQA2>) 中文医学QA数据集
- [CMID](<https://github.com/liutongyang/CMID>) 中文医学QA意图理解数据集
- [KGQA](<https://github.com/YeYzheng/KGQA-Based-On-medicine>) 基于医药知识图谱的智能问答系统 
- [chatbot-base-on-Knowledge-Graph](<https://github.com/baiyang2464/chatbot-base-on-Knowledge-Graph>) 使用深度学习方法解析问题 知识图谱存储 查询知识点 基于医疗垂直领域的对话系统
- [中文医疗对话数据集](<https://github.com/Toyhom/Chinese-medical-dialogue-data>) Chinese medical dialogue data 中文医疗对话数据集 
- [webMedQA](<https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0761-8>) webMedQA
- [MedDialog](<https://github.com/UCSD-AI4H/Medical-Dialogue-System>) The MedDialog dataset contains conversations (in Chinese) between doctors and patients. It has 1.1 million dialogues and 4 million utterances.
- [CHIP2020](<http://cips-chip.org.cn/2020/eval5>) 中医文献问题生成
- [NLPEC](<http://112.74.48.115:8157/>) A Medical Multi-Choice Question Dataset for the National Licensed Pharmacist Examination in China
- [CCKS2021](<http://sigkg.cn/ccks2021/?page_id=27>) 蕴含实体的中文医疗对话生成


# 术语标准化
- [CHIP2019](<http://openkg.cn/dataset/99e3fa10-c5f3-4af8-b147-fe689e67e260>) 临床术语标准化任务:医渡云标准化7K数据集
- [CHIP2020](<http://cips-chip.org.cn/2020/eval3>) 临床术语标准化任务


# 相似句对判断
- [“公益AI之星”挑战赛-新冠疫情相似句对判定大赛](<https://tianchi.aliyun.com/competition/entrance/231776/introduction>) 比赛整理近万条真实语境下疫情相关的肺炎、支原体肺炎、支气管炎、上呼吸道感染、肺结核、哮喘、胸膜炎、肺气肿、感冒、咳血等患者提问句对，要求选手通过自然语言处理技术识别相似的患者问题。


# 文本分类
- [CHIP2019](<https://github.com/zonghui0228/chip2019task3>)临床试验筛选标准短文本分类


# 其他

- [CHIP2018](<https://www.biendata.com/competition/chip2018/>) 针对中文的真实患者健康咨询语料，进行问句意图匹配
- [CHIP2019](<https://www.biendata.com/competition/chip2019/>) 平安医疗科技疾病问答迁移学习比赛
- [CCLUE](<https://github.com/trueto/CCLUE>) 中文临床自然语言处理算法评估基准
- [CCKS2021](<http://sigkg.cn/ccks2021/?page_id=27>) 面向中文医疗科普知识的内容理解

