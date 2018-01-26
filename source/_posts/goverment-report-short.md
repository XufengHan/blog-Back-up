---
title: 数据角度看我党精神世界变迁_简单版
date: 2018-01-24 15:51:42
tags: 政府工作报告 文本分析 自然语言处理
toc: TRUE
---
## 准备工作
### 获取数据
政府工作报告[百度网盘地址](https://pan.baidu.com/s/1hs0CpgC) 密码:i667

### 数据说明
自新中国成立以来，国务院并非每年都发布政府工作汇报。从1950年开始，应该每年都有一次政府工作
汇报，但是1953年之前，政府处于初创，百废待兴，更重要的是人民代表大会还没有成立，政府结构和
程序还处于摸索阶段，所以这段时间政府并没有成型的工作汇报文本。另外1961-1963年国家经历的所
谓的三年自然灾害，政府工作会议因此无法正常举行，1965-1977年，国务院仅在1975年由国务院总理
周恩来发布过一次工作汇报，这一阶段一共发生了十年动乱的文革，76年和77年毛周相继去世，政府工
作处于非正常时期，因此也没进行政府工作汇报。
下图是主持过政府工作报告的领导人合影。
![chief](https://raw.githubusercontent.com/XufengHan/Month-Cost/master/pic/cheif.png)
## 引言
政府工作报告是中华人民共和国政府每年向人民代表大会会议和政治协商会议（俗称“两会” ）代表和政
协委员发布的国情汇报。这份报告更像是政府对人大进行工作汇报的一种书面和口头形式。在欧美先进的
政治体系内也有相似的设定，例如美国总统每年会受过会邀请进行一次国情咨文的演讲，只不过我国的政
府工作报告一般由副总理以上职务在两会期间向两会发布。建国以来，依次有 13 位副总理以上的国务院
要员发布过政府工作报告，其中李鹏和温家宝分别主持了 10 次工作汇报，是历史上主持政府工作报告最
多的总理，周恩来主持政府工作近三十年，仅主持过 4 次工作汇报，主要还是周总理工作阶段处于政府工
作不够稳定的时期。每次政府工作报告的文本都是经过千锤百炼的文案精粹，从某些方面反映来政府工作
心理路程的变化，49年的政府工作报告，约 105 万字，每每牵扯到数亿国人的现实生活，这 100 万字讨
论了多少重大国事，恐怕即便是国史研究的专家也不能述说清楚。但我们可以尝试使用数据挖掘解决这个问题，

## 政府工作报告中的话题线
从数据角度来看，49 年来政府工作报告共讨论了 20 条话题线，下图中每一条线代表一个话题，线上的
词为话题线的关键词。左上方的话题线以战争，苏联，帝国主义为关键词，体现了我国政府当时紧张，激
烈的外部环境。右上方的主题线以人民公社，跃进等词为关键词，体现了我国政府初创时期国内的建设中
心。沿着这两条的话题线，我国政府工作的主题终于磕磕盼盼的来到了经济效益，经济体系这些话题集群
，政府的精神内容终于逐渐有了改革开放的特色。再之后通过科技这个关键词连接到了结构合完善这两个
话题集群，这两个集群将各大事件的关系理的越来越清晰，反应我国的政府工作走进了成熟稳定的阶段。
![pic](https://raw.githubusercontent.com/XufengHan/Month-Cost/master/pic/topic_graph_gibbs.png)

## 政府精神面貌时代划分
从数据上看，政府工作是一个连续变化的过程，我们习惯根据共性和差异性将一个连续变化的过程划分为
不同的阶段，同样政府工作这个连贯的过程也可以划分为渐进变化的阶段。从下图可以看到，根据话题和
内容的不同，政府工作报告可以聚类为两大阶段，每个阶段又可以进一步划分为两个不同的小阶段，每一
个阶段段都具有一定的时代特征。
![pic1](https://raw.githubusercontent.com/XufengHan/Month-Cost/master/pic/report%E2%80%94class.png)

## 政府各个时期精神面貌展示
### 第一个阶段
第一个阶段为自 1954 起至 1978 年，这个阶段以斗争为特征，对外和资本主义、美帝国主义斗争，对
内进行阶级斗争以及各种运动，一时之间风雨如晦。这个阶段词云中的一个词可以非常巧妙的形容这个
阶段，那就是“错误”，虽然不能彻底否定这个阶段。一个新成立的政府总会有一定的摸索时期，就如同
一个人，蹒跚学步是每一个人成长都无法忽略的童年，只是这样的童年对于一个国家来说毕竟不算光鲜。
![ciyun1](https://raw.githubusercontent.com/XufengHan/Month-Cost/master/pic/ciyun1.png)

### 第二个阶段
80 年代至 90 年代初期政府终于从童年的泥沼中挣脱出来，开始有计划的推动这个国家向前进步，国
家结构悄然发生变化，政府的工作重点开始转向了经济建设。重要的是改革开放这个词突然跳上历史舞
台，成为国家当时及以后工作的核心。但是政府工作并没有隔断与早期的联系，词汇结构仍然充斥着
早期阶段的身影，改革还处于概念阶段。
![ciyun2](https://raw.githubusercontent.com/XufengHan/Month-Cost/master/pic/ciyun2.png)

### 第三个阶段
二十世纪末期，国家发展走上了高速通道，社会的方方面面都对发展亟不可待，推进和完善成为了政府
工作的主题，改革开放越来越被人们所认可，科技、体制、经济等词汇开始落实结构的内容，同时描述
改革的词汇例如创新、高新技术、精神文明、市场经济等逐渐开始崭露头角。改革已经从原始概念逐渐
落实，国家的发展进入了黄金时期。
![ciyun3](https://raw.githubusercontent.com/XufengHan/Month-Cost/master/pic/ciyun3.png)

### 第四个阶段
最近十年多年是政府工作发展的时期，政府工作报告中不再是改革和结构等发展方向的词独大，改革相
关词汇与改革齐头并进。同时报告中有关民生的词汇开始增多，例如民生、依法、公共、就业，节能
等。政府工作的重点从原来改革一个词的舞台，转变为一个百花齐放的局面，说明改革已经深化到各个
方面，多个方向均有实质性的进展了。
![ciyun4](https://raw.githubusercontent.com/XufengHan/Month-Cost/master/pic/ciyun4.png)

不识庐山真面目，只缘身在此山中，生活总是在悄无声息的变化，大到一个国家政府，小到一个人的心
态。我们有时候会觉得我们自己总是那个德行，从来没有过什么变化，但谁又能说我们的生活真的是在
原地打转，没有改变呢，只是一点一点的积累没有引起自己的注意。一个人尚且如此，何况一个国家，
或许生活在这个庞大的体系内，我们的眼界已经看不到它悄然改变的脚步了。