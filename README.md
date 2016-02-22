# MapReduce Demo

Map-Reduce程序场景代码。

已完成的有：

> 1.网站kpi数据统计   
> 2.电信运营商用户基站停留数据统计   

##1.网站kpi数据统计

程序中分别对五个kpi指标进行统计操作：   
> 1.browser：用户使用的浏览器统计   
> 2.ips：页面用户独立ip数统计   
> 3.pv：网站pv量统计   
> 4.source：用户来源网址统计   
> 5.time：时间段用户访问量统计   

[数据下载][2]

##2.电信运营商用户基站停留数据统计

原始数据分为位置和网络两种   
位置数据格式为：    
用户标识 设备标识 开关机信息 基站位置 通讯的时间   
example:   
0000009999  0054785806  3   00000089    2016-02-21 21:55:37

网络数据格式为：   
用户标识 设备标识 基站位置 通讯的时间 访问的URL   
example:   
0000000999  0054776806  00000109    2016-02-21 23:35:18 www.baidu.com

需要得到的数据格式为：   
用户标识 时段 基站位置 停留时间

example:00001 09-18 00003 15   
用户00001在09-18点这个时间段在基站00003停留了15分钟

[数据下载][3]

详情见代码

作者：[@小黑][1]

[1]:http://www.xiaohei.info
[2]:http://download.csdn.net/detail/qq1010885678/9439530
[3]:http://download.csdn.net/detail/qq1010885678/9439587
