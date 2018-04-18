# Python_Learning
自学Python资料整理

## 自学
1. [Python资源大全中文版，包括：Web框架、网络爬虫、模板引擎、数据库、数据可视化、图片处理等，由伯乐在线持续更新。](https://github.com/jobbole/awesome-python-cn)
2. [Python的基础练习代码与各种爬虫代码](https://github.com/rieuse/learnPython)
3. [Python爬虫学习手册](https://www.jianshu.com/p/047b4dd3f911?from=singlemessage)
4. [Python系列 - 收藏集 - 掘金](https://www.jianshu.com/p/9554bcf6ba44)
5. [廖雪峰Python教程](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)

### 开发工具
1. Pycharm(小白上手学习用)——用Pycharm写相应脚本和程序包的开发（功能齐全，速度慢）
2. 包管理必备：Anaconda <https://anaconda.org>
>真的要强烈推荐 Anaconda ，它能帮你安装好许多麻烦的东西，包括： Python 环境、pip 包管理工具、常用的库、配置好环境路径等等。这些事情小白自己一个个去做的话，容易遇到各种问题，带来挫败感。如果你想用 Python 搞数据方面的事情，就安装它就好了，它甚至开发了一套 JIT 的解释器 Numba。所以 Anaconda 有了 JIT 之后，对线上科学计算效率要求比较高的东西也可以搞了。
3. 前端在线编辑器：CodeSandbox
>不用安装 npm 的几千个包了，它已经在云端完成了，采让你直接就可以上手写代码、看效果。对于 React、Vue 这些主流前端框架都支持。


### 常用库
#### 标准库
* requests、urllib、urllib2、re
* https://blog.csdn.net/nuli888/article/details/51960217
* https://blog.csdn.net/qiqll/article/details/39339319
* https://www.cnblogs.com/sunshine-1/p/7372906.html

#### 数据分析
* 前期：Numpy & Scipy、Pandas、matplotlib 是 Python 最基本数据分析的三驾马车，而 Jupyter notebook 则是分析的最基本交互式环境。
* 后期：可以学习更为强大的工具，如分布式计算 pyspark，机器学习，深度学习，神经网络等等，Python 都能找到成熟的包以供使用。

#### 网络数据采集
* 前期：数据分析离不开数据采集，所以我偶尔也会使用 Python 的标准库 urllib 去网络采集一些简单数据，图快也会使用 requests，beautifulsoup 是非常不错的 html 解析工具。
* 后期：学习 Python 爬虫框架 pyspider，scrapy 等，以及分布式爬虫。

#### 网站开发
* 主要使用 django 作为开发框架。

## 爬虫项目
### Scrapy爬虫框架
1. [官网](https://doc.scrapy.org/)
2. [中文文档](http://scrapy-chs.readthedocs.io/zh_CN/0.24/)
3. [入门](http://python.jobbole.com/81332/)
4. [网友整理的学习路径（10步）](https://blog.csdn.net/sunnyxiaohu/article/details/50787430)

### 正则表达式
![正则表达式](https://img-blog.csdn.net/20130515113723855)

### github练手小项目
1. [Python3网络爬虫实战：VIP视频破解助手；GEETEST验证码破解；小说、动漫下载；手机APP爬取；财务报表入库；火车票抢票；抖音APP视频下载；百万英雄辅助；网易云音乐批量下载](https://github.com/Jack-Cherish/python-spider)
2. [爬取豆瓣电影排名前100](https://github.com/Andrew-liu/dou_ban_spider)

#### 微博爬虫
* 初级
[新浪微博爬虫，用python爬取新浪微博数据](https://github.com/dataabc/weiboSpider)
* 高级 https://github.com/SpiderClub/weibospider

在线Python代码编译器：https://c.runoob.com/compile/

#### 数据库录入
* https://blog.csdn.net/Mr_blueD/article/details/79343349

#### 多页爬虫
* https://blog.csdn.net/zhfcmx1/article/details/71108621——单页
* https://blog.csdn.net/zhfcmx1/article/details/71598091——多页
#### docker部署爬虫
* [使用Docker部署Scrapy爬虫](https://blog.csdn.net/wang_san_shi/article/details/48178689)

#### 机器学习——TensorFlow
* [TensorFlow中文社区——有示例和数据可以模仿](http://www.tensorfly.cn/tfdoc/get_started/introduction.html)


#### 练手网站
* http://www.xunsee.com
* http://weather.sina.com.cn

## 数据分析
* [小 200 行 Python 代码做了一个换脸程序](http://python.jobbole.com/82546/)

## 笔记
#### yield
[如何理解yield含义](https://www.ibm.com/developerworks/cn/opensource/os-cn-python-yield/)

[generator对象 （可迭代对象）](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/0014317799226173f45ce40636141b6abc8424e12b5fb27000)

[iterable 对象（可迭代对象）](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/00143178254193589df9c612d2449618ea460e7a672a366000)

#### 数据分析
* [利用python进行数据分析（一）：环境搭建及准备工作](https://zhuanlan.zhihu.com/p/23650793)
* [利用python进行数据分析（二）：一些范例数据集](https://zhuanlan.zhihu.com/p/2365)
* [利用python进行数据分析（三）：一种交互式计算和开发环境IPython](https://zhuanlan.zhihu.com/p/23834454)
* [Python+pandas+matplotlib数据分析与可视化案例（附源码）](https://blog.csdn.net/oh5w6hinug43jvrhhb/article/details/78796069)
* [用python玩点有趣的数据分析——一元线性回归分析实例](https://www.cnblogs.com/jiayongji/p/7119028.html?utm_source=itdadao&utm_medium=referral)
[20大Python机器学习开源项目](https://python.freelycode.com/contribution/detail/536)
[今年(2016)GitHub排名前20的Python机器学习开源项目](http://www.sohu.com/a/120011660_465975)

#### 长连接——其实是前端去控制的，后端主要提供web服务器，主要要考虑的是并发问题
* [如何实现单服务器300万个长连接的？](https://www.zhihu.com/question/20831000)
* [python socket 编程之三：长连接、短连接以及心跳](http://www.cnblogs.com/xilouch/p/4618903.html)
* 网上评论：一般来说python就tornado和gevent两个选择, 我个人觉得gevent写起来更舒服

## 调试
https://www.jianshu.com/p/5559e60d26c8?utm_campaign=maleskine&utm_content=note&utm_medium=pc_all_hots&utm_source=recommendation

