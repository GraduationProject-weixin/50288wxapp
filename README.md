# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50288wxapp微信小程序的宠物寄养平台的设计与实现

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 绪论
## 1.1选题背景
网络和科技的进步以及人们生活条件的提高都让计算机技术越来越平民化，深入日常生活中。网络更是成为生活的必备条件，大到国家单位、科研项目，小到大街小巷都充斥着网络的身影。在日常办公中，计算机起到了文字编辑、打印、信息检索、统计等的作用。使用计算机可以使日常繁杂的信息进行科学的加工，使信息变得更加的有序、可利用。计算机技术已成为热门。

正是因为网络、科技、计算机技术使现代人的生活和工作变得便利、轻松，给实体行业带来了巨大的冲击。宠物寄养的日常管理工作也遇到了前所未有的挑战。现如今，对于宠物寄养信息的管理有很多的局限性，究其原因是因为宠物寄养管理的根本是信息的运动。在新时代的环境下，传统的管理方式不再满足用户的需求，难以管理现代的工作。传统的管理方式不仅跟不上时代的发展，还不能实现最基本的工作要求，例如对于各种信息的统计还停留在花费大量的时间进行手动审核，这种方式辐射范围非常有限，效果也非常不好。对于基本工作信息的管理也还是采用人工管理，人工管理出错率大，效率低。对于信息的传递都需要经过多人审核才可以完成，想要定期进行分析和总结更是难上加难。因为每种信息之间的关系错综复杂，在定期的统计和查询中就会出现重复出现的问题，对工作人员来说工作压力非常大。
## 1.2选题目的
现在宠物寄养管理中已有一些商家使用了基本的管理软件，这些软件都是依靠客户端，只可以特定人员使用，不能实现信息的共享。虽然可以帮助工作人员减少工作量，但从根本上还是无法满足用户的需求。这些软件都还是基于网络发展之初的要求，没有利用现代网络的技术，体现不了更为实用的功能。依靠客户端的系统开发时没有考虑园际化的问题，所以也满足不了国际化的要求。最近几年来，我国网络快速发展，传统的管理方式也越来越适应不了新时代的要求，在处理大量信息时表现不足，开发一个依托现代技术、网络技术的基于微信小程序的宠物寄养平台迫在眉捷。这类系统将会改变宠物寄养管理的现状。本课题的主要内容包括管理员和用户两个部分，管理员负责宠物寄养相关信息的管理，包括寄主信息、宠物寄养信息、宠物信息和管理员信息、宠物种类的管理等；用户可以在线寄养。本基于微信小程序的宠物寄养平台满足了用户和管理人员双方的要求，符合了信息化现代的要求。
## 1.3选题意义
想要改变传统的宠物寄养管理的现状，就需要采用更为先进的管理方式。本基于微信小程序的宠物寄养平台就是在新时代发展下开发的。本系统的开发非常有意义，体现了行业的创新。本系统是以信息管理为主导，而信息管理就是行业最大的问题，可以极大的提高工作效率。宠物寄养信息的信息化管理是目前本管理系统的核心，解决了信息化的问题就可以使宠物寄养管理更进一步。开发本系统可以使宠物寄养信息更加的清晰、透明，便于管理人员操作。使用本系统可以使管理工作实现部分自动化，减少人工，提高正确率。

本系统是将网络技术和现代的管理理念相结合，根据宠物寄养信息的特点进行重新分配、整合形成动态的、分类明确的信息资源，实现了宠物寄养信息的自动化，减少人工管理过程，为管理人员的决策提供帮助。使用新型的管理系统已成为时代的标志，本系统可以提高宠物寄养管理的竞争力，提高信息统计效率，使工作人员的管理工作更加轻松。











