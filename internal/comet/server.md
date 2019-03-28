## server.go

表示 comet 服务器类，一些功能的集合
主要包括：
- Bucket ， Room 、 Channel 管理
- LogicClient ，Logic 服务器的 GRPC 客户端实例
- 定期上报自己身上的 Room 、 Channel 数量；并获取相关 Room 总信息
