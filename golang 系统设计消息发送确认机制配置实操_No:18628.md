最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计消息发送确认机制配置实操
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.ogntmfh.asia/blog/1305571.sHtMl

原标题：TLS 版本兼容 HTTPS 握手失败
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.ogntmfh.asia/blog/6727800.sHtMl

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.ogntmfh.asia/blog/5073764.sHtMl

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.ogntmfh.asia/blog/9914216.sHtMl

原标题：golang 多协程任务池并发控制
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.ogntmfh.asia/blog/2904877.sHtMl

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.ogntmfh.asia/blog/2357196.sHtMl

原标题：从零搭建简单的健康检查接口示例
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.ogntmfh.asia/blog/9884287.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.ogntmfh.asia/blog/8861371.sHtMl

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.ogntmfh.asia/blog/0835242.sHtMl

原标题：Security：密码存储哈希加盐最佳实践
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.ogntmfh.asia/blog/5251561.sHtMl

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.ogntmfh.asia/blog/7407617.sHtMl

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.ogntmfh.asia/blog/1273530.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.ogntmfh.asia/blog/1956066.sHtMl

原标题：golang redis zset 排行榜业务实现
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.ogntmfh.asia/blog/2600780.sHtMl

原标题：实践：接口参数自动校验业务落地实践
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.ogntmfh.asia/blog/8521519.sHtMl

原标题：特殊输入字符过滤解析防护
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.ogntmfh.asia/blog/6017235.sHtMl

原标题：HTTP 状态码请求头完整梳理
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.ogntmfh.asia/blog/4106059.sHtMl

原标题：开源实践：开源项目本地调试构建排坑经验
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.ogntmfh.asia/blog/3451864.sHtMl

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.ogntmfh.asia/blog/7751995.sHtMl

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.ogntmfh.asia/blog/3152679.sHtMl

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.ogntmfh.asia/blog/6056480.sHtMl

原标题：快速入门gRPC基础概念与简单示例
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.ogntmfh.asia/blog/2309127.sHtMl

原标题：react 状态管理方案选型对比
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.ogntmfh.asia/blog/4060585.sHtMl

原标题：golang 系统设计短信发送限流降级
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.ogntmfh.asia/blog/6701786.sHtMl

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.ogntmfh.asia/blog/6349947.sHtMl

原标题：接口限流逻辑简单模拟实现
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.ogntmfh.asia/blog/4018930.sHtMl

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.ogntmfh.asia/blog/7781482.sHtMl

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.ogntmfh.asia/blog/6319605.sHtMl

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.ogntmfh.asia/blog/6231259.sHtMl

原标题：前端图片懒加载性能优化
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.ogntmfh.asia/blog/8873453.sHtMl

原标题：ServiceWorker 缓存页面更新清理
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.ogntmfh.asia/blog/2857647.sHtMl

原标题：golang 系统设计内存高占用排查思路
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.ogntmfh.asia/blog/6331091.sHtMl

原标题：golang 系统设计数据库基准压测简单思路
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.ogntmfh.asia/blog/5362348.sHtMl

原标题：golang 系统设计接口超时设计原则梳理
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.ogntmfh.asia/blog/1540193.sHtMl

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.ogntmfh.asia/blog/7019016.sHtMl

原标题：golang docker 私有仓库搭建使用
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.ogntmfh.asia/blog/0795377.sHtMl

原标题：golang 优雅处理 http 超时设置
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.ogntmfh.asia/blog/1640674.sHtMl

原标题：golang docker 基础命令实操汇总
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.ogntmfh.asia/blog/1523510.sHtMl

原标题：golang makefile 自动化构建脚本
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.ogntmfh.asia/blog/4126040.sHtMl

原标题：golang 系统设计开源项目 release 发布流程
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.ogntmfh.asia/blog/5351527.sHtMl


二、踩坑排错｜Troubleshooting
原标题：CDN 缓存刷新获取最新静态资源
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.ogntmfh.asia/blog/4163861.sHtMl

原标题：线上接口超时故障排查思路
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.ogntmfh.asia/blog/0094820.sHtMl

原标题：从零学习简单分页逻辑实现思路
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.ogntmfh.asia/blog/9344962.sHtMl

