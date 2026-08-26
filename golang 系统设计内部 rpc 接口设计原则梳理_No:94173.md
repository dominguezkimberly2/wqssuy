最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.z7yotk.asia/arts/771107.Doc

原标题：golang cron 定时任务防并发执行
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.z7yotk.asia/arts/004711.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.z7yotk.asia/arts/664829.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.z7yotk.asia/arts/960836.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.z7yotk.asia/arts/260211.Doc

原标题：golang kafka 同步异步消费对比
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.z7yotk.asia/arts/262025.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.z7yotk.asia/arts/296980.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.z7yotk.asia/arts/752968.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.z7yotk.asia/arts/131276.Doc

原标题：golang 链路 traceId 透传中间件
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.z7yotk.asia/arts/726584.Doc

原标题：golang redis 连接池参数最佳值
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.z7yotk.asia/arts/413921.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.z7yotk.asia/arts/299341.Doc

原标题：golang consul 服务发现简单示例
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.z7yotk.asia/arts/720729.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.z7yotk.asia/arts/830393.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.z7yotk.asia/arts/245033.Doc

原标题：ICMP 放通网络丢包问题修复
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.z7yotk.asia/arts/123474.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.z7yotk.asia/arts/608629.Doc

原标题：主干开发团队代码合并策略
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.z7yotk.asia/arts/645705.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.z7yotk.asia/arts/217666.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.z7yotk.asia/arts/444916.Doc

原标题：golang prometheus 告警规则编写
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.z7yotk.asia/arts/808005.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.z7yotk.asia/arts/918061.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.z7yotk.asia/arts/345340.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.z7yotk.asia/arts/501135.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.z7yotk.asia/arts/664453.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.z7yotk.asia/arts/974749.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.z7yotk.asia/arts/833241.Doc

原标题：分布式任务调度集群原型开发
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.z7yotk.asia/arts/715663.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.z7yotk.asia/arts/285582.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.z7yotk.asia/arts/976843.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.z7yotk.asia/arts/572664.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.z7yotk.asia/arts/137813.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.z7yotk.asia/arts/181497.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.z7yotk.asia/arts/771799.Doc

原标题：git rebase 整理提交历史实操
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.z7yotk.asia/arts/304729.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.z7yotk.asia/arts/941723.Doc

原标题：golang gorm ORM 数据库操作
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.z7yotk.asia/arts/011803.Doc

原标题：golang 接口返回统一封装工具
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.z7yotk.asia/arts/512434.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.z7yotk.asia/arts/075864.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.z7yotk.asia/arts/330681.Doc


二、踩坑排错｜Troubleshooting
原标题：架构笔记：多数据源架构设计事务处理难点
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.z7yotk.asia/arts/296800.Doc

原标题：golang 配置文件多环境加载
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.z7yotk.asia/arts/993134.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.z7yotk.asia/arts/605519.Doc

原标题：golang mysql 避免 select * 查询
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.z7yotk.asia/arts/327221.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.z7yotk.asia/arts/899967.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.z7yotk.asia/arts/807674.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.z7yotk.asia/arts/601196.Doc

原标题：Spring 事务传播机制配置生效
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.z7yotk.asia/arts/960054.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.z7yotk.asia/arts/926217.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.z7yotk.asia/arts/073695.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.z7yotk.asia/arts/011356.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.z7yotk.asia/arts/781939.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.z7yotk.asia/arts/533350.Doc

原标题：golang grpc protobuf 开发实操
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.z7yotk.asia/arts/572464.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.z7yotk.asia/arts/047091.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.z7yotk.asia/arts/630731.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.z7yotk.asia/arts/311068.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.z7yotk.asia/arts/674653.Doc

原标题：golang docker 部署 kafka 本地调试
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.z7yotk.asia/arts/084924.Doc

原标题：OpenAPI 自动接口文档生成
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.z7yotk.asia/arts/857942.Doc

原标题：环境变量不生效问题修复
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.z7yotk.asia/arts/077602.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.z7yotk.asia/arts/590980.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.z7yotk.asia/arts/634367.Doc

原标题：gitignore 文件编写过滤规则
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.z7yotk.asia/arts/604107.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.z7yotk.asia/arts/976111.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.z7yotk.asia/arts/151332.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.z7yotk.asia/arts/757232.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.z7yotk.asia/arts/080955.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.z7yotk.asia/arts/086218.Doc

