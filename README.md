# 留学数据爬取
##### 本库包括了四个爬虫，分别爬取：寄托天下、一亩三分地、ChaseDream以及新浪微博。

整体的格式是按照这个库来写的：https://github.com/DolorHunter/1p3aMSCSAdminReport 。

#### 一亩三分地
一亩三分地基本就是照搬上面的库，详细的可以看一下上面的这个库是如何运行的。唯一的问题就是触发bot检测机制了。我基本上是爬一页就停10-20分钟，这样的话只是到时检测一下bot即可，不会封号，如果停的时间没有这么长，大概率是直接封号。

#### 寄托天下
寄托天下的爬虫是在一亩三分地的基础上改的。一亩三分地可能会被官方从远程手动关闭连接，这个时候换个IP地址，继续跑就行了。因为寄托不存在看信息需要积分的情况，所以不存在封号的问题。

#### ChaseDream和weibo
这俩就没啥好说的了。
