最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.ntppp5.asia/blog/2506351.sHtML

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.ntppp5.asia/blog/9733085.sHtML

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.ntppp5.asia/blog/9986570.sHtML

原标题：golang prometheus 告警规则编写
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.ntppp5.asia/blog/5073261.sHtML

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.ntppp5.asia/blog/3679647.sHtML

原标题：SourceMap 生成线上报错定位
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.ntppp5.asia/blog/5495449.sHtML

原标题：快速入门OpenAPI文档生成基础实践
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.ntppp5.asia/blog/4027093.sHtML

原标题：Practice：实现业务操作日志记录中间件实践
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.ntppp5.asia/blog/7246080.sHtML

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.ntppp5.asia/blog/9334087.sHtML

原标题：运维笔记：服务器故障排查常用命令清单
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.ntppp5.asia/blog/0913255.sHtML

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.ntppp5.asia/blog/1086867.sHtML

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.ntppp5.asia/blog/2577553.sHtML

原标题：golang 系统设计消息 partition 数量设置思路
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.ntppp5.asia/blog/5468464.sHtML

原标题：Practice：实现业务唯一流水号生成组件实践
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.ntppp5.asia/blog/0861278.sHtML

原标题：零基础理解版本控制核心概念与工作流
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.ntppp5.asia/blog/5193800.sHtML

原标题：golang es 映射 mapping 设计避坑
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.ntppp5.asia/blog/4565217.sHtML

原标题：nodejs 接口限流防刷代码实现
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.ntppp5.asia/blog/6491434.sHtML

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.ntppp5.asia/blog/6380838.sHtML

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.ntppp5.asia/blog/7518588.sHtML

原标题：golang 系统设计 lru 缓存算法实现思路
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.ntppp5.asia/blog/3478456.sHtML

原标题：HelloCI：理解持续集成基础工作流程
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.ntppp5.asia/blog/4449682.sHtML

原标题：前端下载导出文件功能实现
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.ntppp5.asia/blog/0807443.sHtML

原标题：golang es 高亮搜索结果实现方案
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.ntppp5.asia/blog/0728838.sHtML

原标题：数据库事务 ACID 原理讲解
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.ntppp5.asia/blog/4362616.sHtML

原标题：golang redis hyperloglog 基数统计
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.ntppp5.asia/blog/9024130.sHtML

原标题：记一次字符集编码不一致乱码问题全排查
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.ntppp5.asia/blog/1192884.sHtML

原标题：布隆过滤器误判问题修正
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.ntppp5.asia/blog/6273884.sHtML

原标题：快速上手简单信号处理脚本编写
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.ntppp5.asia/blog/8853324.sHtML

原标题：Performance：数据库join优化，大表join规避
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.ntppp5.asia/blog/8323509.sHtML

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.ntppp5.asia/blog/3016996.sHtML

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.ntppp5.asia/blog/8680624.sHtML

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.ntppp5.asia/blog/2276896.sHtML

原标题：golang 文件上传下载接口开发
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.ntppp5.asia/blog/5757995.sHtML

原标题：golang 系统设计用户签到统计方案
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.ntppp5.asia/blog/8837052.sHtML

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.ntppp5.asia/blog/1692468.sHtML

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.ntppp5.asia/blog/0145798.sHtML

原标题：golang 系统设计分库分表中间件思路
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.ntppp5.asia/blog/2051316.sHtML

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.ntppp5.asia/blog/9898000.sHtML

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.ntppp5.asia/blog/4670513.sHtML

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.ntppp5.asia/blog/7586418.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计避免索引失效书写 sql 原则
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.ntppp5.asia/blog/6254553.sHtML

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.ntppp5.asia/blog/3708800.sHtML

原标题：编译打包产物依赖分析解读
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.ntppp5.asia/blog/7859248.sHtML

原标题：golang 协程 panic 捕获防止崩溃
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.ntppp5.asia/blog/5315485.sHtML

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.ntppp5.asia/blog/1957043.sHtML

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.ntppp5.asia/blog/2429277.sHtML

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.ntppp5.asia/blog/7508338.sHtML

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.ntppp5.asia/blog/2662721.sHtML

