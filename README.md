# pandownload-fake-localserver
本地解压运行即可用的虚拟Pandownload服务器

程序运行后,默认会在你的 hosts 写入以下内容(为了保证替换成功,请右键->使用管理员身份运行)
```
127.0.0.1 pandownload.com
```
如果运行'Pandownload服务离线工具.exe'后,还是未成功添加hosts 请自行修改!

根据收到的意见,现在最新版本的,在软件关闭后会自动把hosts文件还原

Tips:原本hosts文件会备份到hosts.1文件 如果没还原成功可以手动替换回去

# 项目参考
[pandownload-fake-server](https://github.com/TkzcM/pandownload-fake-server/)

# 使用方法
1. [下载](https://github.com/EXACG/pandownload-fake-localserver/blob/master/PanDownload_localserver.zip?raw=true)
2. 解压
3. 运行'Pandownload服务离线工具.exe'
4. 运行'Pandownload.exe'

# 一些问题解决
问题:登陆后,卡在登录界面

答: ![login_error.png](login_error.png)