# 第2章 系统分析
## 2.1使用关键技术分析
### 2.1.1Java语言介绍
Java语言跟c++语言非常的相似，可以说是从c++上进行衍生出来的一个新型开发语言，他充分吸收了其他语言的优点，而避开了它们的缺点，使编程语言更加的简单，而且java系统非常的小，摒弃掉了之前的运算符重载，然后造成的卡顿现象，然后添加了垃圾自动清理，增加了开发的简单和可靠性。当然了java最大的特点是平台独立性，只要可以支持java虚拟机环境，就可以直接运行所有程序，而且还是面向对象开发的技术，有很好的封装行，采用了动态编码技术，可以使程序更好的呈现。可以多线程进行运行，用户随时可以加入新的 实例然后不影响整体程序执行，使开发更有灵活性，因为java是在公共密钥技术上进行建立开发的，所以也有一定的安全保障，除此之外，还有一定的跨平台性，可扩展性等优点，可以和不同的操作环境进行互联共享，所以java语言是目前使用最广泛的一个语言开发技术。
### ` `2.1.2Mysql数据库介绍
Mysql数据库最初是由瑞典MySQL AB公司进行开发出来的，后来被SUN公司进行了收购，然后进行了一系列的优化改进，最后被oracle公司收购。mysql数据库是一种关系型数据库，而且采用的是开发式结构，支持大多的平台，而且功能很多，性能很高。Mysql数据库最大的特性就是把自己所编译好的数据进行单独存放，而不是跟传统数据库一样，全部放到一起，这样的话就保证了数据的安全性和灵活性，大大的提供了数据的访问速度，当用户需要调取数据时候可以直接通过sql语句进行查询。Mysql的数据存储非常的稳定，而且是一个开源代码，使用成本非常的低，最大的特点就是安装包非常的小，对硬件没有特别要求，不会造成硬件卡顿，非常便于维护。Mysql还支持多种语言，比如php ，安卓等，都可以支持数据存储。
### 2.1.3微信小程序介绍
微信小程序是一种不用下载就能使用的应用，也是一项创新，经过将近两年的发展，已经构造了新的微信小程序开发环境和开发者生态。微信小程序也是这么多年来中国IT行业里一个真正能够影响到普通程序员的创新成果，已经有超过150万的开发者加入到了微信小程序的开发，与我们一起共同发力推动微信小程序的发展，微信小程序应用数量超过了一百万，覆盖200多个细分的行业，日活用户达到两个亿，微信小程序还在许多城市实现了支持地铁、公交服务。微信小程序发展带来更多的就业机会，2017年小程序带动就业104万人，社会效应不断提升。 
### 2.1.4 SSM框架介绍
SSM（Spring+SpringMVC+MyBatis）框架集由Spring、MyBatis两个开源框架整合而成（SpringMVC是Spring中的部分内容），常作为数据源较简单的web项目的框架。Spring就像是整个项目中装配bean的大工厂，在配置文件中可以指定使用特定的参数去调用实体类的构造方法来实例化对象。也可以称之为项目中的粘合剂。Spring的核心思想是IoC（控制反转），即不再需要程序员去显式地`new`一个对象，而是让Spring框架帮你来完成这一切。SpringMVC在项目中拦截用户请求，它的核心Servlet即DispatcherServlet承担中介或是前台这样的职责，将用户请求通过HandlerMapping去匹配Controller，Controller就是具体对应请求所执行的操作。SpringMVC相当于SSH框架中struts。mybatis是对jdbc的封装，它让数据库底层操作变的透明。mybatis的操作都是围绕一个sqlSessionFactory实例展开的。mybatis通过配置文件关联到各实体类的Mapper文件，Mapper文件中配置了每个类对数据库所需进行的sql语句映射。在每次与数据库交互时，通过sqlSessionFactory拿到一个sqlSession，再执行sql命令。
## 2.2系统可行性分析
可行性分析主要是分析本系统是否有开发的必要性，是否存在开发难度，是否能实现一定的商业价值，所以主要是从技术可行性，经济可行性，操作可行性方面进行研究分析。
### 2.2.1经济可行性
本系统在开发中所使用的技术和软件都是免费的，本系统的运行也只需要电脑。本系统没有抄袭市面上的任何网站、系统，不管是界面风格，还是后台代码，都是自己原创，所以不存在版权方面的纠纷，而且开发环境都是开源的，开源共享的，所以不管是硬件方面还是软件方面都不存在侵权行为。综合分析，本系统在经济可行性上没有问题。
### 2.2.2技术可行性
开发本系统采用目前比较主流的Java开发语言，具有很好的扩展性和平台兼容性，而且功能非常强大，易操作。页面技术采用Vue技术，Vue可以实现动态编码，通过Html进行页面效果呈现，最大的特点就是本系统采用SSM框架进行开发，SSM可以不受本机系统的限制，可以把数据存放到服务器，用户可以直接通过浏览器进行系统访问，对于用户来说非常的简单省事。所以从技术层面考虑是非常可行的。
### 2.2.3操作可行性
本系统采用的全是可视化操作界面，不管是对于系统的管理者还是用户者，都可以在没有任何编程背景的基础下进行系统操作，而且系统界面还存在各种功能提示，用户都可以简单操作，所以在操作可行性上是可行的。
## 2.3系统需求分析
在当今信息化社会发展的条件下人们越来越追求自动化，基于微信小程序的宠物寄养平台组成的多样化是现代宠物寄养常用的管理手段。这种情况下就造成多种信息的暴增，如果还是采用传统的管理方式势必会造成信息的拥堵，用户的烦躁，工作水平的降低。