原标题：方案设计：分布式分页查询架构难点处理
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.ntppp5.asia/blog/6407572.sHtML

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.ntppp5.asia/blog/8805942.sHtML

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.ntppp5.asia/blog/8143488.sHtML

原标题：golang url 参数编码处理方案
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.ntppp5.asia/blog/2338788.sHtML

原标题：golang mysql 批量导入数据实操
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.ntppp5.asia/blog/5491131.sHtML

原标题：golang 容器健康检查接口开发
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.ntppp5.asia/blog/3417479.sHtML

原标题：golang mysql limit 大分页优化
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.ntppp5.asia/blog/8345507.sHtML

原标题：实践：API接口文档自动导出离线文档实践
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.ntppp5.asia/blog/6804128.sHtML

原标题：效率笔记：调试网络请求curl命令高级用法
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.ntppp5.asia/blog/0179640.sHtML

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.ntppp5.asia/blog/3792506.sHtML

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.ntppp5.asia/blog/4170981.sHtML

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.ntppp5.asia/blog/6022731.sHtML

原标题：实战项目：实现分布式任务调度最小原型
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.ntppp5.asia/blog/4584902.sHtML

原标题：浮点计算精度错误处理方案
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.ntppp5.asia/blog/5977052.sHtML

原标题：Shell 脚本自动化命令编写
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.ntppp5.asia/blog/8898666.sHtML

原标题：golang 系统设计分布式事务业务选型决策思路
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.ntppp5.asia/blog/2435647.sHtML

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.ntppp5.asia/blog/7199179.sHtML

原标题：golang 系统设计接口频率限制业务落地
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.ntppp5.asia/blog/9775738.sHtML

原标题：golang mysql 联合索引最左匹配
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.ntppp5.asia/blog/4908503.sHtML

原标题：方案设计：统一错误处理架构全链路方案
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.ntppp5.asia/blog/9493792.sHtML

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.ntppp5.asia/blog/3633319.sHtML

原标题：安全笔记：文件下载接口路径校验安全
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.ntppp5.asia/blog/4896879.sHtML

原标题：零基础理解依赖管理与包管理器
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.ntppp5.asia/blog/1683134.sHtML

原标题：DevOps：环境配置管理区分开发测试生产
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.ntppp5.asia/blog/7458019.sHtML

原标题：golang 系统设计数据库扩容几种方式
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.ntppp5.asia/blog/0132457.sHtML

原标题：golang 系统设计容器健康检查设计思路
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.ntppp5.asia/blog/4564531.sHtML

原标题：golang redis pipeline 原子性说明
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.ntppp5.asia/blog/6946891.sHtML

原标题：前端打包产物体积压缩优化
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.ntppp5.asia/blog/6314534.sHtML

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.ntppp5.asia/blog/5372407.sHtML

原标题：多环境配置中心灵活切换方案
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.ntppp5.asia/blog/1282749.sHtML

原标题：服务器时钟同步任务错乱修复
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.ntppp5.asia/blog/6463491.sHtML

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.ntppp5.asia/blog/6839063.sHtML

三、实战开发｜Practice
原标题：静态网页 HTML CSS 快速入门实战
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.ntppp5.asia/blog/7974933.sHtML

原标题：排错：打包后资源路径，开发生产行为不一致
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.ntppp5.asia/blog/4589506.sHtML

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.ntppp5.asia/blog/4689352.sHtML

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.ntppp5.asia/blog/2727705.sHtML

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.ntppp5.asia/blog/3297145.sHtML

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.ntppp5.asia/blog/2419988.sHtML

原标题：安全复盘：消息队列未授权访问安全加固
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.ntppp5.asia/blog/9995204.sHtML

原标题：时间精度统一业务判断修复
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.ntppp5.asia/blog/8948041.sHtML

原标题：服务启动依赖顺序配置正确
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.ntppp5.asia/blog/7567629.sHtML

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.ntppp5.asia/blog/1694949.sHtML

原标题：golang k8s 日志收集 efk 简单架构
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.ntppp5.asia/blog/7242578.sHtML

原标题：golang 系统设计消息幂等消费去重实现方案
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.ntppp5.asia/blog/3174661.sHtML

