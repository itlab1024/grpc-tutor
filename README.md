# gRPC学习笔记
# gRPC是什么？
[gRPC](https://grpc.io/)是一个高性能、开源的通用RPC框架，他是基于[protocol-buffers](https://developers.google.cn/protocol-buffers/)实现的一个框架。
![](https://itlab1024-1256529903.cos.ap-beijing.myqcloud.com/202301191216748.png)
# 能做什么？
首先他是一个RPC框架，也就是支持服务调用，其显著特点是支持多语言，并且传输的数据量特别小。
![](https://itlab1024-1256529903.cos.ap-beijing.myqcloud.com/202301191217749.png)
# 基础
要学习[gRPC](https://grpc.io/)必须要先掌握[protocol-buffers](https://developers.google.cn/protocol-buffers/)，因为grpc就是通过
[protocol-buffers](https://developers.google.cn/protocol-buffers/)定义的消息（Message）生成的针对不同语言的代码。
# 消息定义
我们就使用官方的消息示例来看下rpc到底是什么，如何使用？
