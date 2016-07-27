# 《Node.js微信开发》


大家好，我是桑世龙，github和cnodejs上的i5ting，目前在天津创业，空弦科技cto，公司目前使用技术主要是Node.js，Moajs作者，
技术栈算所谓的MEAN（mongodb  + express + angular + node），所有代码都部署在阿里云上

曾在新浪，网秦等工作过

算全栈程序员吧，java、php、perl、ruby，bi、云计算、ios、android、h5都做过，带过前端、后端、数据分析、移动端负责人、做过首席架构师、技术总监

哈哈

我的名字i5ting，原因是我媳妇叫张婷，哈哈

闲言少叙，下面开始正题


## 为什么前端越来越难？越来越有意思？


### 大前端

从架构上讲，软件从c/s到b/s过度，它的桥梁是浏览器，尤其是ajax促进了web2.0的成功，所以现在我们看到的绝大部分软件的架构都是b/s的，也称为瘦客户端。

![](https://github.com/i5ting/the-missing-frontend/raw/master/docs/p1.png)

从prototype.js到yui，到jquery，到extjs等他们只是从用法和ui上演进，还有就是underscore等工具库。

而backbone的出现，把mvc引入前端，于是前端开始了分层。

当angular.js横空出世，又引入了双向绑定，ioc依赖注入，指令等概念，这实际上在java里早有的概念，这又再一次增加了前端的复杂度。

上面说的是架构上得演进，还有一些enhance的提高，比如js方面有coffeescript和typescript，css方面有less/sass/scss/stylus等，这些不是什么新概念，是对web开发的增强。前提是你熟练使用js和css才能用。

最后是MEAN的full stack最新趋势。有望替换LAMP.

这些还只是前端的发展，现在是移动互联网时代，在微信淘宝等带领下，h5正如火如荼的袭来，可以说是当下最火的技术。那么移动端h5开发和上面的前端技术如何结合就成了现下得趋势。

我觉得大前端应该现下web的统称，包含web开发最佳实践，趋势以及h5。
nodejs作为一个兼容js语法的平台，更容易让广大前端开发者接受，在构建，工具等领域辅助大前端的成长。

### 如何学习

我们来想想一般的前端有什么技能？

- html
- css（兼容浏览器）
- js会点（可能更多的是会点jquery）
- ps切图
- firebug和chrome debuger会的人都不太多
- 用过几个框架，大部分人是仅仅会用
- 英语一般
- svn/git会一点

那么他们如果想在前端领域做的更深有哪些难点呢？

- 基础：oo，dp，命令，shell，构建等
- 编程思想上的理解（mvc、ioc，规约等）
- 区分概念
- 外围验收，如h5和hybird等
- 追赶趋势，如何学习新东西


以上皆是痛点。

现在来总结一下学习有2种，1是从头来，2是从某一种框架起

第一种学习下来，没个几年很难学通，第二种只会用框架，补齐概念和基础也比较费劲。总之，无论如何学习曲线都是比较陡峭的，那么如何来让入门的开发者快速学习到这些呢？

软件的精髓在应变，殊途同归，学会如何学习才是我们最重要的道。

- 积极的心态，做好适应变化的准备
- 找到属于自己的学习方式
- 如果有机会，改变或创新，贡献开源社区


## 课程目录

0. 第0节：Nodejs入门 (14/14)
1. 第1节：Express和微信开发入门 (6/6)
2. 第2节：微信实例和h5实践 (4/4)
3. 第3节：WeUI实战 (7/7)
4. 第4节：微信支付
5. 第5节：实战付费课程系统

我们花了很多精力把基础知识和单一技能点

- 基本技能（coding ide，git，命令行等）
- nodejs基础
- express
- 微信基础（后台）
- 微信分享
- h5和weui实践
- 微信支付

这些都太零散了，为了能够让大家有一个整体的项目认知，这里面我们再加一个项目实践

《rework》一书里讲，抓自己的痒，是说创业的时候选题，从自身的痛点出发，这样更容易成功

那么，我们（StuQ）的这个课程，如果想要推广，想让更多人参与，怎么办呢？

既然讲的是这课，那我们就写一个吧