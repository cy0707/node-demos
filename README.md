# Learn-node.js

## 该项目的小练习

 * add-student: 利用node.js+express+mongoose做的一个简易的学生的增删改查。
 * shuoshuo：利用node.js+express+mongodb做的一个简易的班级说说,实现了以下功能。
 1. 实现了用户的注册登陆。
 2. 头像的上传与剪裁。
 3. 说说的发表。
 4. 查看其他用户与自己的说说。
 
 * small-album: 一个node.js版的在线文件管理小系统。相对应的也有PHP版的，但是PHP版的
相对比较更加完善。

* small-douban----node.js+express+mongoose做的电影展示小网站，实现了以下功能。
1. 注册与持久化的登陆。
2. 前端首页对电影的分类展示---点击各个分类进入---带有分页的该分类的列表页。
3. 前端首页的搜索框，可以对电影进行模糊搜索，并且对搜索结果进行了分页显示。
4. 前端的电影详情页---具有对电影的详情信息展示+以及电影视频的观看+用户评论（带有二级评论）。
5. 后台电影的录入页面（使用豆瓣电影api）-----输入电影id,直接录入电影信息
6. 后台管理电影增删改。
7. 后台管理用户增删改。


## 2017

### 关于Node.js

学习Node.js的时候，幸好之前学习了PHP，虽然当时只是想了解一下后台到底是怎跟前端进行通信的，
并没有想怎样，不过却让我弄懂了后台到底干了什么事情，而且还一并学习了MYSQL。还是收获满满。
有了后台是干什么的思想，加上前端工作的js语言基础。学起来还是挺容易的。Node.js与php相比较,
还是有了一些小体会。

* php地址栏的路径对应的一定的文件夹，而这个是由Apache提供的，而Node.js提交的服务，
地址栏上路径大部分都不一定有这个文件夹。

* Node.js是单线程。处理并发，是要进行排队的。php是多线程的。

* 如果PHP代码损坏，不会拖垮整个服务器。 PHP代码只运行在自己的进程范围中，当某个请求显示错误时，
它只对特定的请求产生影响。而在Node.js环境中，所有的请求均在单一的进程服务中，当某个请求导致未知错误时，整个服务器都会受到影响。


### 关于Express

* 这个框架api不太多，花不了多长时间就掌握了基本用法。最重要的还是中间件概念。当然掌握基本的
用法还是不够的，还学多加学习练习。


