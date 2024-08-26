# clash_verge
bing.com重定向过多解决方案

使用clash verge开启全局代理后，打开edge使用bing进行搜索出现“当前无法使用此界面，cn.bing.com重定向次数过多，请尝试删除cookies”问题
解决方案：
打开clash verge→设置→系统代理→点击小齿轮图标→代理绕过设置：
在“代理绕过设置”中添加需要绕过的网站域名：bing.com;cn.bing.com;
多个域名用;隔开，可以使用*代替前缀，如：*.bing.com;
即可解决