本基于微信小程序的宠物寄养平台采用了SSM框架进行设计，结构了网络的技术，可以单独运行，不再需要固定的客户端。可以实现宠物寄养信息的快速管理，保证了工作水平，提高用户的好评率。
## 2.4系统功能分析
本系统包括微信部分和电脑部分，在微信部分展示了寄养环境，用户可以选择喜欢的环境进行宠物的寄养并在线支付寄养费用。管理员可以管理宠物信息、宠主信息和寄养信息、寄养环境信息等。
## 2.5性能需求
`　`性能需求主要是对系统存储和后续存储的要求，还有对系统运行的速度和系统的安全性进行考虑。对于系统的性能要求还需要操作的流畅性、理解性以及可靠、维护性。用户使用本系统时要求系统非常好理解，便于用户的操作。售后人员使用本系统时要求系统可读和便于测试。可靠性则指的是系统的准确和运行稳定，在尽可能的情况下利用所有的工具可以使上述要求得到最大的满足。
## 2.6系统用例图
本系统的主要角色为管理员和用户，管理员的用例包括宠主管理、宠物信息管理、宠物种类管理、宠物寄养管理、寄养环境管理、评价管理和系统管理。管理员的用例图如下图2.1所示：

![](/md/blog.001.png)

图2.1管理员用例图

用户的用例包括浏览寄养环境信息和进行寄养管理寄养信息等。用户用例图如下图2.2所示：

![](/md/blog.002.png)

图2.2用户用例图
## 2.7系统操作流程图
本系统主要的功能为用户在线寄养，管理员审核宠物寄养信息和宠主信息，管理网站基本信息。系统操作的整体流程如下图2.3所示：

![](/md/blog.003.png)   　图2.3系统操作流程图





# 第3章 系统设计
## 3.1系统功能结构设计
一个好的设计不止是功能完整，操作流畅，还要符合用户的审美和界面的友好。在进入正式系统实施前，不可缺少的步骤为系统的总体结构设计，本系统为实用性的系统，所以开发的功能都是针对宠物寄养信息相关的。本系统的结构可以分为管理员界面和用户功能界面。在管理员界面主要展示的是用户和宠物寄养相关的信息，在用户界面展示的主要是查看信息、在线寄养和寄养管理。本系统的总体结构图如下图3.1所示：

![](/md/blog.004.png)             　图3.1基于微信小程序的宠物寄养平台的功能结构图
## 3.2数据库设计
### 3.2.1数据库概念结构设计
数据库的概念结构设计就是需要在系统分析的过程中分析开发本系统是要做什么，然后设计出大的框架，根据大的框架把系统进行转换成怎么做的物理模型。然后再进行设计。

`　　`在所有的系统设计中数据库的设计占有举足轻重的地位，选择合适的数据库软件进行设计非常重要。因为本系统的功能非常有针对性，没有进行扩展，所以本系统采用小型轻便的MySQL软件进行设计。数据库的安全保障着系统里数据的安全，本系统的主要数据为用户信息、宠物寄养信息、公告信息以及评论、寄养环境信息等。本系统的ER关系图如下图3.2所示：

![](/md/blog.005.png)

图3.2实体关系ER图

（1）管理员的属性包括编号、用户名和密码，管理员的ER图如下图3.3所示：

![](/md/blog.006.png)

图3.3管理员信息ER图

（2）用户信息管理为本系统的核心功能，主要包含用户的各种信息的记录，详细的用户信息ER图如下图3.4所示：

![](/md/blog.007.png)

图3.4用户信息ER图

(3)宠物寄养信息的ER图如下图3.5所示：

![](/md/blog.008.png)

