# 1PanelTools
名字起得着实有点大了,现在的功能就是监控定时任务运行,如果出错的会自动给你发消息(通知现在只有一个gotify),默认运行间隔时间是1h,直接硬编码的,如果你要修改的话自行fork编译吧.

直接从release下载下来二进制文件,在同目录下照着 `.env.example` 配置一下东西就行了(我觉得我变量名起得挺清晰的,就没写注释).

哦对,保存数据的json文件权限我设置的是0777,请确保你运行时给了程序足够的权限(0777这权限确实太大了,但我自己用不想改了).
