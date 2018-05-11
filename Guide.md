# 资源导航

在这里提供该项目资源的快捷导航，点击相关目录从进一步查看信息，对于具体条目中资源按推荐程度排序：

1. [Python介绍与下载：Python的简介、版本及获取地址](#1. Python介绍与下载)
2. [Python文档与模块：Python文档以及热门模块 ](#2. Python文档与模块)
3. [学习Python语言：提供从入门到高阶的学习资源以及不同学习方向的路径](#3. 学习Python语言)
4. [Python的应用与实战：Python在web开发、数据处理、网络爬虫等方面的应用和实战例子](#4. Python的应用与实战)
5. [Python求职：Python面试技巧和职位信息](#5. Python求职)
6. [其他待归类资源：python工具和软件等](#6. 其他待归类资源)

## 1. Python介绍与下载

### 1.1 Python是什么

[Python 维基百科](https://zh.wikipedia.org/wiki/Python) ：Python，是一种广泛使用的高级编程语言，属于通用型编程语言，由吉多·范罗苏姆创造，第一版发布于1991年。可以视之为一种改良的LISP。作为一种解释型语言，Python的设计哲学强调代码的可读性和简洁的语法。相比于C++或Java，Python让开发者能够用更少的代码表达想法。

[Python简介|菜鸟教程](http://www.runoob.com/python/python-intro.html) 中简练地介绍了Python的特点和发展历史。

[Python官方网站](https://www.python.org/) 英文，在这里获取Python的最新官方信息

### 1.2 Python的版本

Python主要有2.x和3.x两个版本，[Python2.x与3.x版本区别| 菜鸟教程](http://www.runoob.com/python/python-2x-3x.html)。

有关如何更换Python版本及共存问题，以下为在互联网检索下的筛选结果：

- [Mac OS X 上如何切换默认的Python 版本？ - 知乎](https://www.zhihu.com/question/30941329)
- [PyCharm切换Python版本- CSDN博客](https://blog.csdn.net/sinat_36246371/article/details/55251854)
- [Ubuntu16.04下完美切换Python版本- CSDN博客](https://blog.csdn.net/CYM_LMY/article/details/78315139)
- [技术|如何将Debian Linux 中的默认的Python 版本切换为替代版本](https://linux.cn/article-6970-1.html)
- [windows下多个python版本共存,pip使用- CSDN博客](https://blog.csdn.net/qq_22194315/article/details/77968609)
- [Linux下多版本python共存| Airghc](www.airghc.top/2017/01/17/haha/)
- [为Mac 设置Python多版本开发环境· GitHub](https://gist.github.com/miminus/671de665a440ef12cafc31e7a97acc89)

### 1.3 Python的发行版

有关各版本间选择问题参见[Python科学计算发行版](https://blog.csdn.net/u014636245/article/details/52948084)，目前流行的Python的科学计算发行版：

- Python（x，y）：免费的科学和工程开发软件，用于基于Python编程语言，Qt图形用户界面和Spyder交互式科学开发环境的数值计算，数据分析和数据可视化。[官网](https://python-xy.github.io/)
- WinPython：Python(x,y)的作者开发，GUI基于PyQt，关注便携式安装体验。[官网](https://winpython.github.io/)
- Anaconda：Python语言的免费增值 开源发行版，用于进行大规模数据处理, 预测分析, 和科学计算, 致力于简化包的管理和部署。 Anaconda使用软件包管理系统Conda进行包管理。[官网](https://anaconda.org/)
- Canopy：Enthought 公司发行，专为科学家和工程师的工作流程打造，将精简的集成分析环境与超过450种科学分析软件包相结合。[官网](https://www.enthought.com/product/canopy/)

此外，还有

Sage：是一个基于GPL协议的开源数学软件。它使用Python作为通用接口，将现有的许多开源软件包整合在一起，构建一个统一的计算平台。[SageMath - 中文官网](www.sagemath.org/zh)

### 1.4 国内相关的镜像站

由于某些原因，部分网站在中国大陆境内无法访问或访问速度缓慢，为了解决这个问题，有很多机构和组织为其相关资源提供了镜像站点，用户可以从这些镜像站点获取与原网站相同的资源，并提供文件校验码供用户核对保证所下载的文件未遭第三方更改。以下是人们较为常用的访问稳定的镜像源：

#### 安装包等文件资源的下载

以下为主要的国内开源镜像站，提供各项开源资源的下载。

##### 教育网主要镜像站

- **[中国科学技术大学开源软件镜像](https://mirrors.ustc.edu.cn/)：推荐**，[中国科学技术大学网络信息中心](http://ustcnet.ustc.edu.cn/) 提供支持。 是 Debian, Ubuntu, Fedora, Archlinux, CentOS 等多个发行版的官方源。目前是中国大陆高校访问量最大，收录最全的开源软件镜像。 提供[anacoda](https://mirrors.ustc.edu.cn/anaconda/)，[pythonxy](https://mirrors.ustc.edu.cn/pythonxy/)和[pypi](https://mirrors.ustc.edu.cn/pypi/)镜像。
- **[清华大学开源软件镜像站](https://mirror.tuna.tsinghua.edu.cn/)：推荐**，由清华大学信息化技术中心支持创办，由清华大学 TUNA 协会运行维护。提供[anaconda](https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/)和[pypi](https://mirrors.tuna.tsinghua.edu.cn/help/pypi/)镜像。
- **[上海大学开源镜像站](https://mirrors.shu.edu.cn/)：推荐**，由[上海大学信息化办公室](http://www.its.shu.edu.cn/)提供基础设施支持，由[上海大学NITA实验室](https://nita.shu.edu.cn/)提供服务器支持，由[上海大学开源社区](https://osc.shu.edu.cn/)负责管理维护。本站所有源均可通过HTTP、FTP和RSYNC方式访问，RSYNC的访问模块名为源的HTTP子目录名。 提供[anaconda](https://mirrors.shu.edu.cn/anaconda)和[pypi](https://mirrors.shu.edu.cn/pypi)镜像。
- **[北京理工大学开源软件镜像](http://mirror.bit.edu.cn/web/)：推荐**，由北京理工大学网络信息技术中心提供的北理工开源镜像服务。可以通过 HTTP 或 RSYNC 协议访问此服务器的资源，服务器分域名提供 IPv4 和 IPv6 的访问地址。

完整列表如下：

- **东北地区：**东北大学（[IPv4 & IPv6](http://mirror.neu.edu.cn/), [IPv6](http://mirror.neu6.edu.cn/)）、大连理工大学（[IPv4 & IPv6](http://mirror.dlut.edu.cn/)）、大连东软信息学院（[IPv4 & IPv6](http://mirrors.neusoft.edu.cn/)）、哈尔滨工业大学（[IPv4 & IPv6](http://run.hit.edu.cn/), [IPv6](http://run.hit6.edu.cn/)）
- **华北地区：**清华大学（[IPv4 & IPv6](http://mirrors.tuna.tsinghua.edu.cn/), [IPv4](http://mirrors.4.tuna.tsinghua.edu.cn/), [IPv6](http://mirrors.6.tuna.tsinghua.edu.cn/)）、北京理工大学（[IPv4](http://mirror.bit.edu.cn/), [IPv6](http://mirror.bit6.edu.cn/)）、北京交通大学（[IPv4 & IPv6](http://mirror.bjtu.edu.cn/)）、天津大学（[IPv4](http://mirror.tju.edu.cn/), [IPv6](http://mirror.tju6.edu.cn/)）
- **华东北地区：**中国科学技术大学（[IPv4 & IPv6](http://mirrors.ustc.edu.cn/), [IPv4](http://mirrors4.ustc.edu.cn/), [IPv6](http://mirrors6.ustc.edu.cn/)）
- **华中地区：**华中科技大学（[IPv4](http://mirrors.hust.edu.cn/)）、中国地质大学（[IPv4 & IPv6](http://mirrors.cug.edu.cn/), [IPv6](http://mirrors.cug6.edu.cn/)）
- **华东南地区：**上海交通大学（[IPv4](http://ftp.sjtu.edu.cn/), [IPv6](http://ftp6.sjtu.edu.cn/)）、浙江大学（[IPv4 & IPv6](http://mirrors.zju.edu.cn/)）、厦门大学（[IPv4 & IPv6](http://mirrors.xmu.edu.cn/), [IPv6](http://mirrors.xmu6.edu.cn/)）
- **华南地区：**中山大学（[IPv4](http://mirror.sysu.edu.cn/)）
- **西北地区：**兰州大学（[IPv4 & IPv6](http://mirror.lzu.edu.cn/)）
- **西南地区：**重庆大学（[IPv4](http://mirrors.cqu.edu.cn/)）

##### 非教育网的主要镜像站

- [网易开源镜像站](http://mirrors.163.com/):pypi
- [阿里开源镜像站](http://mirrors.aliyun.com/):pypi
- [搜狐开源镜像站](http://mirrors.sohu.com/):python

#### pip源地址

以下国内网站提供pypi的镜像，需要配置Python中的相关参数为站点地址，配置方法参见其站内帮助页面

- 中国科学技术大学：[http://pypi.mirrors.ustc.edu.cn/simple/](https://link.jianshu.com?t=http://pypi.mirrors.ustc.edu.cn/simple/)  ，[使用帮助](https://mirrors.ustc.edu.cn/help/pypi.html)
- 清华：[https://pypi.tuna.tsinghua.edu.cn/simple](https://link.jianshu.com?t=https://pypi.tuna.tsinghua.edu.cn/simple)，[使用帮助](https://mirrors.tuna.tsinghua.edu.cn/help/pypi/)
- 上海大学：https://pypi.shuosc.org/simple，[使用帮助](https://mirrors.shu.edu.cn/help/pypi.html)
- 豆瓣：[http://pypi.douban.com/simple](https://link.jianshu.com?t=http://pypi.douban.com/simple)
- 阿里：http://mirrors.aliyun.com/pypi/simple/
- V2EX：[http://pypi.v2ex.com/simple](https://link.jianshu.com?t=http://pypi.v2ex.com/simple)  **不推荐，似乎已停止维护** 。



## 2. Python文档与模块

### 2.1 Python 文档

广义上的与python相关的文档，还包括Python重要第三方模块的文档。以下是Python官方文档：

- **[Documentation(Python 文档)](https://www.python.org/doc/)**：英文，Python的官方标准文档，教程和指南，涵盖Python语言的 标准用法，可以免费下载和在线浏览。提供针对初学者、中等和高级的教程；提供其3.x版本和2.x版本的标准文档。

  - **[Python3的稳定版本文档](https://docs.python.org/3/)** ：**推荐**，可选英、法、日、韩四种语言，目前最新的稳定版本的文档，包括Python的入门教程、库参考、语言语法参考、Python设置和用法 、Python模块安装和分发、针对C/C++程序员的扩展和嵌入教程等内容。

- **[OpenBookProject中的Python中文文档](http://docspy3zh.readthedocs.io/en/latest/)**：Python中文文档：**推荐**。[DocsPy](https://code.google.com/archive/p/openbookproject/wikis/DocsPyZh.wiki) 翻译小组的汉化工程，只包括Python官方文档。

  ##### 以下资源除Python官方文档外，还包括一些重要的第三方模块文档的中文翻译，推荐搭配使用。

- **[一译Python文档](https://yiyibooks.cn/)** ：Python中文文档：**推荐** 。包括Python3文档、相关图书翻译、一些重要的第三方模块的中文翻译。

- **[Python Chinese documents](https://ictar.gitbooks.io/python-doc-zh/)** Python中文文档：**推荐** ，与Python相关的文档的中文版本，包括了Python常规文档和库文档，以及相关文章的中文译版，**部分内容未完全翻译**。主要涵盖的内容有：python 常规文档 、Web框架、DevOps工具、测试、硬件、科学计算和数据分析、自然语言处理、机器学习、函数式编程、图像处理、新闻订阅资源。

- **[PythonTab在线手册](http://docs.pythontab.com/)  ：中文译版，优化手机端浏览，推荐，有广告。** Python手册，Scrapy手册，Django手册，Redis手册，Flask手册，Github手册，Jinja2手册，Python3手册，Nodejs手册，Beautifulsoup手册，Tornado手册，Nginx手册，Jinja2手册，TensorFlow手册。

  ##### 更多，有关文档学习的资源：

- **[PyMOTW-3](https://pymotw.com/3/#)** ：**英文，推荐，被诸多参考源推荐。**Python Module of the Week，每周一个Python 3 模块。 每篇介绍一个 Python 标准库的使用，提供索引查找。 
  - [PyMOTW](https://pymotw.com/2/) ：PyMOTW-3的原版，介绍Python2.7的标准库。有中文译版，中文版由[ZoomQuiet](https://readthedocs.org/profiles/ZoomQuiet/) 翻译。[英文版](https://pymotw.com/2/) | [中文版](http://pymotwcn.readthedocs.io/en/latest/index.html#)

### 2.2 Python 软件包

包括Python常用的标准库、第三方模块以及软件、工具等的资源集合。

- **[Python资源 - 伯乐在线 awesomepython中文版](http://hao.jobbole.com/?catid=144)**：**中文，推荐，译版及原版被诸多参考源推荐**。Python开发中常用的开发库、开发工具、开发框架、以及学习指南等资源，还包括Python不同应用中所需的库和工具的集合，其内容十分丰富。

- **[Python资源整理合集 - jing 薄荷微凉](https://www.8u7u6u.com/?post=281)** ：中文，**推荐**，最近更新。由网站 [薄荷微凉](https://www.8u7u6u.com/) 的作者 [jing](https://www.8u7u6u.com/?author=1) 整理，资源十分丰富，内容包括：网页框架、用户图形接口相关框架、网络相关、数据库相关、游戏相关、开源框架、大数据与人工智能相关、网络爬虫、测试与代码分析审核、安全与破解相关、图表及图像相关、语音相关、运维相关、树莓派、第三方平台、IDE、其他库、博客与播客及书籍文档等。

- **[Python开源库 - 掘金](https://juejin.im/repos/filtered?tag=Python)** ：中文，**推荐**。掘金社区整理的Python开源库，提供热门和最新库分类浏览，同时也提供[科学计算](https://juejin.im/repos/filtered?tag=Python_%E7%A7%91%E5%AD%A6%E8%AE%A1%E7%AE%97) 、[机器学习](https://juejin.im/repos/filtered?tag=Python_%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0) 、[深度学习](https://juejin.im/repos/filtered?tag=Python_%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0) 、[数据库](https://juejin.im/repos/filtered?tag=Python_%E6%95%B0%E6%8D%AE%E5%BA%93) 、[网络爬虫](https://juejin.im/repos/filtered?tag=Python_%E7%BD%91%E7%BB%9C%E7%88%AC%E8%99%AB) 、[GUI](https://juejin.im/repos/filtered?tag=Python_GUI)[游戏开发](https://juejin.im/repos/filtered?tag=Python_%E6%B8%B8%E6%88%8F%E5%BC%80%E5%8F%91) 、[运维](https://juejin.im/repos/filtered?tag=Python_%E8%BF%90%E7%BB%B4) 、 [Web 开发](https://juejin.im/repos/filtered?tag=Python_Web%20%E5%BC%80%E5%8F%91)、[科学计算](https://juejin.im/repos/filtered?tag=Python_%E7%A7%91%E5%AD%A6%E8%AE%A1%E7%AE%97) 、[机器学习](https://juejin.im/repos/filtered?tag=Python_%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0) 、[深度学习](https://juejin.im/repos/filtered?tag=Python_%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0) 、[数据库](https://juejin.im/repos/filtered?tag=Python_%E6%95%B0%E6%8D%AE%E5%BA%93) 等分类下的库。 可选用Github、微博和微信第三方账号登陆，登陆后可**定制开源库推荐**。

- **[python_reference](https://github.com/rasbt/python_reference)** ：GitHub上由[rasbt](https://github.com/rasbt) 发起的Python参考资源，**英文**，包括了有用的脚本，教程和其他Python相关的东西，文档提供便捷的链接导航。内容包括：Python技巧和教程 、Python和网络 、 算法 、绘图和可视化 、性能、Python和“数据科学” 、有用的脚本和代码段、新闻、Python学习资源以及作者最爱的Python项目和软件包。

  ##### 针对特定领域或用途的资源集合

- 网络爬虫：**[awesome-web-scraping](https://link.juejin.im/?target=http%3A%2F%2Flink.zhihu.com%2F%3Ftarget%3Dhttps%253A%2F%2Fgithub.com%2Florien%2Fawesome-web-scraping%2Fblob%2Fmaster%2Fpython.md)**：**英文，推荐**。**爬虫工具集合**，由[lorien](https://github.com/lorien)整理包含Python网页抓取和数据处理相关的库。 原网页为英文版，中文版参见： [SDK.cn技术文章](https://sdk.cn/news/8050) 。主要内容包括：网络相关的通用库以及异步的相关资源、网络爬虫框架、HTML/XML解析及相关规范、文本处理相关的库、处理特编辑特殊字符格式的库、自然语言处理库、浏览器自动化与仿真、多进程并发、异步网络编程库、队列、云计算、电子邮件处理库、URL和网络地址操作相关的库、网页内容提取相关的库、用于Web Socket的库、DNS解析、计算机视觉相关的库、代理服务器以及其他杂项。

- Python Web：**[Full Stack：Python全栈导航](https://www.fullstackpython.com/)** ：**被诸多参考源推荐**，提供中文译本，Matt Makai 整理创建的有关如何创建、部署并且运行生产级Python web应用的一切知识 。中文版由 [开源爱好者们](https://github.com/haiiiiiyun/fullstackpython.cn/graphs/contributors) 共同翻译 。[英文版](https://www.fullstackpython.com/) | [中文版](http://fullstackpython.atjiang.com/)
- 网络安全和破解：**[Python军火库 - t00ls.net](https://www.t00ls.net/static/html/pytools.html)** ：中文。有关网络安全的Python资源，**推荐专业人员使用**。其内容包括：漏洞及渗透练习平台、扫描器、信息搜集工具、WEB、windows域渗透工具、Fuzz、漏洞利用及攻击框架、漏洞POC&EXP、中间人攻击及钓鱼、密码破解、二进制及代码分析工具、二进制静态分析工具、EXP编写框架及工具、隐写、各类安全资料、各类CTF资源、甲方安全工程师生存指南、蜜罐、远控以及各类编程资源。
- 科学计算：**[pythonidae](https://github.com/svaksha/pythonidae)** ：英文，GitHub上由[svaksha](https://github.com/svaksha) 发起的有关Python科学编程以及数学和统计计算的资源集合，此处列出的一些资源也可能在其代码库中使用Go，Java，Julia，R语言等其他语言。提供优化阅读的[另一版本Pythonidae](http://svaksha.github.io/pythonidae/)。
- Python项目大集合：**[Python Github Projects](http://itgeekworkhard.com/python-github-projects/)** : GitHub上的Python项目集合。**英文**，收集了GitHub上的Python热门开放项目，并按照项目的用途进行分类，推荐在新建项目时参考使用，目前已停止列表的维护。项目源代码参见：[checkcheckzz/python-github-projects](https://github.com/checkcheckzz/python-github-projects) 

## 3. 学习Python语言

通过以下的资源来学习Python语言，除纸质图书及无特殊说明外，以下资源均可免费获取。

整合资源列表中提供了在网络中已有人整合的较为完整的学习资源，其他的条目皆为本项目根据所获取的全部参考源后对学习资源的筛选整理，有关在本项目中怎样选取学习资源，请参见 ：[资源评价](./help.md#怎样选取学习资源？) 

### 3.1 整合资源列表

针对Python学习整理好的学习资源的网站列表，通常已针对初学者和熟练者作区分，资源内容包括图书、网站和视频等，除特殊说明外均可免费获取。

> 注：该栏目内容与下两节内容有重复部分，如果您准备学习python，从中选取一个即可，建议使用有`推荐`标记的资源。有关该项目如何确定推荐资源，请参见：[资源评价](./help.md#是怎么对参考源进行评价的？) 

**[Documentation(Python 文档)](https://www.python.org/doc/)**：英文，推荐**英文好的用户**使用。一门编程语言的官方文档永远是最好的学习资源。Python的官方标准文档，教程和指南，涵盖Python语言的 标准用法，可以免费下载和在线浏览。提供针对初学者、中等和高级的教程；提供其3.x版本和2.x版本的标准文档。

**[Full Stack：Python全栈导航](https://www.fullstackpython.com/)** ：**被诸多参考源推荐**，提供中文译本，Matt Makai 整理创建的有关如何创建、部署并且运行生产级Python web应用的一切知识 。中文版由 [开源爱好者们](https://github.com/haiiiiiyun/fullstackpython.cn/graphs/contributors) 共同翻译 。[英文版](https://www.fullstackpython.com/) | [中文版](http://fullstackpython.atjiang.com/) 

- **最佳Python资源**：最佳的常用 Python 资源，并附有其提供给读者的相关资源描述。 包括初学者、特定行业、有经验的开发者初学 Python、视频、屏幕录像和演示文稿、精选的 Python 包、播客以及时讯等方面的资源。[英文版](https://www.fullstackpython.com/best-python-resources.html) | [中文版](http://fullstackpython.atjiang.com/best-python-resources.html) 
- **最佳Python视频汇总：**注**：视频资源本身为英文。最好的免费视频链接，以及其它一些视频列表，这些视频都是在过去几年的讨论会和见面会上发布的 。[英文版](https://www.fullstackpython.com/best-python-videos.html) |[中文版](http://fullstackpython.atjiang.com/best-python-videos.html) 

**[知乎上的Python话题的问答](https://www.zhihu.com/topic/19552832/index)** : **中文，推荐。**国内社会化问答网站，其Python话题下整合了知乎上包括python相关的讨论、精华以及待回答问题。提供优质内容的索引，包括：Python 入门 、Python 进阶 、Python 玩具 、比较·反思·战争 、Python Web开发 、网络爬虫/数据采集 。并提供父子话题结构。

**[极客学院中的 Python wiki列表](http://wiki.jikexueyuan.com/list/python/)：中文**，**推荐**。该网站可能访问不稳定。IT技术图文教程库，全部免费 、离线下载 、教程全面 、排版优美 、通俗易学。

**[Python中文文档项目](https://wiki.woodpecker.org.cn/moin/PythonZhDoc)**  ：包括Python的教学类中文图书及翻译图书（分初中高级），开发包/API类手册等。还包括Python精读书目及文章，但其主要针对Python 2.x版本。

**[Pythonidae提供的资源列表](https://github.com/svaksha/pythonidae/blob/master/Resources.md)**：英文，项目中关于Python资源的文档，提供免费和付费区分的资源，内容包括：可供提问解答的网站、书籍、针对Python新手科学家的资源和指南 、博客、备忘单 、会议、一般资源、新闻、组织、工具、视频、研讨会教程等。

**[W3CSchool提供的Python教程](https://www.w3cschool.cn/python/)** ：中文，提供初高级Python教程以及[Wiki列表](https://www.w3cschool.cn/python/list/) 和[python问答讨论区](https://www.w3cschool.cn/python/topic) 。Wiki列表提供python速查词典、IDE和编程训练。

**[GitHub项目List of free programming books中的python书籍](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books-zh.md#python)**：中文，免费，**推荐**。整理了中文版免费的编程书籍列表。

### 3.2 初学者

针对初学者的系统教程：

- [Python教程- 廖雪峰的官方网站](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000) ：网上最流行的，小白的*Python*新手*教程*，具有如下特点：. 中文，免费，零起点，完整示例，基于最新的*Python* 3版本。  

- [Python3 教程| 菜鸟教程](http://www.runoob.com/python3/python3-tutorial.html) ：[菜鸟教程](https://www.runoob.com/)提供了最全的基础编程技术教程，所有资源是完全免费的，并且会根据当前互联网的变化实时更新内容。这套Python3教程适合想从零开始学习Python编程语言的开发人员 。本站包括了HTML、CSS、Javascript、PHP、C、Python等各种基础编程教程。同时本站中也提供了大量的在线实例，通过实例，您可以更好地学习如何建站。

- [Crossin的编程教室](http://crossincode.com/home/) ：由知乎用户[Crossin](https://www.zhihu.com/people/crossin) 创建， 整理了零基础python入门教程系列，并提供在线写代码、签到打卡、实战项目等。

  ##### 推荐书籍：

- [简明Python教程 a byte of python](https://legacy.gitbook.com/book/lenkimo/byte-of-python-chinese-edition/details)：被推荐最多的入门书籍之一。旨在于介绍如何使用 Python 语言进行编程。它以教材与指南的形式为入门者介绍 Python 语言。如果你对电脑知识的了解仅限于如何保存文本文件的话，那这本书就是为你准备的。 

- 《与孩子一起学编程》：一本老少咸宜的编程入门奇书！一册在手，你完全可以带着自己的孩子，跟随Sande父子组合在轻松的氛围中熟悉那些编程概念，如内存、循环、输入和输出、数据结构和图形用户界面等。这些知识一点儿也不高深，听起来备感亲切，书中言语幽默风趣而不失真义，让学习过程充满乐趣。细心的作者还配上了孩子们都喜欢的可爱漫画和经过运行测试的程序示例，教你用最易编写和最易理解的Python语言，写出你梦想中的游戏程序。 [获取纸质版](https://book.douban.com/subject/5338024/)

- 《Head First Python 中文版》：超越枯燥的语法和甩法手册，通过一种独特的方法教你学习这种语言。你会迅速掌握Python的基础知识，然后转向持久存储、异常处理、Web开发、SQLite、数据加工和lGoogle App Engine。你还将学习如何为Android编写移动应用，这都要归功于Python为你赋予的强大能力。本书会提供充分并且完备的学习体验，帮助你成为一名真正的Python程序员。 作者巴里觉得你的时间相当宝贵，不应当过多地花费在与新概念的纠缠之中。通过应用认知科学和学习理论的最新研究成果，《Head First Python(中文版)》可以让你投入一个需要多感官参与的学习体验，这本书采用丰富直观的形式使你的大脑真正开动起来，而不是长篇累牍地说教，让你昏昏欲睡。 [获取纸质版](https://book.douban.com/subject/10561367/) 

- [笨办法学Python](https://legacy.gitbook.com/book/wizardforcel/lpthw/details)  ：这本书指导你在Python中通过练习和记忆等技巧慢慢建设和建立技能,然后应用它们解决越来越困难的问题。在这本书的最后，你需要拥有必要的工具开始进行更多复杂程序的学习。我喜欢告诉大家，我的书带给你们“编程黑带”。意思是说你知道的基础知识足够现在就开始学习编程。 

- [Python核心编程](

- [深入理解Python](

- [Python标准库]

- [Python编程指南]

- [django_book](https://djangobook.com/the-django-book/) ：[Django Book 2.0 中文版· GitBook](https://www.gitbook.com/book/wizardforcel/django-book-20-zh-cn)

- [django-web-app-book中文](https://github.com/wwq0327/django-web-app-book) - Django Web 开发实战,本书是一本在线的免费的Django Web编程书籍 

### 3.3 进阶

- [Dive Into Python3 中文版](https://dipyzh.bitbucket.io/ )：*Dive Into Python* 是为有经验的程序员编写的一本 Python 书 
- [Django book 2.0](http://djangobook.py3k.cn/2.0/) 

- [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html) ：英文。开源应用程序的体系结构 ，共有四本书
  - 500 Lines or Less：包含了22个由该领域的专家完成，用不到500行的代码实现一个特定功能的子项目。 
  - The Performance of Open Source Applications
  - The Architecture of Open Source Applications Ⅰ
  - The Architecture of Open Source Applications Ⅱ
- [Python Cookbook第三版](http://python3-cookbook.readthedocs.io/zh_CN/latest/) (作者：David Beazley, Brian K.Jones 翻译：熊能)
- [Think Python](http://greenteapress.com/wp/think-python-2e/) : [How to Think Like a Computer Scientist](http://greenteapress.com/thinkpython2/thinkpython2.pdf) by Allen Downey, 2nd Edition, Version 2.2.18. Example programs and solutions to some exercises are in this [GitHub repository](https://github.com/AllenDowney/ThinkPython2/tree/master/code).
- [像计算机科学家一样思考Python](https://www.ctolib.com/docs/sfile/think-python-2e/0.html) (中英对照版 作者：Allen B. Downey 翻译：大胖哥)
- [PySourceCode](https://wiki.woodpecker.org.cn/moin/PySourceCode) -- 《Python源码剖析》从Python源码中来，到Python应用中去 
- [Python之旅](http://funhacks.net/explore-python) (作者：Ethan)

### 3.4 常用资源列表

包括论坛、新闻、订阅、社交媒体等。

## 4. Python的应用与实战

- [Applications for Python (Python 的应用)](https://www.python.org/about/apps/) ：英文，官方介绍Python在网络开发、科学计算、教育、软件开发、商业应用等领域的应用和相关软件包，以及其桌面GUI 软件包。
- [A "Best of the Best Practices" (BOBP) guide to developing in Python.](https://gist.github.com/sloria/7001839) ：Python 最佳实践。 
- 网络爬虫：**[awesome-web-scraping](https://link.juejin.im/?target=http%3A%2F%2Flink.zhihu.com%2F%3Ftarget%3Dhttps%253A%2F%2Fgithub.com%2Florien%2Fawesome-web-scraping%2Fblob%2Fmaster%2Fpython.md)**：**英文，推荐**。**爬虫工具集合**，由[lorien](https://github.com/lorien)整理包含Python网页抓取和数据处理相关的库。 原网页为英文版，中文版参见： [SDK.cn技术文章](https://sdk.cn/news/8050) 。主要内容包括：网络相关的通用库以及异步的相关资源、网络爬虫框架、HTML/XML解析及相关规范、文本处理相关的库、处理特编辑特殊字符格式的库、自然语言处理库、浏览器自动化与仿真、多进程并发、异步网络编程库、队列、云计算、电子邮件处理库、URL和网络地址操作相关的库、网页内容提取相关的库、用于Web Socket的库、DNS解析、计算机视觉相关的库、代理服务器以及其他杂项。
- Python Web：**[Full Stack：Python全栈导航](https://www.fullstackpython.com/)** ：**被诸多参考源推荐**，提供中文译本，Matt Makai 整理创建的有关如何创建、部署并且运行生产级Python web应用的一切知识 。中文版由 [开源爱好者们](https://github.com/haiiiiiyun/fullstackpython.cn/graphs/contributors) 共同翻译 。[英文版](https://www.fullstackpython.com/) | [中文版](http://fullstackpython.atjiang.com/)
- 网络安全和破解：**[Python军火库 - t00ls.net](https://www.t00ls.net/static/html/pytools.html)** ：中文。有关网络安全的Python资源，**推荐专业人员使用**。其内容包括：漏洞及渗透练习平台、扫描器、信息搜集工具、WEB、windows域渗透工具、Fuzz、漏洞利用及攻击框架、漏洞POC&EXP、中间人攻击及钓鱼、密码破解、二进制及代码分析工具、二进制静态分析工具、EXP编写框架及工具、隐写、各类安全资料、各类CTF资源、甲方安全工程师生存指南、蜜罐、远控以及各类编程资源。
- 科学计算：**[pythonidae](https://github.com/svaksha/pythonidae)** ：英文，GitHub上由[svaksha](https://github.com/svaksha) 发起的有关Python科学编程以及数学和统计计算的资源集合，此处列出的一些资源也可能在其代码库中使用Go，Java，Julia，R语言等其他语言。提供优化阅读的[另一版本Pythonidae](http://svaksha.github.io/pythonidae/)。
- Python项目大集合：
  - **[Python Github Projects](http://itgeekworkhard.com/python-github-projects/)** : GitHub上的Python项目集合。**英文**，收集了GitHub上的Python热门开放项目，并按照项目的用途进行分类，推荐在新建项目时参考使用，目前已停止列表的维护。项目源代码参见：[checkcheckzz/python-github-projects](https://github.com/checkcheckzz/python-github-projects) 
  - **[实验楼上的Python实战项目课程](https://www.shiyanlou.com/courses/?category=all&course_type=all&fee=all&tag=Python&unfold=0)** ：中文，包含收费内容。实验楼是一家专注于IT技术的在线实训平台，采用创新的“在线实验”学习模式，为学生及在职程序员提供编程、运维、测试、云计算、大数据、数据库等当前主流IT技术实践课程 。
  - **[show-me-the-codePython 练习册](https://github.com/Yixiaohan/show-me-the-code)** ：中文，GitHub用户[Yixiaohan](https://github.com/Yixiaohan)创建。每天用写一个小程序。内容包括题目和答案。 

# 5. Python求职 

## 5. Python求职

**[Reddit上的Python板块](https://www.reddit.com/r/Python/)**：**英文。**Reddit社区上关于Python的讨论，其中包含问答和职业招聘信息。Reddit是一个娱乐、社交及新闻网站，注册用户可以将文字或链接在网站上发布，使它基本上成为了一个电子布告栏系统，目前是美国人气最高的新闻社区。 

**[PythonTab论坛](http://bbs.pythontab.com/) ：推荐，十分活跃**。包括Python技术交流和技术资源两类，[技术交流](http://bbs.pythontab.com/forum.php?gid=1) 包括问答、代码分享和机器学习；[技术资源](http://bbs.pythontab.com/forum.php?gid=6) 包括求职招聘、进阶提升、SQL数据库、杂谈、其他web技术和Python视频教程。

**[python4cn招聘](http://simple-is-better.com/jobs/)**：提供整合的全国python 招聘的职位，支持搜索。

**[indeed 上的Python招聘](https://cn.indeed.com/%E5%B7%A5%E4%BD%9C-Python)** ：Indeed上的全国Python招聘职位，支持搜索和高级检索。

**[Python招聘-招聘求职信息-拉勾网](https://www.lagou.com/zhaopin/Python/)** ：拉勾网是互联网领域垂直招聘*网站*，提供*Python*招聘信息，支持搜索和高级筛选。

## 6. 其他待归类资源
