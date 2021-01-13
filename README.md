# Bilibili-Knowledge-Graph-Project

1. 前1000用户 互相关注的情况， 有向图
2. up 总关注 总播放量
3. up 主要活跃区域
4. up 合作视频



1. 最短路径
2. 关键节点
3. 相似up-图聚类
4. 推荐



up主基本信息（粉丝数排序）:
http://leptc.github.io/bili/2020/09/a.html

关注人:
https://api.bilibili.com/x/relation/followings?vmid=6420775&pn=1&ps=20&order=desc&jsonp=jsonp

投稿视频：
https://api.bilibili.com/x/space/arc/search?mid=546195&ps=30&tid=0&pn=1&keyword=&order=pubdate&jsonp=jsonp

up主主页基本信息
https://api.bilibili.com/x/space/acc/info?mid=546195&jsonp=jsonp

up主信息（关注人数，粉丝数）
https://api.bilibili.com/x/relation/stat?vmid=1&jsonp=jsonp

up主信息（总播放）
https://api.bilibili.com/x/space/upstat?mid=423895&jsonp=jsonp

实时进度：

~~提取关注度前3000up主名单（完成）~~

~~爬取总关注数，排序，提取关注前1000up主名单（标注数据提取时间）(完成)~~

遍历名单，爬取关注列表及视频列表，获得up在各个分区投稿数目

遍历所有合作视频，记录合作者mid及分工，视频创建为实体，只取在2019年1月1日及之后发布的视频

爬取萌娘百科up主词条，提取信息

（可选）遍历所有2年内发布的视频，提取视频的标签，播放量、投币、收藏、点赞、弹幕等

（可选）将标签创建为实体，并利用其分析up主之间的关系，以取代分区的作用

