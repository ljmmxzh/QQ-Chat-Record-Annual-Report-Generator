# QQ-Chat-Record-Annual-Report-Generator
qq聊天记录生成年度报表
## 重要代码来源：
原始微信聊天年度报表生成
https://foolishfox.cn/posts/202402-WeChatMsgAnalysis.html
重要参考代码来自以下ipynb文件
https://gist.github.com/YiHui-Liu/1ed2f9484c5e20587d016e5d7854c273
词义文件txt均在目录下。
同等重要的qq生成网页项目：
https://github.com/ping-xiong/annual-report-builder
这是一个非常简单的exe就能完成的年度报表生成
## 使用前有一些要注意的地方：
1、首先我们应先导出电脑版本的txt文件
2、与原始的微信聊天记录分析类似，不过导出之后需要注意的是将，所有发送者的名字统一替换为某某（qq号）的格式，这样方便处理，同时因为qq的聊天记录是每次更改名称之后都会有不同的名字，所以需要替换多次来统一命名，然后我们需要聊天记录的头部删除，只保留一般格式的聊天记录
3、使用上述年度报表分析的exe时路径不能有中文出现，包括txt文件名称。
4、将首先处理好的txt文件重命名为2.txt放入本项目同级目录下，依次运行ipynb命令即可，如遇上问题请参照代码说明进行日期上的修改，可能是前调或者后调以保证周数对的上。