图3.5宠物寄养信息ER图

(4)公告信息的属性包括编号、标题和发布时间等，公告信息ER图如下图3.6所示：

![](/md/blog.009.png)

图3.6公告信息ER图

(5)评论信息ER图如下图3.7所示：

![](/md/blog.010.png)

图3.7评论信息ER图
### 3.2.2数据库表设计
本系统的数据库表有管理员信息表、宠物信息表、寄养环境信息表等。数据库表如下表3.1-3.10所示：

表3.1 chongwujiyang

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|jiyangdanhao|varchar|200| | | | |是| | |
|4|chongwumingcheng|varchar|200| | | | |是| | |
|5|chongwuzhonglei|varchar|200| | | | |是| | |
|6|chongwuxingbie|varchar|200| | | | |是| | |
|7|shifoujueyu|varchar|200| | | | |是| | |
|8|chongwunianling|varchar|200| | | | |是| | |
|9|kaishishijian|date| | | | | |是| | |
|10|jiyangshizhang|int|11| | | | |是| | |
|11|tuoguanfeiyong|float| | | | | |是| | |
|12|zongfeiyong|float| | | | | |是| | |
|13|chongzhuxingming|varchar|200| | | | |是| | |
|14|chongzhuzhanghao|varchar|200| | | | |是| | |
|15|yuyueshijian|datetime| | | | | |是| | |
|16|jiyangyuanyin|longtext| | | | | |是| | |
|17|beizhu|longtext| | | | | |是| | |
|18|ispay|varchar|200| | | | |是|未支付| |

||
| :- |
表3.2 chongwuzhonglei

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|chongwuzhonglei|varchar|200| | | | |否| | |

||
| :- |
表3.3 chongzhu

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|chongzhuzhanghao|varchar|200| | | | |否| | |
|4|chongzhuxingming|varchar|200| | | | |否| | |
|5|mima|varchar|200| | | | |否| | |
|6|xingbie|varchar|200| | | | |是| | |
|7|touxiang|varchar|200| | | | |是| | |
|8|lianxidianhua|varchar|200| | | | |是| | |

||
| :- |
表3.4 config

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|name|varchar|100| | | | |否| | |
|3|value|varchar|100| | | | |是| | |

||
| :- |
表3.5 discussjiyanghuanjing

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|refid|bigint|20| | | | |否| | |
|4|userid|bigint|20| | | | |否| | |
|5|nickname|varchar|200| | | | |是| | |
|6|content|longtext| | | | | |否| | |
|7|reply|longtext| | | | | |是| | |

||
| :- |
表3.6 jiyanghuanjing

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|quyumingcheng|varchar|200| | | | |是| | |
|4|tuoguanfeiyong|varchar|200| | | | |是| | |
|5|xiaoducishu|varchar|200| | | | |是| | |
|6|mianji|varchar|200| | | | |是| | |
|7|huanjing|varchar|200| | | | |是| | |
|8|xiangqing|longtext| | | | | |是| | |

||
| :- |
表3.7 news

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|title|varchar|200| | | | |否| | |
|4|introduction|longtext| | | | | |是| | |
|5|picture|varchar|200| | | | |否| | |
|6|content|longtext| | | | | |否| | |

||
| :- |
表3.8 storeup

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|userid|bigint|20| | | | |否| | |
|4|refid|bigint|20| | | | |是| | |
|5|tablename|varchar|200| | | | |是| | |
|6|name|varchar|200| | | | |否| | |
|7|picture|varchar|200| | | | |否| | |
|8|type|varchar|200| | | | |是|1| |
|9|inteltype|varchar|200| | | | |是| | |

||
| :- |
表3.9 token

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|userid|bigint|20| | | | |否| | |
|3|username|varchar|100| | | | |否| | |
|4|tablename|varchar|100| | | | |是| | |
|5|role|varchar|100| | | | |是| | |
|6|token|varchar|200| | | | |否| | |
|7|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|8|expiratedtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |

||
| :- |
表3.10 users

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|username|varchar|100| | | | |否| | |
|3|password|varchar|100| | | | |否| | |
|4|role|varchar|100| | | | |是|管理员| |
|5|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |

||
| :- |
## 3.3界面设计
### 3.3.1界面设计原则
系统的界面设计至关重要。良好的界面可以给人好的感受和良好的操作体验。在系统界面设计时需要遵守的原则为：

