# ABOUT
## <center>Xingchen Lin</center>
### <center>WEB AND SOFTWARE ENGINEER, PHP/JAVA/GOLANG DEVELOPER</center>
### <center> [BUAAFutureCoder@gmail.com](mailto:buaafuturecoder@gmail.com); [+86(0)15101669791](tel:008615101669791); Beijing, China</center>


# EDUCATION
### 2019 - 2021, Master Degree, Beijing University of Aeronautics and Astronautics
* Software Engineering majored in artificial intelligence

### 2012 - 2016, Bachelor Degree, Shenyang University of technology
* Computer Science and Technology
* Language courses:English & Japanese
* 




## 技能清单
* 语言：PHP / JAVA / Golang / Python / 前端系列
* 框架：CodeIgniter(PHP) / SSM(JAVA) / Gin&Beego(GO)
* 前端 & 跨平台：Vue / Bootstrap / HTML5 / jQuery / 闭包风格 / Chrome拓展 / PhoneGap
* Cache：Redis / Memcache
* 数据库相关：MySQL / MongoDB / OpenTSDB / ElasticSearch
* 流式计算 & 异步队列：Kafka / ZooKeeper / 多线程、协程计算 / RabbitMQ
* 版本管理：Git / SVN
* 虚拟化：Docker / VM
* 持续集成：Jenkins
* 机器学习基础原理
* 以Linux & MacOS作为日常操作系统 
* 坚持每日全方位全栈练习提高 / 每周一本书
* 擅长独立或合作快速完成整个项目，并保持高提前上线率、低BUG率、低事故率


## 工作经历
### 阿里巴巴集团 - 饿了么 新零售研发中心 - 实习→资深研发工程师（2015年11月至今）
#### 新零售紧急项目救火队员(2018.07至今)
* 作为救火队员奔走于新零售各个项目组之间，支援紧急项目开发，独自或带领团队设计架构、开发多个1.0项目，试水并推动项目技术栈由PHP转至JAVA。主要负责并交接：结算1.0、订单履约1.0、拣货助手1.0、多活服务改造、各方向JAVA技术栈改革。

#### 基础服务支付(2017.09 - 2018.07)
* 负责支付收银台、免密支付、对账平台、支付稳定性监控、第三方对接开发，极其慎重对待每一行代码和每一分真金白银，没有出现任何事故。

#### 仓储生态链及扩品类通用频道(2016.07 - 2017.09)
* 负责仓储生态链系统开发，是迄今为止业务逻辑最为复杂的系统。后期负责鲜花蛋糕、早餐、下午茶、生鲜通用频道开发。

#### 质享生活及商超频道(2015.11 - 2016.07)
* 负责质享生活及商超频道的迭代、优化及管理后台开发等工作。实现全国配送、节日特色活动、商品分享图片生成、商超数据导出等功能。