原标题：序列化版本不一致解析失败
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.ogntmfh.asia/blog/4511711.sHtMl

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.ogntmfh.asia/blog/9875591.sHtMl

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.ogntmfh.asia/blog/2542133.sHtMl

原标题：短信服务封装失败自动重试
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.ogntmfh.asia/blog/5813384.sHtMl

原标题：golang ci 流水线环境变量管理方案
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.ogntmfh.asia/blog/7410167.sHtMl

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.ogntmfh.asia/blog/3905073.sHtMl

原标题：Nginx 丢失请求头配置修正
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.ogntmfh.asia/blog/0419978.sHtMl

原标题：Docker 容器入门镜像实操教程
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.ogntmfh.asia/blog/5249415.sHtMl

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.ogntmfh.asia/blog/1821831.sHtMl

原标题：golang 大文件读取内存优化
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.ogntmfh.asia/blog/5504829.sHtMl

原标题：golang 系统设计内存复用 sync.pool 使用
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.ogntmfh.asia/blog/6708987.sHtMl

原标题：golang 系统设计开源项目协作流程梳理
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.ogntmfh.asia/blog/2787607.sHtMl

原标题：程序性能指标 CPU 内存监控
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.ogntmfh.asia/blog/6676931.sHtMl

原标题：golang redis pipeline 原子性说明
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.ogntmfh.asia/blog/4498955.sHtMl

原标题：golang 系统设计参数校验统一处理方案
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.ogntmfh.asia/blog/2704974.sHtMl

原标题：golang docker 部署 prometheus 整套
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.ogntmfh.asia/blog/2627117.sHtMl

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.ogntmfh.asia/blog/2565344.sHtMl

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.ogntmfh.asia/blog/6646863.sHtMl

原标题：项目构建脚本编译打包解析
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.ogntmfh.asia/blog/8710297.sHtMl

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.ogntmfh.asia/blog/2370486.sHtMl

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.ogntmfh.asia/blog/5224677.sHtMl

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.ogntmfh.asia/blog/8932438.sHtMl

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.ogntmfh.asia/blog/8888715.sHtMl

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.ogntmfh.asia/blog/9318128.sHtMl

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.ogntmfh.asia/blog/2178489.sHtMl

原标题：内存溢出问题现象识别排查
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.ogntmfh.asia/blog/8082439.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.ogntmfh.asia/blog/1164475.sHtMl

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.ogntmfh.asia/blog/1083146.sHtMl

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.ogntmfh.asia/blog/6604224.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.ogntmfh.asia/blog/2361598.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.ogntmfh.asia/blog/6276319.sHtMl

原标题：golang redis set 集合去重业务
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.ogntmfh.asia/blog/5591875.sHtMl

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.ogntmfh.asia/blog/5630771.sHtMl

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.ogntmfh.asia/blog/5846565.sHtMl

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.ogntmfh.asia/blog/5252979.sHtMl

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.ogntmfh.asia/blog/6831313.sHtMl

原标题：跨平台换行符统一异常修复
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.ogntmfh.asia/blog/0622944.sHtMl

三、实战开发｜Practice
原标题：慢查询分析索引调优数据库实战
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.ogntmfh.asia/blog/5232201.sHtMl

原标题：Git commit 钩子提交规范校验
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.ogntmfh.asia/blog/2596450.sHtMl

原标题：golang redis 限流几种实现方案
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.ogntmfh.asia/blog/8189454.sHtMl

原标题：GitHub 项目提交推送完整流程讲解
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.ogntmfh.asia/blog/6008998.sHtMl

原标题：缓存穿透防护保护数据库
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.ogntmfh.asia/blog/5539712.sHtMl

原标题：golang ci 流水线环境变量管理方案
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.ogntmfh.asia/blog/2116410.sHtMl

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.ogntmfh.asia/blog/1487827.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.ogntmfh.asia/blog/8142710.sHtMl

原标题：实践：大文件分片上传后端完整实现思路
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.ogntmfh.asia/blog/6337690.sHtMl

原标题：GitHub 项目提交推送完整流程讲解
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.ogntmfh.asia/blog/1747557.sHtMl

原标题：golang mysql 分表自增 id 方案
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.ogntmfh.asia/blog/2677666.sHtMl