1. 不同的身份使用的功能不同，所以要设计不同的登录界面以便来区分不同的身份。在设计界面时首先要考虑好身份的区别和不同身份的界面功能，根据不同的身份来设计不同的操作界面；
1. 要采用尽可能减少手动输入的方式进行设计。对于某些信息如果可以减少输入就都自动生成，这样也可以减少用户手动输入时的错误；
1. 设置大量的帮助词和提示词来指导用户的操作，减少用户的记忆。
### 3.3.2数据输入界面设计
为了减少用户手动输入的次数，增加系统的容忍有力，在数据输入界面设计时就要注意以下几点：

1. 对于多种字段需要输入里可以采用列表框。比如在输入宠物类型，寄养时间时，可以选择信息进行填写。对于需要大量文字描述的特定信息时可以选择特定缩写、数字等来代替；
1. 对于同一类型的信息在输入时可以采用统一的界面风格，可以培养用户的输入习惯。对于特定信息在输入时可以设定好数据类型，比如在输入手机号时只能输入数字，在输入数量时，只能输入数字。















# 第4章 系统详细设计与实现
## 4.1登录功能模块
### 4.1.1登录功能模块概述
登录功能包括用户登录和管理员登录，在登录界面设计中包括用户名和密码、角色的检验。用户名和密码、角色的检验过程由数据库自动完成，此过程需要1秒左右。首先由用户填写账号和密码，选择角色，然后点击登录系统，数据库自行对用户名和密码进行对比，所填写数据正确方能进行登录，所填写数据错误则需要返回登录界面重新登录。用户登录界面的设计运行界面效果如下图4.1所示：

![](/md/blog.011.png)

图4.1系统用户登录界面效果
### 4.1.2登录功能模块流程图
用户登录功能，本系统的流程为先进行登录，在登录中需要输入账号和密码并选择相对应的身份才可以登录成功，管理员登录后的功能主要为管理，用户登录后的功能主要为在线寄养。用户登录流程图如下图4.2所示：

![](/md/blog.012.png)

图4.2用户登录流程图
## 4.2 宠物寄养管理功能模块
### 4.2.1在线寄养功能模块概述
用户可以在线寄养，首先需要选择寄养环境然后填写寄养信息、支付费用完成寄养。用户填写寄养信息功能的实现界面如下图4.3所示：

![](/md/blog.013.png)

图4.3填写寄养明细界面

用户管理寄养信息的实现界面如下图4.4所示：

![](/md/blog.014.png)

图4.4用户管理寄养信息的实现界面
### 4.2.2用户在线寄养功能的流程图
用户在线寄养的流程为先进行登录，然后输入寄养信息进行发布。用户发布寄养信息功能的流程如下图4.5所示：

![](/md/blog.015.png)

图4.5用户发布寄养信息流程图
## 4.3用户注册功能模块
### 4.3.1用户注册功能模块概述
用户注册可以实现拥有账号和密码。用户注册功能界面的运行效果界面如下图4.6所示：

![](/md/blog.016.png)

图4.6用户注册功能界面的运行效果 
## 4.4首页功能模块
### 4.4.1首页功能模块概述
首页可以看到所有的公告信息和寄养的环境信息。首页功能的实现界面如下图4.7所示：

![](/md/blog.017.png)

图4.7首页功能界面实现
## 4.5我的界面模块
我的界面主要的功能就是对寄养信息、收藏信息进行管理。我的功能实现界面如下图4.8所示：

![](/md/blog.018.png)

图4.8我的功能实现界面
## 4.6管理员中心界面模块
管理员主要的功能为宠主管理、系统管理、宠物种类管理、寄养环境管理和宠物寄养管理等。实现界面如下图4.9所示：

![](/md/blog.019.png)

图4.9管理员中心实现界面


# 第5章　系统功能测试
## 5.1测试环境
本系统的测试环境为安装有微信开发者工具软件和MySQL数据库的电脑一台。本人在自己的电脑上进行测试。

对于一些错误不需要测试就可以自动提示进而修改，像在编码时的语法、公式等的错误微信开发者工具软件可以进行提示，但还有一部分的错误不容易被发现，必须进行测试才可以修改。这些错误一般都是由错误的操作或者输入不合法的数据才发生的，而且这些错误还具有有时出现，有时不出现的特点。对于此类的错误在发现非常困难。

