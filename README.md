
<!-- TOC -->

- [Bootstrap-移动优先|全球最流行的响应式前端设计框架！](#bootstrap-移动优先全球最流行的响应式前端设计框架)
- [更新信息](#更新信息)
    - [状态标识](#状态标识)
- [维护团队](#维护团队)
- [图标与webfont引用](#图标与webfont引用)
- [发行说明](#发行说明)
- [匠者用心临砥上流-Bootstrap v4 前端架构翻译手记(基于bootstrapv4.0最新的中文简体手册)](#匠者用心临砥上流-bootstrap-v4-前端架构翻译手记基于bootstrapv40最新的中文简体手册)
- [匠者用心临砥上流-Bootstrap v4 前端架构翻译手记](#匠者用心临砥上流-bootstrap-v4-前端架构翻译手记)

<!-- /TOC -->




# Bootstrap-移动优先|全球最流行的响应式前端设计框架！




<p align="center">
  <a href="http://code.z01.com/v4">
    <img src="http://code.z01.com/v4/assets/img/bootstrap-stack.png" width="300">
  </a>
  <p><a href="http://code.z01.com/v4">点此进入Bootstrap 4中文站</a></p>
</p>
<br>




# 更新信息


## 状态标识

[![Slack](https://bootstrap-slack.herokuapp.com/badge.svg)](https://bootstrap-slack.herokuapp.com/)
[![Build Status](https://github.com/twbs/bootstrap/workflows/Tests/badge.svg)](https://github.com/twbs/bootstrap/actions?workflow=Tests)
[![npm version](https://img.shields.io/npm/v/bootstrap.svg)](https://www.npmjs.com/package/bootstrap)
[![Gem version](https://img.shields.io/gem/v/bootstrap.svg)](https://rubygems.org/gems/bootstrap)
[![Meteor Atmosphere](https://img.shields.io/badge/meteor-twbs%3Abootstrap-blue.svg)](https://atmospherejs.com/twbs/bootstrap)
[![Packagist Prerelease](https://img.shields.io/packagist/vpre/twbs/bootstrap.svg)](https://packagist.org/packages/twbs/bootstrap)
[![NuGet](https://img.shields.io/nuget/vpre/bootstrap.svg)](https://www.nuget.org/packages/bootstrap/absoluteLatest)
[![peerDependencies Status](https://img.shields.io/david/peer/twbs/bootstrap.svg)](https://david-dm.org/twbs/bootstrap?type=peer)
[![devDependency Status](https://img.shields.io/david/dev/twbs/bootstrap.svg)](https://david-dm.org/twbs/bootstrap?type=dev)
[![Coverage Status](https://img.shields.io/coveralls/github/twbs/bootstrap/master.svg)](https://coveralls.io/github/twbs/bootstrap?branch=master)
[![CSS gzip size](https://img.badgesize.io/twbs/bootstrap/master/dist/css/bootstrap.min.css?compression=gzip&label=CSS+gzip+size)](https://github.com/twbs/bootstrap/tree/master/dist/css/bootstrap.min.css)
[![JS gzip size](https://img.badgesize.io/twbs/bootstrap/master/dist/js/bootstrap.min.js?compression=gzip&label=JS+gzip+size)](https://github.com/twbs/bootstrap/tree/master/dist/js/bootstrap.min.js)
[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)](https://www.browserstack.com/automate/public-build/SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)
[![Backers on Open Collective](https://img.shields.io/opencollective/backers/bootstrap.svg)](#backers)
[![Sponsors on Open Collective](https://img.shields.io/opencollective/sponsors/bootstrap.svg)](#sponsors)


本文档在线浏览地址：
1. [http://code.z01.com/](http://code.z01.com/ "http://code.z01.com/")
2. [http://github.z01.com/bootstrap4-zhcn-documentation/](http://github.z01.com/bootstrap4-zhcn-documentation/ "http://github.z01.com/bootstrap4-zhcn-documentation/")


中文镜像历史版本：
1. v4.0版     发布时间：2018-2-10  文档地址：[http://code.z01.com/4.0/index.html](http://code.z01.com/4.0/index.html "http://code.z01.com/4.0/index.html")
2. v4.1.1.版  发布日期：2018-6-11  文档地址：[http://code.z01.com/v4/](http://code.z01.com/v4/ "http://code.z01.com/v4/")
3. v4.2.1.版  发布日期：2019-1-25  文档地址：[http://code.z01.com/v4/](http://code.z01.com/v4/ "http://code.z01.com/v4/")
4. v4.4.1.版  发布日期：2020-2-20  文档地址：[http://code.z01.com/v4/](http://code.z01.com/v4/ "http://code.z01.com/v4/")
4. v4.5.0.版  发布日期：2020-5-18  文档地址：[http://code.z01.com/v4/](http://code.z01.com/v4/ "http://code.z01.com/v4/")
>更新提示：v4.4.1增加row-cols、.container-sm|md|lg|xl等属性、可以更好的支持移动配置，欢迎大家欣赏，新增栅格部份可见 http://code.z01.com/v4/layout/overview.html 及 http://code.z01.com/v4/layout/grid.html#row-columns





# 维护团队
由Zoomla!逐浪CMS团队维护
我们是一个有着16年历史的本土web开发团队和企业级CMS研发组织，官网[www.z01.com](http://www.z01.com "www.z01.com")



QQ交流群号：
[![加入QQ群](https://img.shields.io/badge/一群-541450128-blue.svg?style=for-the-badge&logo=appveyor)](https://jq.qq.com/?_wv=1027&k=5qIayyX)  [![加入QQ群](https://img.shields.io/badge/二群-541450128-blue.svg?style=for-the-badge&logo=appveyor)](https://jq.qq.com/?_wv=1027&k=5Ephzpq)   [![加入QQ群](https://img.shields.io/badge/三群-601781959-blue.svg?style=for-the-badge&logo=appveyor)](https://jq.qq.com/?_wv=1027&k=50a28BK) 


官方QQ客服：
[![官方QQ客服1](https://img.shields.io/badge/官方QQ客服1-524979923-red.svg?style=for-the-badge&logo=appveyor)](http://wpa.qq.com/msgrd?v=3&uin=745151353&site=qq&menu=yes)  [![官方QQ客服2](https://img.shields.io/badge/官方QQ客服2-1799661890-red.svg?style=for-the-badge&logo=appveyor)](http://wpa.qq.com/msgrd?v=3&uin=1799661890&site=qq&menu=yes) 



# 图标与webfont引用
基于zico（一个专为中国开发者而生的跨平台图标解决方案)，官网[ico.z01.com](http://ico.z01.com "ico.z01.com").
基于zico技术可以快速渲染webfont或svg矢量图标，并提供免费的网页字体技术。

# 发行说明
这是2018年春节翻译第一版时的文字记录（翻译工作前提有2个月，工作量很大），以飨读者。


# 匠者用心临砥上流-Bootstrap v4 前端架构翻译手记(基于bootstrapv4.0最新的中文简体手册)


#匠者用心临砥上流-Bootstrap v4 前端架构翻译手记

做Web开发和移动开发的人，很少有人不知道Bootstrap前端架构。

作为当今世界上最优秀的前端架构，从Twitter内部项目孵化出来，并以开源、专注维护更新、易于使用、只关注最核心、移动优化先等机制，获得了国际上众多团队的交赞。

即使是国内BAT等 一线企业的很多项目也以Bootstrap为核心进行开发，甚至有多个前端规范是在Boostrap基础上进行“改装”，可见影响力之大。




逐浪CMS从Bootstrap2.0将其开始引入中国，莆一面世，在多个移动项目上即取得了卓越的成效，赢得各个业界平台纷纷仿效，并在生产力领域取得广泛的应用。




由于中国互联网的管制，访问海外网站总是有各种困难，迅速的，逐浪CMS团队即投入到了Bootstrap中文镜象站的工作，并建立了Bootstrap中文站点：http://code.z01.com 




其后，我们为其提供了SSL服务，可以通过https://code.z01.com 进行访问，获得Bootstrap包。




随着全新的Bootstrap v4版本的研发完善工作进入尾声，我们紧跟官方步伐，提供了全新的V4使用手册和中文镜像，同时保留旧版的镜像。




Bootstrap V3 中文镜像：http://code.z01.com/boot 

Bootstrap V4中文镜像：http://code.z01.com/v4 

注：均提供SSL访问、使用手册、最新程序包下载。




以下为本次翻译的几个原则：

1、基于汉语和中文简体语惯来翻译，比如港台地区的“预设”，一般在本案中，表达为“默认值”。

2、有借鉴樊潇洁老师部份内容，其译本是相当早期的一个版本，借鉴同时进行了大胆的改进。

3、力求信、雅、达，并做了一些相应知识的链接，比如SVG图片、HTMl5规范等，其中诸如grid在翻译中，我们采用中文业界广泛认同的“栅格”来表达。

4、主题模板：官方只有三个主题模板，而且是基于bootstrap 3的，所以我们在此不进行释译或引用。我们提供了一组中文环境下范例，即：http://code.z01.com/v4/themes/ 

5、原汁原味的体现官方站点风格。

6、Bootstrap官方站点在V4发布以来，其搜索采用了algolia的搜索服务，我们在中文镜像中，也做了同样的设置。

7、充份考虑中文环境，一些版面为中国用户而优化。





2017年国庆，去了一趟西藏拉萨，这是继几年前林芝项目之后的又一次西行，特地从成都坐火车西行，路过青海，抵达拉萨，还有羊湖、冬宫、珠峰大本营、大小昭寺、文成公主表演，无不让人思考人生之真谛，时时于世界之高体会人间万物，可你能为世界做些什么。

然后就着手这个翻译了。

整个翻译工作于2017年10月8日完成，凌凌总总的做了一些优化。

提交上去没几天，官方老大modo就接受了提交。

感慨海外开源社区火爆！


**********************************************************
2018年2月9日，更新Bootstrap v4正式版手册，在逐字斟酌官方手册后，进行了更新。

主要更新包括：

1、官方实例和修正的样式。

2、一些前版翻译不足处。

3、官方实例包括Expo模板都重新设计优化，同样保存了Zoomla!逐浪CMS官方团队的一些实例。


未来我们还将不断的维护，提供更多的更新，比如flexbox布局补充引导等。

**********************************************************
2018年6月，更新为Bootstrap 4.1

2019年1月，更新为Bootstrap 4.2.1

2019年4月，更新为Bootstrap 4.3.1

2020年4月，更新文档和使用指引。

 ## Web不死，Zoomla!逐浪CMS筑力中国web开发进程
 ### Zoomla!逐浪CMS团队卓越出品
**CMS+AI智能+字库+图库全栈生态-->做中国最优秀的全栈门户服务商**

Zoomla!逐浪CMS：中文业界alexa排名第一的CMS系统|专注.net与windows平台企业级研发，集成内容管理、webfont、商城、店铺、黄页、教育、考试、3D、三维全景、混合现实、CRM、ERP、OA、论坛、贴吧等为一体，打造国内高端的CMS产品典范。

官网：http://www.z01.com

免费下载：http://www.z01.com/mb

视频教程：http://www.z01.com/mtv

模板资源：http://www.z01.com/mb

zico中文图标库：http://ico.z01.com

Uni全球字码表：http://www.ziti163.com/uni

webfont： http://www.ziti163.com/webfont

字典： http://zd.ziti163.com

在线智写做字库： http://v.ziti163.com

方言语音项目： http://a.ziti163.com

智图： http://p.ziti163.com

