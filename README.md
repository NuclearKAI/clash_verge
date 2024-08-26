# clash_verge
bing.com重定向过多解决方案

使用clash verge开启全局代理后，打开edge使用bing进行搜索出现“当前无法使用此界面，cn.bing.com重定向次数过多，请尝试删除cookies”问题
![屏幕截图2024 08 27](https://github.com/user-attachments/assets/42dc26e1-a33f-4b29-b274-2538a739b93b)
解决方案：
打开clash verge→设置→系统代理→点击小齿轮图标→代理绕过设置：

在“代理绕过设置”中添加需要绕过的网站域名：bing.com;cn.bing.com;

多个域名用;隔开，可以使用*代替前缀，如：*.bing.com;

即可解决

![屏幕截图2024 08 272](https://github.com/user-attachments/assets/1931479c-9bbe-4908-b1dc-6a4073fdf7fb)

系统代理→点击小齿轮图标→代理绕过设置

![屏幕截图2024 08 237](https://github.com/user-attachments/assets/97fa40de-acc4-4379-940c-174216d1c3e8)

在“代理绕过设置”中添加需要绕过的网站域名：bing.com;cn.bing.com;
多个域名用;隔开，可以使用*代替前缀，如：*.bing.com;

NOTE:个人常用代理绕过设置
localhost;127.*;192.168.*;10.*;172.16.*;172.17.*;172.18.*;172.19.*;172.20.*;172.21.*;172.22.*;172.23.*;172.24.*;172.25.*;172.26.*;172.27.*;172.28.*;172.29.*;172.30.*;172.31.*;bing.com;cn.bing.com;gitee.com;baidu.com;sougou.com;so.com;quark.sm.cn;huya.com;douyu.com;bilibili.com;iqiyi.com;v.qq.com;youku.com;v.baidu.com;tv.souhu.com;tv.cctv.com;mgtv.com;miguvideo.com;douyin.com;toutiao.com;kuaishou.com;music.163.com;y.qq.com;kuwo.cn;kugou.com;xiami.com;music.migu.cn;music.douban.com;zhihu.com;weibo.com;youtiao.com;12306.cn;tieba.baidu.com;jianshu.com;juejin.cn;segmentfault.com;oschina.net;blog.csdn.net;cnblogs.com;iconfont.cn;wx.qq.com;meituan.com;ctrip.com;qunar.com;jd.com;taobao.com;pinduoduo.com;suning.com;tmall.com;vip.com;gome.com.cn;mogu.com;yhd.com;consumer.huawei.com;vivo.com.cn;mi.com;opposhop.cn;pan.baidu.com;lanzou.com;aliyundrive.com;ctfile.com;weiyun.com;cloud.189.cn;email.163.com;mail.qq.com;foxmail.com;mail.10086.cn;webmail30.189.cn;mail.sina.com.cn;mail.souhu.com;mail.wo.com.cn;mail.yahoo.com;mail.aliyun.com;mail.china.com;amap.com;map.qq.com;map.baidu.com;ditu.amap.com;docs.qq.com;docs.wps.cn;note.youdao.com;yuque.com;shimo.im;doc.weiyun.com;yinxiang.com;feishu.cn;zhipin.com;lanhuapp.com;bbs.oneplus.com;cloud.tencent.com;busuanzi.ibruce.info;wei.com;douyin.com;douyinpic.com;*.douyin.com;*.douyinpic.com;*.douyinvod.com;