系统测试是所有程序员都会面临的问题，是必不可少的步骤。一般对于系统的测试开始于系统设计完成后，这种测试可以针对简单不复杂的系统。但对于一些大的项目的系统在系统的编写中就要开始测试，每到一个阶段就开始测试，用这种方法来保证下一个阶段编写的正确性。这种测试可以保证每个部分都是正确的，可以方便在以后的测试中减少工作量，同时也方便错误的找出。对于系统在编码过程中，不管采用什么方法和步骤进行编写设计都会不可避免的产生错误，即使采用最先进的技术和语言、环境来进行设计，也只能进行简单错误的提醒。这时候就需要进行系统测试才可以把所有的错误找出来。
## 5.2功能测试
在本论文里简单阐述几个功能的测试用例。
### 5.2.1用户登录功能的测试
对用户登录功能的测试过程为输入不同的账号和密码进行登录提交，查看结果提示是否可以符合要求，对用户登录功能的测试过程如下表5.1所示：

表5.1用户登录测试过程表

![](/md/blog.020.png)
### 5.2.2发布信息功能的测试
管理员可以发布信息，对发布信息功能的测试采用输入用例信息和不输入用例信息进行提交，看是否可以出来预期的结果，发布信息功能的测试过程如下表5.2所示：

表5.2信息发布功能的测试过程表

![](/md/blog.021.png)
## 5.3测试总结
根据测试发现本系统的优点表现在：

1. 本系统的设计是针对宠物寄养管理，非常有特色，本系统的实现可以为宠物寄养管理带来前景；
1. 本系统的兼容性很强，可以在多种环境中进行运行，只需要手机和微信就可以进行运行，数据库采用的MySQL也非常的简单，可以使数据快速的反应；
1. 所有的数据在设置时采用了格式，对于特定的数据采用了选择框进行自动填写，减少了出错率，提高了文字输入的速度；
1. 界面站在用户的角度设计，所以非常的操作方便，对于不懂编程的人员来说也非常的好学。

当然本系统也还存在很多的问题，需要进行不断的改善。本系统的不足主要表现在：

（1）用户界面和功能界面都不够美观，因为素材和技术水平的有限使界面设计并不是太满意。所有的界面只是采用了简单的表格和文字、图片来进行美化，颜色也没有协调到最好，所以界面给人的感觉太过于简单；

（2）系统中还有很多的废弃代码，数据字段也没有做到精短，这样使系统在运行中速度反应不好；

（3）本系统所设计的功能都是最需要的功能，没有额外再进行扩展。

针对以上三个问题，本人想到了解决问题并加入改进，

1. 对于界面美观问题，本人去资源库里下载了更多的图片材料，也去相关的商用网站里学习了各种配色，利用制图工作进行图片的加工，使图片更加的符合主题，针对不同的信息设置了不同的颜色使界面看起来更为丰富；
1. 对于代码和数据的问题，本人进行再一次的减化，把废弃代码和数据找出来进行删除，提高系统的运行效率，对数据库的范式进行进一步的优化；
1. 对于功能方面，本人参考其它系统尽自己能力进行扩展。
#
#
#
#
#
#
#
#

# 总　结
通过本次毕业设计，让我真正意识到了纸上谈兵的真正含义，看着平时老师上课教的内容都懂，都熟悉，可真正的让自己去实际独立完成一个项目时，才知道了原来理论和现实还是有很大的一定差距。首先开发系统的第一步给人的第一种感觉就是无从下手，根本不知道从哪里开始，然后可以干什么，完全一头雾水。然后在开发的过程中，更是面临各种各样的挑战，最大的难题就是没办法把自己所说知识融会贯通到一起，导致了漏洞百出。比如代码编好了，数据库表也建立好了，就是没办法链接成功，最后才发现原来是字符集选择不对，等等很多问题。通过本次设计让我充分认识到了自己的不足，只有通过更多的实践练习才能慢慢的熟悉，一步一步成长，所以学无止境，还要继续加油努力，不停的发现问题，解决问题。虽然本次系统最终还是在老师和同学的帮助下顺利完成了，但是还是有很大的不足需要改进，比如界面设计不够美观，代码处理不够精简等，我还是要继续努力，继续加油，通过不断的学习，更加的完善。
#

#
#
#