原标题：golang github actions 发布 release 包
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.z7yotk.asia/arts/778061.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.z7yotk.asia/arts/886032.Doc

原标题：从零搭建简单Mock接口服务
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.z7yotk.asia/arts/099850.Doc

原标题：零基础理解进程、线程基础概念区别
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.z7yotk.asia/arts/480663.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.z7yotk.asia/arts/645004.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.z7yotk.asia/arts/729105.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.z7yotk.asia/arts/318039.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.z7yotk.asia/arts/354447.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.z7yotk.asia/arts/319436.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.z7yotk.asia/arts/898222.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.z7yotk.asia/arts/900297.Doc

三、实战开发｜Practice
原标题：设计思考：业务系统如何做故障隔离架构
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.z7yotk.asia/arts/559474.Doc

原标题：golang docker 镜像构建最佳实践
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.z7yotk.asia/arts/717004.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.z7yotk.asia/arts/614036.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.z7yotk.asia/arts/567689.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.z7yotk.asia/arts/044370.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.z7yotk.asia/arts/167976.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.z7yotk.asia/arts/649139.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.z7yotk.asia/arts/269405.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.z7yotk.asia/arts/419033.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.z7yotk.asia/arts/497614.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.z7yotk.asia/arts/753288.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.z7yotk.asia/arts/234377.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.z7yotk.asia/arts/715759.Doc

原标题：JSON XML 数据解析处理示例
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.z7yotk.asia/arts/590367.Doc

原标题：前端工程化 webpack 打包优化
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.z7yotk.asia/arts/199129.Doc

原标题：golang 系统设计会话共享多实例部署
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.z7yotk.asia/arts/593152.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.z7yotk.asia/arts/893151.Doc

原标题：定时任务周期调度 demo 开发
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.z7yotk.asia/arts/372007.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.z7yotk.asia/arts/269971.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.z7yotk.asia/arts/231122.Doc

原标题：接口请求重试容错机制实现
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.z7yotk.asia/arts/901244.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.z7yotk.asia/arts/564028.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.z7yotk.asia/arts/819863.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.z7yotk.asia/arts/154137.Doc

原标题：前端静态缓存更新生效处理
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.z7yotk.asia/arts/218142.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.z7yotk.asia/arts/156622.Doc

原标题：进程线程并发基础概念讲解
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.z7yotk.asia/arts/931096.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.z7yotk.asia/arts/482137.Doc

原标题：golang mysql 字符集排序规则设置
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.z7yotk.asia/arts/552232.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.z7yotk.asia/arts/190190.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.z7yotk.asia/arts/743738.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.z7yotk.asia/arts/788214.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.z7yotk.asia/arts/866326.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.z7yotk.asia/arts/177353.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.z7yotk.asia/arts/694423.Doc

原标题：golang 大文件 http 下载服务
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.z7yotk.asia/arts/893086.Doc

原标题：数据库读写分离性能优化
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.z7yotk.asia/arts/335875.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.z7yotk.asia/arts/604782.Doc

原标题：golang docker compose 环境变量
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.z7yotk.asia/arts/180658.Doc

原标题：golang 单例模式实现几种方式
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.z7yotk.asia/arts/561752.Doc

四、架构设计｜Architecture
原标题：golang 系统设计时间字段选型 datetime timestamp
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.z7yotk.asia/arts/764882.Doc

原标题：轻量 API 后端接口服务快速开发
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.z7yotk.asia/arts/209828.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.z7yotk.asia/arts/501104.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.z7yotk.asia/arts/260808.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.z7yotk.asia/arts/212366.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.z7yotk.asia/arts/183006.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.z7yotk.asia/arts/062879.Doc

原标题：nestjs 全局返回格式统一处理
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.z7yotk.asia/arts/741200.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.z7yotk.asia/arts/744238.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.z7yotk.asia/arts/252584.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.z7yotk.asia/arts/899906.Doc

原标题：golang es 分词器选型业务适配
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.z7yotk.asia/arts/730487.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.z7yotk.asia/arts/829509.Doc

原标题：游标分页大数据查询性能提升
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.z7yotk.asia/arts/434180.Doc

原标题：golang grpc protobuf 开发实操
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.z7yotk.asia/arts/215433.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.z7yotk.asia/arts/185804.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.z7yotk.asia/arts/012888.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.z7yotk.asia/arts/827184.Doc

?
