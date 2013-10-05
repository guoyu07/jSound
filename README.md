jSound
======

jSound是一个轻量级的web提示声音兼容库，不依赖Flash等外部插件。在线演示：<http://www.toobug.net/jSound>

特色
======

1、封装不同浏览器的实现差异。目前只实现了非常简单的包装，支持audio标签的浏览器使用audio，不支持audio的使用bgsound实现  
2、封装不同浏览器对声音操作的差异。比如对音量的控制等。  
3、采用dataURI的方式内置常用提示音，无额外请求。  

ToDo
======

1、整理更多的常用声音并压缩内置  
2、解决内置声音对低版本浏览器的兼容方案  
3、管理多实例的播放（也许用constructor的方式？）