原标题：golang gorm 批量插入性能调优
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.ntppp5.asia/blog/6810706.sHtML

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.ntppp5.asia/blog/6194641.sHtML

原标题：部署实践：容器时区统一配置解决方案
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.ntppp5.asia/blog/0629126.sHtML

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.ntppp5.asia/blog/0430994.sHtML

原标题：接口签名校验防篡改实现
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.ntppp5.asia/blog/6330220.sHtML

原标题：golang k8s 命名空间资源隔离方案
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.ntppp5.asia/blog/6986920.sHtML

原标题：Docker 容器入门镜像实操教程
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.ntppp5.asia/blog/8157201.sHtML

原标题：nodejs 事件循环机制完整讲解
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.ntppp5.asia/blog/2667197.sHtML

原标题：调试工具断点调试变量查看技巧
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.ntppp5.asia/blog/7135830.sHtML

原标题：跨域偶现失败配置修复
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.ntppp5.asia/blog/8244997.sHtML

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.ntppp5.asia/blog/7129143.sHtML

原标题：移动端适配 rem vw 方案对比
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.ntppp5.asia/blog/2930667.sHtML

原标题：Practice：实现请求body重复读取中间件实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.ntppp5.asia/blog/8979688.sHtML

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.ntppp5.asia/blog/6298458.sHtML

原标题：golang kafka offset 提交策略
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.ntppp5.asia/blog/7162201.sHtML

原标题：前端大文件分片上传完整方案
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.ntppp5.asia/blog/9770827.sHtML

原标题：golang gin 静态资源访问配置
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.ntppp5.asia/blog/3202022.sHtML

原标题：数据库分表路由写入分片修正
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.ntppp5.asia/blog/0151631.sHtML

原标题：多套环境灵活切换配置方案
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.ntppp5.asia/blog/8518643.sHtML

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.ntppp5.asia/blog/1908074.sHtML

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.ntppp5.asia/blog/0941865.sHtML

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.ntppp5.asia/blog/5615390.sHtML

原标题：golang docker 部署 kafka 本地调试
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.ntppp5.asia/blog/6385531.sHtML

原标题：运维笔记：服务器Swap分区调优生产实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.ntppp5.asia/blog/1577664.sHtML

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.ntppp5.asia/blog/3311794.sHtML

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.ntppp5.asia/blog/2340081.sHtML

原标题：golang 系统设计消息幂等消费去重实现方案
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.ntppp5.asia/blog/2417029.sHtML

原标题：调优方案：消息队列消费速度优化处理堆积
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.ntppp5.asia/blog/3959179.sHtML

四、架构设计｜Architecture
原标题：坑点：软链接权限问题容器读取文件失败
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.ntppp5.asia/blog/2501436.sHtML

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.ntppp5.asia/blog/7222132.sHtML

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.ntppp5.asia/blog/2010534.sHtML

原标题：WebSocket 聊天室实时通讯开发
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.ntppp5.asia/blog/3248330.sHtML

原标题：golang mysql 联合索引最左匹配
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.ntppp5.asia/blog/5213859.sHtML

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.ntppp5.asia/blog/7571995.sHtML

原标题：架构思考：单体应用向微服务拆分演进路径
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.ntppp5.asia/blog/2966832.sHtML

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.ntppp5.asia/blog/5540833.sHtML

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.ntppp5.asia/blog/7695951.sHtML

原标题：磁盘占满服务不可用清理方案
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.ntppp5.asia/blog/0834388.sHtML

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.ntppp5.asia/blog/7957304.sHtML

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.ntppp5.asia/blog/3388266.sHtML

原标题：golang gorm ORM 数据库操作
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.ntppp5.asia/blog/5329962.sHtML

原标题：golang 简易埋点日志上报实现
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.ntppp5.asia/blog/4808270.sHtML

原标题：golang 数据库慢查询监控实现
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.ntppp5.asia/blog/6453790.sHtML

原标题：golang redis pipeline 批量操作
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.ntppp5.asia/blog/7970721.sHtML

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.ntppp5.asia/blog/3892465.sHtML

原标题：操作系统内核版本适配服务
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.ntppp5.asia/blog/8996725.sHtML

?
