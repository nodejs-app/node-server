README
===========================
node-demo

****
###　Author:Alex Dong

### 来了就留个 :feet:吧，star一下证明你来过  :stuck_out_tongue_closed_eyes:

>  如果对您对此项目有兴趣，可以点 "Star" 支持一下 谢谢！ ^_^

>  或者您可以 "follow" 一下，我会不断开源更多的有趣的项目

>  如有问题请直接在 Issues 中提，或者您发现问题并有非常好的解决方案，欢迎 PR 👍

>  传送门1：[优雅的vue2 + element-ui + axios后台管理系统](https://github.com/Alex-0407/vue2-admin-grace)

>  传送门2：[angulat4后台管理系统](https://github.com/Alex-0407/ng4-grace)



===========================

### Installation & Development

1. clone this repo: `git clone https://github.com/Alex-0407/node-express-start.git` or download
2. `cd node-express-start`
3. run `node express_demo4.js` from a terminal
4. open `http://localhost:8081/upload.html` in the browser


### 项目地址：
https://github.com/Alex-0407/node-express-start

#### Node.js 学习资源

* [Node.js 菜鸟教程](http://www.runoob.com/nodejs/nodejs-tutorial.html)
* [Node.js下载地址](https://nodejs.org/en/download/)
* [Node.js安装教程](http://www.runoob.com/nodejs/nodejs-install-setup.html)
* [Node.js中文网](http://nodejs.cn/api/)
* [Node.js官网](https://nodejs.org/en/docs/)

#### Node.js 进阶——框架

* [Node.js koa/koa2](http://koa.bootcss.com/#introduction)
* [Node.js koa-grace 支持MVC](https://github.com/xiongwilee/koa-grace/tree/v2.x)

###笔记

js 全局对象 window
nodejs全局对象 global

nodes模块
每个文件就是一个模块

__filename当前文件被解析后的绝对路径 模块作用域内
外部不能直接访问
如果想要在一个模块中访问另一个模块中定义的变量
1.把变量作为global对象的一个属性，但是不推荐这种做法
2.使用模块队形module（module保存当前模块有关的信息）
在module对象下有一个子对象，可以通过这个对象把模块中的局部变量供外部访问

var m5＝require（./2.js） m5就是2.js的module.export

模块加载系统
require(‘模块地址’) 
注意：不能直接写require(‘2.js’) 会加载npde中的核心模块或node——modules
首先会按照加载模块的文件名进行查找
如果没有找到，会自动在文件名后面加上.js
如果还没有找到，就会在文件名称后加.json
如果还没有找到，就会在文件名称后加.node
如果还没有找到，就会抛出错误

process是一个全局变量，和当前程序有关的进程和细节

### 新浪云活动

新浪云平台Sina App Engine(SAE)，是由新浪公司开发和运营的开放云计算平台的核心组成部分，国内第一家公有云计算平台，可以为网站开发者，App开发者提供稳定、快捷、透明、可控的服务化的平台，并且减少开发者的开发和维护成本。

「新浪云福利」1000云豆免费领！低成本、免运维、灵活、安全稳定，轻松应对业务爆发式增长，一起来用吧！ 注册地址：http://t.cn/R5oFIaD


### 最新技术福利

免费视频教程百度云盘链接：

React Native入门  链接: https://pan.baidu.com/s/1qYtryC8

ionic入门  链接: https://pan.baidu.com/s/1i5mKcnF

微信小程序入门  链接: https://pan.baidu.com/s/1o8FGjDw

为了保证连接的可使用性，请关注微信公众号 <font color=red>`全栈弄潮儿`</font>，

React Native入门视频 回复“RN提取码”领取 提取码

ionic入门视频 回复“ionic提取码”领取 提取码

微信小程序入门视频 回复“小程序提取码”领取 提取码


#### 欢迎关注我的微信公众号或头条号`全栈弄潮儿` ，获取更多学习资源及技术文章等

* 微信公众号二维码，扫一扫或者搜索"全栈弄潮儿"即可关注

<img src="https://github.com/Alex-0407/sinacloud-node/blob/master/fullstack-8cm.jpg" width="320px" style="display:inline;">

* 今日头条号二维码，扫一扫即可关注

<img src="https://github.com/Alex-0407/node-demo/blob/master/toutiao.jpg" width="320px" style="display:inline;">