原标题：多套环境灵活切换配置方案
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.ogntmfh.asia/blog/8178108.sHtMl

原标题：golang 系统设计分库分表中间件思路
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.ogntmfh.asia/blog/4708688.sHtMl

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.ogntmfh.asia/blog/8538545.sHtMl

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.ogntmfh.asia/blog/8111348.sHtMl

原标题：golang 系统设计接口防刷 ip 限流实现
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.ogntmfh.asia/blog/8036745.sHtMl

原标题：前后端交互跨域问题完整处理
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.ogntmfh.asia/blog/8031748.sHtMl

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.ogntmfh.asia/blog/7735686.sHtMl

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.ogntmfh.asia/blog/5257225.sHtMl

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.ogntmfh.asia/blog/6852155.sHtMl

原标题：编译打包产物依赖分析解读
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.ogntmfh.asia/blog/8152365.sHtMl

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.ogntmfh.asia/blog/6888930.sHtMl

原标题：CI 构建缓存加速编译速度
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.ogntmfh.asia/blog/1054750.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.ogntmfh.asia/blog/3609308.sHtMl

原标题：golang 项目 go mod 依赖管理
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.ogntmfh.asia/blog/9294789.sHtMl

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.ogntmfh.asia/blog/0269034.sHtMl

原标题：快速入门消息通知简单实现方案
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.ogntmfh.asia/blog/9632453.sHtMl

原标题：golang 简单爬虫请求防封禁
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.ogntmfh.asia/blog/5578137.sHtMl

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.ogntmfh.asia/blog/2544111.sHtMl

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.ogntmfh.asia/blog/6378576.sHtMl

原标题：实战项目：GitHubAction自动测试构建实践
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.ogntmfh.asia/blog/8774284.sHtMl

原标题：数据库读写分离性能优化
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.ogntmfh.asia/blog/9354727.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.ogntmfh.asia/blog/7169754.sHtMl

原标题：实战：数据库explain执行计划分析实操演练
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.ogntmfh.asia/blog/7786996.sHtMl

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.ogntmfh.asia/blog/2844798.sHtMl

原标题：golang docker 镜像安全扫描漏洞
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.ogntmfh.asia/blog/1030961.sHtMl

原标题：项目依赖安全扫描漏洞防范
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.ogntmfh.asia/blog/0918829.sHtMl

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.ogntmfh.asia/blog/8251054.sHtMl

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.ogntmfh.asia/blog/2939730.sHtMl

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.ogntmfh.asia/blog/4741990.sHtMl

四、架构设计｜Architecture
原标题：Performance：长连接管理优化减少连接重建开销
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.ogntmfh.asia/blog/8824937.sHtMl

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.ogntmfh.asia/blog/2494379.sHtMl

原标题：golang http 服务性能优化调参
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.ogntmfh.asia/blog/2527851.sHtMl

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.ogntmfh.asia/blog/8311148.sHtMl

原标题：golang 分布式锁防死锁处理
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.ogntmfh.asia/blog/5817227.sHtMl

原标题：跨平台 uniapp 多端开发实操
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.ogntmfh.asia/blog/5863129.sHtMl

原标题：零基础理解幂等性基础概念与场景
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.ogntmfh.asia/blog/3780456.sHtMl

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://book.ogntmfh.asia/blog/7713986.sHtMl

原标题：golang 定时任务 cron 使用指南
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.ogntmfh.asia/blog/0667199.sHtMl

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.ogntmfh.asia/blog/7688392.sHtMl

原标题：macOS 脚本执行权限开启
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.ogntmfh.asia/blog/5345990.sHtMl

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.ogntmfh.asia/blog/5280061.sHtMl

原标题：golang jwt 过期刷新 token 实现
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.ogntmfh.asia/blog/9278832.sHtMl

原标题：CDN 缓存刷新获取最新静态资源
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.ogntmfh.asia/blog/8485735.sHtMl

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.ogntmfh.asia/blog/8593262.sHtMl

原标题：项目实践：定时任务防重复执行落地实践
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.ogntmfh.asia/blog/4837607.sHtMl

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.ogntmfh.asia/blog/7799719.sHtMl

原标题：实战：数据库explain执行计划分析实操演练
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.ogntmfh.asia/blog/9819028.sHtMl

?
