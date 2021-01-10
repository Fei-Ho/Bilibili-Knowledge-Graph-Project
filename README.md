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
