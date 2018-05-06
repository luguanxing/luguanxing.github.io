# 系统分析与设计博客

## 第一次作业
### 题目
- 1、简单题
    -  软件工程的定义
    -  阅读经典名著“人月神话”等资料，解释 software crisis、COCOMO 模型。
    -  软件生命周期。
    -  按照 SWEBok 的 KA 划分，本课程关注哪些 KA 或 知识领域？
    -  解释 CMMI 的五个级别。例如：Level 1 - Initial：无序，自发生产模式。
    -  用自己语言简述 SWEBok 或 CMMI （约200字）

-  2、解释 PSP 各项指标及技能要求：
    -  阅读《现代软件工程》的 PSP: Personal Software Process 章节。http://www.cnblogs.com/xinz/archive/2011/11/27/2265425.html
    -  按表格 PSP 2.1， 了解一个软件工程师在接到一个任务之后要做什么，需要哪些技能，解释你打算如何统计每项数据？ （期末考核，每人按开发阶段提交这个表）
<br/>

### 解答
- 1.简答题
    -  软件工程是指将系统化的、规范的、可度量的方法应用于软件的开发、运行和维护的过程,即将工程化应用于软件过程。
    -  软件危机是指在软件开发及维护的过程中所遇到的一系列严重问题，这些问题皆可能导致软件产品的寿命缩短甚至夭折。COCOMO是一种在软件项中估算工作量、成本以及时间表的模型，包括参数化的项目估算方法，参数建模是把项目的某些特征作为参数，通过建立一个数字模型预测项目成本。
    -  软件生命周期又称为软件生存周期或系统开发生命周期，是软件的产生直到报废的生命周期，周期内有问题定义、可行性分析、总体描述、系统设计、编码、调试和测试、验收与运行、维护升级到废弃等阶段，这种按时间分程的思想方法是软件工程中的一种思想原则，即按部就班、逐步推进，每个阶段都要有定义、工作、审查、形成文档以供交流或备查，以提高软件的质量。
    -  SWEBok的知识领域有软件需求、软件设计、软件测试、软件建构、软件维护与更新、软件构型管理、软件工程管理、软件开发过程、软件工程工具与方法、软件质量。本课程关注的知识领域有软件需求、软件设计、软件建构、软件测试、软件构型管理、软件开发工程、软件工程工具与方法、软件质量等。 
    -  Level 1 - Initial(初始级)：软件过程是无序的，有时甚至是混乱的，对过程几乎没有定义，成功取决于个人努力。管理是反应式的。<br/>
Level 2 - Managed(已管理)：建立了基本的项目管理过程来跟踪费用、进度和功能特性。制定了必要的过程纪律，能重复早先类似应用项目取得的 成功经验。第二级共7个过程域：需求管理、项目规划、项目跟踪与控制、供应商协议管路、度量与分析、过程与产品质量保证、配置管理。<br/>
Level 3 - Defined(已定义)：已将软件管理和工程两方面的过程文档化、标准化，并综合成该组织的标准软件过程。所有项目均使用经批准、剪裁的标准软件过程来开发和维护软件，软件产品的生产在整个软件过程是可见的。<br/>
Level 4 - Quantitatively Managed(已量化)：分析对软件过程和产品质量的详细度量数据，对软件过程和产品都有定量的理解与控制。管理有一个作出结论的客观依据，管理能够在定量的范围内预测性能。第四级共两个过程域：组织过程性能、量化项目管理。<br/>
Level 5 - Optimizing(优化中)：过程的量化反馈和先进的新思想、新技术促使过程持续不断改进<br/>
    -  SWEBOK是IEEE-CS/ACM联合指导委员会定义的“软件工程知识体”。SWEBOK全面描述了软件工程实践所需的知识，为开发本科软件工程教育计划打下了基础。ACM和IEEE-CS发布的SWEBOK定义了软件工程学科的内涵，它由10个知识域构成，即软件需求、软件设计、软件测试、软件建构、软件维护与更新、软件构型管理、软件工程管理、软件开发过程、软件工程工具与方法、软件质量。SWEBOK描述的是广泛共识的知识，随着软件技术的迅速发展，当前一些学术界的研究成果以及产业开始应用的新技术将逐渐普及，因此SWEBOK V3项目组的最后一个目标是希望能建立SWEBOK每三年周期性更新的制度，持续改进知识体系。期待SWEBOK能成为持续推进软件工程走向成熟的重要力量之一。
<br/>
- 2.阅读题

