# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0386springboot船舶维保管理系统--论文pf

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T1bpekEK7?p=58)


# 第一章  课题背景及研究内容

## 1.1 课题背景
信息数据从传统到当代，是一直在变革当中，突如其来的互联网让传统的信息管理看到了革命性的曙光，因为传统信息管理从时效性，还是安全性，还是可操作性等各个方面来讲，遇到了互联网时代才发现能补上自古以来的短板，有效的提升管理的效率和业务水平。传统的管理模式，时间越久管理的内容越多，也需要更多的人来对数据进行整理，并且数据的汇总查询方面效率也是极其的低下，并且数据安全方面永远不会保证安全性能。结合数据内容管理的种种缺点，在互联网时代都可以得到有效的补充。结合先进的互联网技术，开发符合需求的软件，让数据内容管理不管是从录入的及时性，查看的及时性还是汇总分析的及时性，都能让正确率达到最高，管理更加的科学和便捷。本次开发的船舶维保管理系统实现了船舶管理、维修成本管理、船家管理、字典管理、公告管理、故障上报管理、维保公司管理、维保计划管理、维保人员管理、管理员管理等功能。系统用到了关系型数据库中王者MySql作为系统的数据库，有效的对数据进行安全的存储，有效的备份，对数据可靠性方面得到了保证。并且程序也具备程序需求的所有功能，使得操作性还是安全性都大大提高，让船舶维保管理系统更能从理念走到现实，确确实实的让人们提升信息处理效率。
## 1.2 开发目的和意义
小康时代的到来，使得人们满意度上升，生活各个方面都产生了许多变化，比如办公都有相应软件，很多工作都要求员工会操作计算机，可以说现在的时代基本被软件覆盖得差不多了，软件行业的特征就是大家都在使用软件代替传统手工记载操作，软件的出现让我们的生活还有工作又向前翻了新篇章。船舶维保管理系统是一个利用软件形式管理船舶信息的平台。管理员管理租车信息也不再需要用纸张进行信息记录及查询管理操作，所有的操作都是利用电脑进行办公，用户需要使用密码还有用户名进行系统登录操作，按照系统主页界面的各个功能展示进行相关操作，无论添加或者是删除，拟或是修改查询等操作，时间上不需要太多，短短几分钟就会搞定。况且软件是不限制办公地点以及办公时间的，只要有操作需要，随时随地登录系统就可以完成任务。办公效率提高这个不再是难题。公告租赁店对于租车信息的管理操作早就应该进行变革了，利用软件管理租车信息，节约人力物力成本，这是一个新的租车信息管理的创举。
## 1.3 论文研究内容
本次开发的船舶维保管理系统的论文从下面几个部分进行编写：

第一章：本章介绍了程序开发背景和目的意义，罗列出了论文写作内容信息，让我们知道论文编写是如何进展的。

第二章：本章主要讲解了系统开发用到的相关技术方面的知识，比如SSM技术，MySQL数据库知识等内容。帮助人们更好的理解系统技术上面的相关知识。

第三章：文章第3章主要介绍了系统开发的可行性问题，从经济，时间，操作等内容上面进行了大致介绍，确定系统开发确实可行，然后分析了系统的开发流程，确定系统需要具备的大概的功能，保障系统能够稳定使用和运行。

第四章：这个章节主要绘制出了系统功能架构，让我们更直观了解船舶维保管理系统的功能，对后台数据库表进行了设计，还画出了对应的Ｅ－Ｒ图。

第五章：这个章节主要介绍系统各个部分功能具体实现的界面效果。让我们了解到各个部分的功能详细情况。

第六章：这个部分主要就是对船舶维保管理系统进行整体测试，看看程序是否能够达到用户使用要求，程序能否进行验收上交操作。





# 第二章 相关技术

本次开发船舶维保管理系统使用的是Vue进行程序开发，船舶维保管理系统的数据信息选择MySQL数据库进行存放。

