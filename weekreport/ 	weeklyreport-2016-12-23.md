# weeklyreport-2016-12-16
## 王建兴
1.主要完成了第一次注册时邮件认证的功能  
重新搭建了服务端,上周发送的数据得不到有效处理可能是由于服务端多个module影响造成的,目前已经解决.  
客户端:完成邮件认证的逻辑:发送用户名和密码,解析服务端返回代码.完成注册后向系统发送通知.  
2.安装和升级的issue  
OTA的版本不再在代码中进行具体的管理而是放在dev.openthos.org中的配置文件中,代码中只实现版本管理的逻辑  
3.FM对seaf-cli提出了一些需求:  
需要普通权限运行,运行参数和路径需要修改,proot版本需要修改  
目前还有两个剩余的issue:  
849 2016-12-12 版， 安装界面， normal install里， 选择手动安装、自动安装的位置，显示的选项经常被命令行覆盖（显示错误）  
openthos投影问题  
