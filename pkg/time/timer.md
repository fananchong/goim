## timer.go

提供一个优化的定时器功能
- 使用最小堆管理、排序`定时任务`
- 所有`定时任务`，只使用一个 golang 的 time.Timer
