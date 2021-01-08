正则改标题


例：
原始链接
第01集$https://youku.cdn11-okzy.com/20200729/19087_46eb4026/index.m3u8
更改为
#EXTINF:-1 ,恶之花 第02集
https://youku.cdn11-okzy.com/20200730/19118_2acef27d/index.m3u8


代码如下：
查找    第(\d\d{1,})集\$
替换为   #EXTINF:-1 ,恶之花 第$1集\n