## 2.1 VUE介绍
`	`Vue (读音 /vjuː/，类似于 view) 是一套用于构建用户界面的渐进式框架。与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。另一方面，当与[现代化的工具链](https://v2.cn.vuejs.org/v2/guide/single-file-components.html)以及各种[支持类库](https://github.com/vuejs/awesome-vue#libraries--plugins)结合使用时，Vue 也完全能够为复杂的单页应用提供驱动。
## 2.2 MySQL数据库
开发的程序面向用户的只是程序的功能界面，让用户操作程序界面的各个功能，那么很多人就会问，用户使用程序功能生成的数据信息放在哪里的？这个就需要涉及到数据库的知识了，一般来说，程序开发通常就会对常用数据存储工具的特点进行分析比对，比如Mysql数据库的特点与优势，Access数据库的特点与优势，Sqlserver数据库的特点与优势等，最终看哪个数据库与需要开发的程序比较匹配，也符合程序功能运行需要的数据存储要求，比如，需要开发商业级别的程序，存储的数据对数据库要求较高，可以选用Oracle，如果只是比较简单的程序，对数据存储没有过多要求，可以选用微软旗下的Access，当开发程序要求数据库占用空间小，并能满足程序数据存储要求时，就可以考虑Oracle公司从瑞典MySQL AB公司在很早之前就收购过一个关系型数据库，它是现在的Mysql数据库。所以船舶维保管理系统后台数据库使用的是MySQL进行数据库方面的开发工作的，MySQL它是微软开发的一款平台软件，这个软件可以给用户提供高效率的智能数据，并且数据信息还是很可靠，使用它进行数据存储可以满足大众企业管理各种各样的数据信息的需求。MySQL在MySQL版本里面它是最全面的，也是最强大的开发平台， MySQL在许多关键之处都进行了改进的操作，它也增加了很多新特性，这些改进和更新让公司能够对关键应用程序进行高效运行，并且还可以让公司降低发送信息给用户的成本，以及降低数据信息管理的基础设施。因此MySQL在公司以及企业中它的地位是非常高的，ERP还有OA系统，以及公司财务的系统都离不开MySQL，在软件开发非常流行的今天，MySQL也被用来作为网站开发的网站后台数据库，可以说公司使用MySQL进行数据管理不仅节约成本，还可以让公司数据信息的管理效率大大提高，公司数据存放在MySQL平台上，数据信息的安全性也不用担心，因为MySQL他可以给数据库里面的日志还有数据文件以及整个数据库进行加密操作，另外MySQL还提供在线备份功能，这样可以节约存储空间，加快数据备份的速度。总之，选择MySQL进行在线系统的后台数据库开发是很有优势的。这是个不错的软件选择。


##
# 第三章 系统分析

## 3.1可行性分析
可行性分析从时间，经济以及操作和技术上面进行调查和研究，确保合理利用信息资源，避免在进行程序设计过程中因为考虑不周到所带来的困扰，帮助我们更好的进行程序设计。
### 3.1.1时间可行性
本次进行系统开发，我预留了两个月时间来完成，从系统的需求分析，功能结构设计，功能详细设计以及系统测试等环节，两个月时间是可以完成程序开发操作的，我打算每天早中晚都进行程序的编写操作，这期间也包括查阅各种资料信息，加上同学以及老师的帮助和指点，相信程序开发的时间也会缩短不少。所以时间上是可行的。
### 3.1.2 经济可行性
船舶维保管理系统的开发平台是IDEA，数据库选用MySQL数据库，使用的浏览器都是大众浏览器，这些软件是不需要收费就能进行下载安装操作的。在系统开发的硬件选择上面，我使用的是自己的笔记本进行开发操作。因此在进行系统开发时，经济上面无需额外支出。开发出来的程序可以提高办公效率，带来的经济效益比较高，系统开发的投入产出比很可观。
### 3.1.3 操作可行性
船舶维保管理系统的界面设计比较简单，界面布局根据用户日常使用习惯进行设计，网站各个功能在导航栏里面清晰可见，网站的数据操作可视化，用户操作网站不需要培训就能上手，只需要跟着网站功能提示进行操作就行。
### 3.1.4 技术可行性
作为计算机专业学生，在学校期间就学习到许多关于编程方面的知识，像SSM技术，还有MySQL数据库等知识，我对IDEA开发平台以及MySQL数据库的操作也比较熟练，所以技术上面还是有一定把握。
### 3.1.5 法律可行性
自己本人开发的软件和用到的资料来源都是图书馆以及百度文库和百度网页等渠道，并不涉及违法。在个人毕业设计上面，无论源代码还是论文编写内容不存在抄袭行为。

从上面的经济，操作以及时间上面进行的分析，得出结论就是这次开发的船舶维保管理系统在开发上面是能够进行的，系统开发出来能创造更大的经济效益，越早开发升值空间越大。
## 3.2系统流程分析
船舶维保管理系统的开发也是有对应的流程，开发之前必须要进行用户功能需求的分析，最后根据功能需求进行网站设计还有数据库相关数据的设计工作，此次开发的船舶维保管理系统开发流程如图3.1所示。

![](/md/blog.004.png)

图3.1 程序操作流程图

系统开发完成之后会给用户提供登录入口，在这个界面用户输入的信息会得到验证，通过验证之后才能进去船舶维保管理系统的访问主界面，系统登录执行流程如下：

![](/md/blog.005.png)

图3.2 系统执行流程图
## 3.3系统功能需求分析
系统的开发离不开前期的需求分析，这个阶段就是让程序员知道自己该做什么事情，在进行需求分析的时候，着重点就是用户对系统的功能要求，这个阶段要是分析得很到位，系统开发出来投入使用时，用户就会发现系统的功能跟用户需求保持一致，程序稳定性也是达标的，可以说需求分析是决定系统开发成败的关键，它主要就是把现实世界进行抽象化，然后把抽象化的对象用来构建模型。

船舶维保管理系统的受益群体主要是工作人员，该网站能够方便使用者进行数据信息的查找和管理工作，本次开发的网站我们设计的界面展示主要分为管理员界面以及用户界面，具体界面的功能分布如下。

船舶维保管理系统管理员可以管理用户的基本信息，可以管理公告信息，可以管理公告信息等。
## 3.4 系统非功能需求分析
（1）完整性需求

本次开发的船舶维保管理系统里面记录的数据信息不能保持为空，并且数据信息一定要核对正确才行，系统里面数据之间存在的联系不能出错，不能够张冠李戴，数据表里面同一数据在不同数据表里面的显示内容要一样。

（2）性能需求

用户在操作船舶维保管理系统的各个部分内容时，弹出的页面响应时间不能太长，最好控制在三秒钟以内，最大限制值就是四秒，这个是给用户一个好的程序体验。并且系统还要能够承载多人同时在线进行船舶维保管理系统的访问操作。

（3）界面需求

船舶维保管理系统界面设计上面应该考虑到用户日常操作习惯，比如导航栏的设计不能在右边，这个完全违背了用户使用网站的操作习惯，同时功能导航的字体以及颜色应该比较显眼，方便用户容易找寻，避免用户在进行功能操作上面浪费太多时间。

（4）安全性需求

船舶维保管理系统的安全性要有保证，给用户一种可靠，可以信赖的感觉，系统在运行过程中，不能总是出错，与用户进行功能界面交互时，要及时给出反馈信息，另外系统要设置登录窗口，让不是系统的用户不可以进行系统功能界面的访问操作。系统用户也要经过用户名密码的填写操作，才可以进入系统主界面，这样就可以保障系统数据信息处于一种安全状态。



# 第四章 系统设计

## 4.1 总体功能
船舶维保管理系统是根据需求定制开发，开发软件选用IDEA平台配合MySQL数据库进行开发环境的搭建操作，网站采用WEB应用程序中最流行的小程序结构进行开发，用户访问系统数据仅仅需要在客户端安装谷歌浏览器或者是当下常用浏览器就可以访问网站内容。
## ` `4.2 系统模块设计
船舶维保管理系统系统在进行系统中功能模块的划分时，采用层次图来进行表示。层次图具有树形结构，它能使用矩形框来描绘数据信息。顶层代表的数据结构很完整，顶层下面的矩形框表示的数据就是子集数据，当然处于最下面的矩形框就是不能再进行细分的数据元素了，使用层次方框图描述系统功能能让用户一目了然，能够明白系统的功能，以及对应功能板块下面的子功能都可以清楚领会。船舶维保管理系统分为管理员和用户两部分操作角色，下面将对他们的功能进行阐述。

管理员可以管理用户的基本信息，可以管理等功能。管理员功能结构图如下：

]![结构设计图](/md/blog.006.jpeg "结构设计图")