一个软件工程师在接到一个任务之后要做如下:
```
计划
 - 估计这个任务需要多少时间
开发
 - 分析需求
 - 生成设计文档
 - 设计复审 (和同事审核设计文档)
 - 代码规范 (为目前的开发制定合适的规范)
 - 具体设计
 - 具体编码
 - 代码复审
 - 测试（包括自我测试，修改代码，提交修改）
记录时间花费
测试报告
计算工作量
事后总结
提出过程改进计划
```
我的数据统计方法:<br/>
估计时间=(开发难度) / (技术水平 * 人数)<br/>
记录时间花费=具体到ide上编码的时间<br/>
计算工作量=代码行数(不带复制粘贴)<br/>

<br><br><br><br><br><br><br>

## 第二次作业
### 题目
- 1、简单题
    -  简述瀑布模型、增量模型、螺旋模型（含原型方法）的优缺点。
    -  简述 UP 的三大特点，其中哪些内容体现了用户驱动的开发，哪些内容体现风险驱动的开发？
    -  UP 四个阶段的划分准则是什么？关键的里程碑是什么？
    -  IT 项目管理中，“工期、质量、范围/内容” 三个元素中，在合同固定条件下，为什么说“范围/内容”是项目团队是易于控制的
    -  为什么说，UP 为企业按固定节奏生产、固定周期发布软件产品提供了依据？

-  2、解释 PSP 各项指标及技能要求：
    -  使用截图工具（png格式输出），展现你团队的任务 Kanban，请注意以下要求
        -  每个人的任务是明确的。即一周后可以看到具体成果
        -  每个人的任务是1-2项。
        -  至少包含一个团队活动任务表）
<br/>

### 解答
- 1.简答题
    -  瀑布模型
        -  瀑布模型的优点：有利于大型软件开发过程中人员的组织、管理，有利于软件开发方法和工具的研究，从而提高了大型软件项目开发的质量和效率。
        -  瀑布模型的缺点：（1）开发过程一般不能逆转，否则代价太大；（2）实际的项目开发很难严格按该模型进行；（3）客户往往很难清楚地给出所有的需求，而该模型却要求如此。（4）软件的实际情况必须到项目开发的后期客户才能看到，这要求客户有足够的耐心。 
    -  增量模型
        -  增量模型的优点：（1）采用增量模型的优点是人员分配灵活，刚开始不用投入大量人力资源；（2）如果核心产品很受欢迎，则可增加人力实现下一个增量；（3）可先发布部分功能给客户，对客户起到镇静剂的作用。
        -  增量模型的缺点：（1）并行开发构件有可能遇到不能集成的风险，软件必须具备开放式的体系结构；（2）增量模型的灵活性可以使其适应这种变化的能力大大优于瀑布模型和快速原型模型，但也很容易退化为边做边改模型，从而是软件过程的控制失去整体性。
    -  螺旋模型
        -  螺旋模型的优点：（1）设计上的灵活性,可以在项目的各个阶段进行变更；（2）以小的分段来构建大型系统,使成本计算变得简单容易；（3）客户始终参与每个阶段的开发,保证了项目不偏离正确方向以及项目的可控性；（4） 随着项目推进,客户始终掌握项目的最新信息 , 从而他或她能够和管理层有效地交互。 
        -  螺旋模型的缺点：（1）采用螺旋模型需要具有相当丰富的风险评估经验和专门知识，在风险较大的项目开发中，如果未能够及时标识风险，势必造成重大损失；（2）过多的迭代次数会增加开发成本，延迟提交时间。
    -  UP 的三大特点三大特点：
        -  (1)用例驱动
        -  (2)以架构为中心的
        -  (3)受控的迭代式增量开发
        -  其中，1、3体现用户驱动开发，2体现风险驱动开发
    -  UP 四个阶段的划分准则：
        -  初始：获得项目的基础；生命周期目标
        -  细化：迭化系统构架；生命周期构架
        -  构造：构造软件；初始运作功能
        -  移交：把软件部署到用户环境；产品发布
    -  固合同定的条件下，工期固定了，质量的把关需要客户参与，所以项目团队不易控制，范围／内容更对的取决于项目团队的选择，所以较易控制。
    -  UP规定流程都是时间限制的。而且每过一个迭代周期就有一个新的版本，让开发团队能有比较准确的把握。
- 2.团队项目
    订餐管理系统

<br><br><br><br><br><br><br>

## 第三次作业
### 题目
![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/q-3-1.jpg?raw=true)
![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/q-3-2.jpg?raw=true)

<br/>

