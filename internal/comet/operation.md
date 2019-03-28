## operation.go

与 Logic 服务交互的 GRPC 调用

可以理解为，相关业务逻辑都可以写这里

目前从客户端开始触发的有：

- Connect / OpAuth ，账号验证
- Heartbeat / OpHeartbeat ，心跳
- Operate / OpChangeRoom ，进入或换房间
- Operate / OpSub ，订阅某主题
- Operate / OpUnsub ，取消订阅某主题
- Receive / 未知协议

目前从 comet 开始触发的有：
- Disconnect / 账号断开连接
- RenewOnline / 定时同步 Comet 到 Logic
