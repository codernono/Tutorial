* MQ总结
  * 消息总线（Message Queue），是一种跨进程的通信机制，用于上下游传递消息。
  * 在互联网架构中，MQ是一种非常常见的上下游“逻辑解耦+物理解耦”的消息通信服务。
* 什么时候不使用MQ？
  * 上游实时关注执行结果
* 什么时候使用MQ？
  * 数据驱动的任务依赖
  * 上游不关心多下游执行结果
  * 异步返回执行时间长