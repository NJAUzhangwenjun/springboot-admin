# 说明
最简单的单线程单次访问BIO模式简易http服务器。
# 知识点
- http 请求建立在tcp/ip请求上。
- http 访问本质是网络io
# 过程
1 建立 socket连接，开始监听。

2 获取 客户端输入流，读入缓存区

3 获取 客户端输入流，写入内容

4 关闭 文件io流，socket网络流