## room.go

提供一个房间类
- 创建房间
- 关闭房间
- 加入 channel
- 删除 channel
- 维护本房间人数、该房间真实人数（多个 comet 上可能都有同一个房间）
  - Online 字段
  - AllOnline 字段
- 下发房间消息给 channel
