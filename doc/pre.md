前言：网站开发、搜索和爬虫是异曲同工的，开发过网站，弄过搜索，回到爬虫，觉得很有趣，以前开发大型python爬虫，项目管理难，且用的都是别人封装的库，而且要开发并发程序也难，坑多，有些写到最后一堆乱麻，不排除我的问题，知其所以然才是王道，Golang HTTP原生库你可以直接看到代码，学习到HTTP协议的实现，我的包是在原生库基础上进行封装，支持高并发，各种结构都加了锁，人类友好姿态API。--||

Golang爬虫封装包，组件化开发，支持Cookie持久，用户代理，多浏览器模拟等，封装了redis和mysql,可敏捷开发。

使用场景：网站测试自动化，脚本刷单（阿里要打我），写各种外挂（留言灌水，机器人！），对接阿里云、网易云音乐、新浪等API（等你们提需求，我要写token hmac1 mad5啥的加密登录），自动发文章（单平台写一篇发多个平台，要自己实现），爬各种数据（文章，图片，种子，这种很暴力，如爬天猫全网数据，京东啥的，有点风险，做这种工作的不太道德）

目前不从事网站开发和爬虫开发，兴趣所向，以前做数据挖掘（其实是爬虫）的同事也很牛逼，请移动到：http://www.tybai.com 我的技术博客为http://www.lenggirl.com

爬虫需谨慎，有风险！