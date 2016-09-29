# LogMonitor - Log日志Web在线监控
实现网页监控系统日志，实时监控系统运行状态

#效果
![输入图片说明](http://git.oschina.net/uploads/images/2016/0928/115347_4742a2bb_490173.png "在这里输入图片标题")
![输入图片说明](http://git.oschina.net/uploads/images/2016/0928/115359_8404751a_490173.png "在这里输入图片标题")
![输入图片说明](http://git.oschina.net/uploads/images/2016/0928/115414_dd318ab3_490173.png "在这里输入图片标题")

#部署 

本项目为MyEclipse下Maven项目。文件和类都较少，修改你需要修改的文件和配置即可。

#运行 

Run as... ==> maven build... ==> jetty:run

#警告 

本功能的实现逻辑是基于servlet3.0的异步servlet和log4j的Appender，所以servlet必须3.0+，web.xml中的配置涉及到的过滤器必须全部配置为：
```
<async-supported>true</async-supported>
```

#开发计划
1.优化UI
2.封装成即插即用包

#联系 
![输入图片说明](http://git.oschina.net/uploads/images/2016/0928/120126_12ec637e_490173.png "在这里输入图片标题")