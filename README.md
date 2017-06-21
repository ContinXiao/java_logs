## log4j2 使用目标

### 不同类别的日志分开记录
> * 业务调用日志
> * 性能监控日志
> * 访问日志

### 日志按照级别输出到不同文件
> * `error` 级别输出到error日志
> * `warn` 级别输出到warn日志
> * `info` 级别输出到info日志
> * 控制台不输出日志

### 大小与容量控制
> * 按照时间间隔滚动生成
> * 按照大小滚动生成
> * 只保留30天的日志
> * 日志总大小控制

### 全局唯一ID支持
> * 应用域唯一ID
> * 全链路唯一ID

### 性能
> * 高吞吐/低负载
> * 低内存消耗（Garbage-free）


