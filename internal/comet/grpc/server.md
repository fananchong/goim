## server.go

Job 服务会通过 GRPC 调用该类方法

Job 主要让 Comet 做如下事情：
- Ping ，ping comet
- PushMsg ， 推送消息给 comet ， comet 然后发给客户端
- Broadcast ，让 comet 广播消息
- BroadcastRoom ，让 comet 做房间内消息广播
- Rooms ，从 comet 获取该 comet 上所有房间 ID 号