图4.1 管理员功能结构图

## 4.3 数据库设计
### 4.3.1 数据库设计
数据库设计它是建立在数据库还有它对应的应用系统的一门技术，只要是信息系统开发还有系统建设，都会用到数据库设计，但是这个数据库设计并不是很简单就可以完成的，设计期间会遇到很多麻烦事，在设计期间需要考虑再考虑，逐步完善。主要内容也就是把数据库里面的对象还有对象之间的联系进行系统规划操作，还有把他们结构化的过程。
### 4.3.2 数据库E-R 图
E-R 图分成三部分内容，分别是实体，实体的属性以及实体之间的关系这三个部分的内容，通常长方形表示的就是实体，椭圆形表示的就是属性，菱形表示的就是关系了。在E-R 图里面，实体就是对象，比如学生，人，音乐等都能代表实体，实体都具备自己的成员，比如张三就是学生实体里面的成员。一个学生会具有自己的姓名，年龄，出生日期等信息，这些信息就是学生这个实体的属性，因此E-R 图属性代表的就是数据对象具备的属性，E-R 图的关系就是实体跟实体之间的关系了，比如学生跟课程会存在一定的关系，这种关系使用菱形进行表示。

（1）下图是公告实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\公告.jpg](/md/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\公告.jpg")

公告实体属性图

（2）下图是维修成本实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\维修成本.jpg](/md/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\维修成本.jpg")

维修成本实体属性图

（3）下图是维保计划实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\维保计划.jpg](/md/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\维保计划.jpg")

维保计划实体属性图

（4）下图是故障上报实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\故障上报.jpg](/md/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\故障上报.jpg")

故障上报实体属性图

（5）下图是维保人员实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\维保人员.jpg](/md/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\维保人员.jpg")

维保人员实体属性图

（6）下图是船舶实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\船舶.jpg](/md/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\船舶.jpg")

船舶实体属性图

（7）下图是船家实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\船家.jpg](/md/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\船家.jpg")

船家实体属性图

（8）下图是维保公司实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\维保公司.jpg](/md/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\3.1\\_\_\_\_img\维保公司.jpg")

维保公司实体属性图







### 4.3.3 数据库表设计
数据库里面的数据表存放的就是各种数据记录，我们在进行系统增删改查操作时，其实也是在对应数据表里面进行的增删改查操作，一个好的数据库能够缩短信息处理时间，所以说数据库的设计工作不容小觑，数据库里面设置哪些表，表里面的字段设计以及字段类型和字段长度等信息都要考虑周到才行，比如时间这个字段，它的数据类型就不能是int型，不然在系统操作中就会弹出输入数据格式不符合要求的报错提示。下面简单介绍船舶维保管理系统的一些数据表。

表4.1船舶表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chuanjia\_id|Integer|船家|是|
|3|weibaogongsi\_id|Integer|维保公司|是|
|4|chaunbo\_uuid\_number|String|船舶编号|是|
|5|chaunbo\_name|String|船舶名字|是|
|6|chaunbo\_photo|String|船舶照片|是|
|7|chaunbo\_file|String|附件|是|
|8|chaunbo\_types|Integer|船舶类型|是|
|9|chaunbo\_zhuangtai\_types|Integer|船舶状态|是|
|10|chaunbo\_content|String|船舶介绍|是|
|11|insert\_time|Date|上传时间|是|
|12|create\_time|Date|创建时间|是|
表4.2维修成本表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|guzhang\_id|Integer|故障|是|
|3|chengben\_uuid\_number|String|维修成本编号|是|
|4|chengben\_types|Integer|维修成本类型|是|
|5|chengben\_file|String|附件|是|
|6|chengben\_jine|BigDecimal|金额|是|
|7|chengben\_time|Date|花费时间|是|
|8|chengben\_content|String|备注|是|
|9|insert\_time|Date|录入时间|是|
|10|create\_time|Date|创建时间|是|
表4.3船家表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chuanjia\_uuid\_number|String|船家编号|是|
|3|chuanjia\_name|String|船家姓名|是|
|4|chuanjia\_phone|String|船家手机号|是|
|5|chuanjia\_id\_number|String|船家身份证号|是|
|6|chuanjia\_photo|String|船家头像|是|
|7|chuanjia\_email|String|船家邮箱|是|
|8|jinyong\_types|Integer|账户状态|是|
|9|create\_time|Date|创建时间|是|
表4.4字典表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.5公告表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|公告名称|是|
|3|gonggao\_photo|String|公告图片|是|
|4|gonggao\_types|Integer|公告类型|是|
|5|insert\_time|Date|发布时间|是|
|6|gonggao\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.6故障上报表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chaunbo\_id|Integer|船舶|是|
|3|weibaorenyuan\_id|Integer|维保人员|是|
|4|guzhang\_uuid\_number|String|故障编号|是|
|5|guzhang\_name|String|故障标题|是|
|6|guzhang\_photo|String|故障照片|是|
|7|guzhang\_address|String|故障位置|是|
|8|guzhang\_types|Integer|故障类型|是|
|9|guzhang\_content|String|故障内容|是|
|10|guzhang\_zhuangtai\_types|Integer|故障状态|是|
|11|insert\_time|Date|报修时间|是|
|12|guzhang\_text|String|维修评价|是|
|13|create\_time|Date|创建时间|是|
表4.7维保公司表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|weibaogongsi\_uuid\_number|String|维保公司编号|是|
|3|weibaogongsi\_name|String|维保公司名称|是|
|4|weibaogongsi\_fuzeren|String|负责人|是|
|5|weibaogongsi\_phone|String|维保公司手机号|是|
|6|weibaogongsi\_photo|String|公司logo|是|
|7|weibaogongsi\_address|String|公司位置|是|
|8|jinyong\_types|Integer|账户状态|是|
|9|create\_time|Date|创建时间|是|
表4.8维保计划表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chaunbo\_id|Integer|船舶|是|
|3|weibaogongsi\_id|Integer|维保公司|是|
|4|weibaorenyuan\_id|Integer|维保人员|是|
|5|weibaojihua\_uuid\_number|String|维保计划编号|是|
|6|weibaojihua\_name|String|维保计划标题|是|
|7|weibaojihua\_file|String|维保计划附件|是|
|8|weibaojihua\_types|Integer|维保计划类型|是|
|9|weibaojihua\_buwei|String|维保部位|是|
|10|weibao\_time|Date|维保时间|是|
|11|weibaojihua\_address|String|维保地点|是|
|12|weibaojihua\_content|String|维保详情|是|
|13|insert\_time|Date|上传时间|是|
|14|weibaojihua\_yesno\_types|Integer|申请状态|是|
|15|weibaojihua\_yesno\_text|String|审核意见|是|
|16|weibaojihua\_shenhe\_time|Date|审核时间|是|
|17|create\_time|Date|创建时间|是|
表4.9维保人员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|weibaogongsi\_id|Integer|维保公司|是|
|3|weibaorenyuan\_uuid\_number|String|维保人员编号|是|
|4|weibaorenyuan\_name|String|维保人员姓名|是|
|5|weibaorenyuan\_phone|String|维保人员手机号|是|
|6|weibaorenyuan\_id\_number|String|维保人员身份证号|是|
|7|weibaorenyuan\_photo|String|维保人员头像|是|
|8|weibaorenyuan\_email|String|维保人员邮箱|是|
|9|jinyong\_types|Integer|账户状态|是|
|10|create\_time|Date|创建时间|是|
表4.10管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|学生名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

# 第五章 系统实现

## 5.1 管理员功能模块的实现
### 5.1.1 船舶列表
如图5.1显示的就是船舶列表页面，此页面提供给管理员的功能有：查看船舶、新增船舶、修改船舶、删除船舶等。

![](/md/blog.015.png)

图5.1 船舶列表页面
### 5.1.2 公告信息管理
管理员可以对公告信息进行管理，可以新增公告信息,修改公告信息,删除无效的公告信息。公告信息管理界面如图5.2所示。

![](/md/blog.016.png)

图5.2 公告信息管理页面
### 5.1.3 公告类型管理
公告类型管理页面显示所有公告类型，在此页面既可以让管理员添加新的公告信息类型，也能对已有的公告类型信息执行编辑更新，失效的公告类型信息也能让管理员快速删除。下图就是公告类型管理页面。公告类型管理界面如图5.3所示。

![](/md/blog.017.png)

图5.3公告类型管理界面
### 5.1.4 维保计划管理
如图5.4显示的就是维保计划管理页面，此页面提供给管理员的功能有：新增维保计划,修改维保计划,删除维保计划。

![](/md/blog.018.png)

图5.4维保计划管理页面
### 5.1.5 维保计划类型管理
如图5.5显示的就是维保计划类型管理页面，此页面提供给管理员的功能有：新增维保计划类型,修改维保计划类型,删除维保计划类型。

![](/md/blog.019.png)

图5.5 维保计划类型管理页面











