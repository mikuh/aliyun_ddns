# aliyun_ddns
利用阿里云ddns接口实现动态ip dns刷新实现远程访问<br>
因为国内禁用了家庭宽带的80等端口，所以要使用别的接口。

阿里云的文档写的比较烂，懒得细看了，在https://github.com/limoxi/aliyun_ddns的基础上改成了python3的版本,增加了定时任务。


##使用方法
在settings.json 填入自己的密钥和ip<br>
在阿里云上增加该ip的到相关A记录域名解析<br>
运行ddns.py `python ddns.py`