#### 三篇专利（审中）
[导航线路生成方法、装置、设备和电动车](http://www.soopat.com/Patent/201710596785)   
[原料信息的提供方法、装置和电子设备](http://www.soopat.com/Patent/201710560336)  
[服务分配方法、装置、电子设备及计算机可读存储介质](http://www.soopat.com/Patent/201810164044)

### 百度 - 云安全部 - 实习研发工程师（2015年4月至2015年11月）
#### [csiem云分析项目](http://xi.baidu.com/)
* 在此项目负责作为项目中间件的PHP API以及其对应的后台管理系统的开发并书写全部接口的英文文档。开发四十余个接口及对应的单元测试、封装ElasticSearch检索方法、一个后台管理系统整站及两千余行格式化英文文档。 

### [沈阳工业大学 - 实践类课程 - 外聘教师](https://github.com/SUTFutureCoder/resume/blob/master/TeacherOfSUT.jpeg)（2018年11月至今）
* [在校时期](https://github.com/SUTFutureCoder/resume/blob/master/README_SCHOOL_VER.md)工程、竞赛实践突出，毕业后义务面向计算机专业开展两次毕业就业指导会、多次线上义务集训指导，平均每年指导三位学生（专业不限）获得百度面试机会、多位入职一线互联网公司、多位在国家级竞赛获奖。曾两个月时间义务指导非计算机专业学生从沈阳华晨宝马到北京滴滴出行总部的就职飞跃。因此受邀担任沈阳工业大学信息科学与工程学院实践类课程外聘教师。


## 技术类项目
#### 流式计算框架项目
**S** 公司缺少一个直观展示接口QPS及服务稳定性平台，服务长时间抖动且报警滞后导致用户流失，现有日志监控难以自定义字段监控。 

**T** 构建一个高性能、高可靠性流式日志处理框架。允许监控字段配置化接入或DIY二次开发以适应多种业务需求。指标异常时能够及时报警。  

**A** 使用Golang语言，高性能、协程处理日志流数据，优化程序性能，降低内存及CPU消耗。使用Kafka等分布式中间件，与现有日志流采集中间件对接。使用OpenTSDB，落地时序处理后数据。与钉钉和短信平台对接能够在第一时间将指标异常报出。使用Grafana将数据图形化，直观展示各指标数据以方便人工监控。通用化、配置化设计快速接入全方向服务核心指标避免重复开发。离线流式计算能够在低成本恶劣环境运行并且不受封线限制。  

**R** 独立完成流式计算框架开发，并提供简易配置接入方式。通过图表QPS发现接口异常4次，联合基础架构部对恶意爬虫进行封禁，清洗75%爬虫造成的接口流量。为公司全业务方向提供毫秒级实时稳定的日志流式统计，直观展示服务稳定性及流量，避免服务长时间抖动造成用户流失。经过四版升级迭代，代码风格、文档完整性和处理效率均有较大提升，任何同事都可以轻松进行二次开发以满足DIY需求。  

#### 前后端及中间件通用监控平台
**S** 公司缺少一个前端、后端、慢查询全方位监控平台。经常因数据库慢查询、接口超时、服务不可用、前端配置错误导致用户流失、公司品牌声誉受损问题。 

**T** 对公司前后端及中间件进行实时监控，能够将日志流处理结果输出至目标存储介质以进行自定义展示。能够对线上问题更早地预警，有效防范事故集中爆发。  

**A** 使用上述流式计算框架项目提供的日志流处理能力。流式计算框架实时分类分析已接入各服务、中间件、前端空白gif打点、数据库中间件等日志流。根据各个业务差异性输出、持久化至目标存储介质。使用Grafana进行通用指标展示，各个接入方也可以选择自行开发展示工具进行特殊性指标展示。  

**R** 使用流式计算框架对数据流进行高性能处理、各中间件日志配置化快速接入。开发监控平台前端展示工具，方便查看、定位、解决前后端性能问题及慢查询。消除因超时、服务不可用、前端配置错误导致用户流失、公司品牌声誉受损问题。

#### 极速对账项目
**S** 支付产品需要对各个渠道支付进行监控、对账以保障公司资金安全，原有对账算法缓慢、逻辑不清、内存溢出、无法支持高订单量下的快速对账、并且当对账错误或第三方账单提供延迟时无法进行回滚。 
 
**T** 学习业界现有对账系统架构、对账产品流程、核心对账算法。结合Redis和集合论，构建极速对账核心技术，极大提升对账性能。实现极速对账算法，降低内存使用，对账分步清晰执行，允许数据回滚以重新执行对账。
  
**A** 划分五步：1.获取通道对账单，2.转储通道账单，3.转储本方账单，4.执行极速对账，5.输出结果邮件。其中转储过程中对字段进行分析，并构造hash关键字段存放至Redis，执行对账时直接SDIFF即可完成极速对账，极大降低对账内存使用和执行时间。因SDIFF不会对原始数据进行操作，能够轻松进行数据库数据回滚、重新对账操作。 
 
**R** 提升12倍对账效率，消除所有OOM问题，及时发现刷单漏洞，提前发现不平账避免客诉，逻辑友好易于维护，守护公司和用户资金安全。  


## 曾获荣誉 / 晋升
* 2019.01 [2018年度“一马当先”奖](https://github.com/SUTFutureCoder/resume/blob/master/TakeTheLead.jpeg)
* 2018.04 晋升资深研发工程师 (最快速度晋升)
* 2017.12 [饿了么第二届Hackathon亚军](https://github.com/SUTFutureCoder/resume/blob/master/hackathon2nd.jpeg)
* 2017.08 [创新先锋奖](https://github.com/SUTFutureCoder/resume/blob/master/innovation_pioneer.jpeg)
* 2017.04 晋升高级研发工程师
* 2017.03 [高效开发奖](https://github.com/SUTFutureCoder/resume/blob/master/efficient_development.jpeg)
* 2016.12 百度外卖第一届Hackathon参与奖
* 2016.07 毕业之前至高中时期 独立参加国家、省、市实践竞赛和学习共42项荣誉请见 [校招简历](https://github.com/SUTFutureCoder/resume/blob/master/README_SCHOOL_VER.md)

# Amateur Exploration
[Github](https://github.com/SUTFutureCoder)