### 解答
- 1.用例建模
    -  a.阅读 Asg_RH 文档，绘制用例图<br>
        ![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-3-1.png?raw=true)<br/><br>
    -  b.携程网<br>
        ![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-3-2.png?raw=true)<br/>
        ![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-3-3.png?raw=true)<br/><br>
    -  c.紧跟时代潮流，使用流行的三方软件(百度地图、支付宝、微信)，酒店推荐排序(广告排序)等<br>
    -  d.搜索酒店<br>
        -  选择城市、日期、关键字，点击搜索<br>
        -  根据热门点击排序<br>
        -  根据推荐排序<br>
        -  需要通过计划中决定迭代完成的目标，然后把这个进行整合，形成一个搜索引擎<br>
- 2.业务建模<br>
    -  a.酒店预定流程图<br>
        ![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-3-4.png?raw=true)<br/><br>
    -  b.ATM取款流程<br>
        ![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-3-5.png?raw=true)<br/><br>
    -  c.淘宝退款流程<br>
        ![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-3-6.png?raw=true)<br/><br>
- 3.用例文本编写<br>
    -  优点<br>
        -  简洁、直观、易理解<br>
        -  让需求和设计工作分离开来，条理清晰<br>
    -  缺点<br>
        -  无法描述细节<br>


<br><br><br><br><br><br><br>

## 第四次作业
### 题目
![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/q-4-1.png?raw=true)<br>

<br/>

### 解答
![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-4-1.png?raw=true)<br>
![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-4-2.png?raw=true)<br>

```
/*Table structure for table `customer` */

DROP TABLE IF EXISTS `customer`;

CREATE TABLE `customer` (
  `cid` int(11) NOT NULL,
  `name` varchar(100) DEFAULT NULL,
  `phone` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`cid`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

/*Data for the table `customer` */

/*Table structure for table `hotel` */

DROP TABLE IF EXISTS `hotel`;

CREATE TABLE `hotel` (
  `hid` int(11) NOT NULL,
  `name` varchar(100) DEFAULT NULL,
  `address` varbinary(100) DEFAULT NULL,
  PRIMARY KEY (`hid`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

/*Data for the table `hotel` */

/*Table structure for table `payment` */

DROP TABLE IF EXISTS `payment`;

CREATE TABLE `payment` (
  `pid` int(11) NOT NULL,
  `payment` int(11) DEFAULT NULL,
  `platform` varchar(100) DEFAULT NULL,
  `rid` int(11) DEFAULT NULL,
  PRIMARY KEY (`pid`),
  KEY `FK_payment` (`rid`),
  CONSTRAINT `FK_payment` FOREIGN KEY (`rid`) REFERENCES `reservation` (`rid`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

/*Data for the table `payment` */

/*Table structure for table `reservation` */

DROP TABLE IF EXISTS `reservation`;

CREATE TABLE `reservation` (
  `rid` int(11) NOT NULL,
  `cid` int(11) DEFAULT NULL,
  `oredrdate` varchar(100) DEFAULT NULL,
  `checkindate` varchar(100) DEFAULT NULL,
  `checkoutdate` varchar(100) DEFAULT NULL,
  `city` varchar(100) DEFAULT NULL,
  `hid` int(11) DEFAULT NULL,
  PRIMARY KEY (`rid`),
  KEY `FK_hotel` (`hid`),
  KEY `FK_customer` (`cid`),
  CONSTRAINT `FK_customer` FOREIGN KEY (`cid`) REFERENCES `customer` (`cid`),
  CONSTRAINT `FK_hotel` FOREIGN KEY (`hid`) REFERENCES `hotel` (`hid`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

/*Data for the table `reservation` */

/*Table structure for table `room` */

DROP TABLE IF EXISTS `room`;

CREATE TABLE `room` (
  `rid` int(11) NOT NULL,
  `type` varchar(100) DEFAULT NULL,
  `number` varchar(100) DEFAULT NULL,
  `hid` int(11) DEFAULT NULL,
  PRIMARY KEY (`rid`),
  KEY `FK_room` (`hid`),
  CONSTRAINT `FK_room` FOREIGN KEY (`hid`) REFERENCES `hotel` (`hid`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```

<br/>

<br><br><br><br><br><br><br>

## 第五次作业
### 题目
![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/q-5-1.png?raw=true)<br>

<br/>

### 解答
![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-5-1.png?raw=true)<br>
![img](https://github.com/luguanxing/luguanxing.github.io/blob/master/pictures/a-5-2.png?raw=true)<br>


<br><br><br><br><br><br><br>
