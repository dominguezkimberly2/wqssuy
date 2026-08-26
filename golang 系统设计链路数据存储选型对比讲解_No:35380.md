最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计链路数据存储选型对比讲解
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.jgkds3.asia/blog/670440.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.jgkds3.asia/blog/864633.Doc

原标题：开源项目本地运行排错完整清单
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.jgkds3.asia/blog/580107.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.jgkds3.asia/blog/746911.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.jgkds3.asia/blog/457063.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.jgkds3.asia/blog/773313.Doc

原标题：golang k8s ingress 路由域名转发
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.jgkds3.asia/blog/303988.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.jgkds3.asia/blog/447392.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.jgkds3.asia/blog/181717.Doc

原标题：批量数据处理脚本编写技巧
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.jgkds3.asia/blog/529212.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.jgkds3.asia/blog/441049.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.jgkds3.asia/blog/581326.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.jgkds3.asia/blog/755218.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.jgkds3.asia/blog/679770.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.jgkds3.asia/blog/753986.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.jgkds3.asia/blog/878913.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.jgkds3.asia/blog/387019.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.jgkds3.asia/blog/719336.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/585149.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.jgkds3.asia/blog/075719.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.jgkds3.asia/blog/856527.Doc

原标题：golang mock 单元测试编写技巧
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/522188.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.jgkds3.asia/blog/952414.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.jgkds3.asia/blog/389818.Doc

原标题：golang toml 配置文件解析教程
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.jgkds3.asia/blog/377471.Doc

原标题：golang redis 事务 multi exec 使用
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.jgkds3.asia/blog/901790.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.jgkds3.asia/blog/372570.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/488454.Doc

原标题：golang redis 发布订阅简单示例
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.jgkds3.asia/blog/205442.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.jgkds3.asia/blog/342363.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.jgkds3.asia/blog/492763.Doc

原标题：跨库查询性能优化处理
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.jgkds3.asia/blog/294537.Doc

原标题：golang 项目 docker compose 本地调试
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.jgkds3.asia/blog/592421.Doc

原标题：golang 时间时区处理避坑指南
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/719807.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.jgkds3.asia/blog/359881.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/319825.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.jgkds3.asia/blog/962444.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.jgkds3.asia/blog/327127.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.jgkds3.asia/blog/188070.Doc

原标题：golang github actions 发布 release 包
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.jgkds3.asia/blog/834367.Doc


二、踩坑排错｜Troubleshooting
原标题：静态网页 HTML CSS 快速入门实战
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.jgkds3.asia/blog/978003.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.jgkds3.asia/blog/742584.Doc

原标题：消息队列重复消费业务处理
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.jgkds3.asia/blog/429344.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.jgkds3.asia/blog/453554.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.jgkds3.asia/blog/418859.Doc

原标题：golang 接口限流中间件开发
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.jgkds3.asia/blog/746660.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.jgkds3.asia/blog/786269.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.jgkds3.asia/blog/423555.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.jgkds3.asia/blog/638468.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.jgkds3.asia/blog/978705.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.jgkds3.asia/blog/155807.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.jgkds3.asia/blog/192435.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.jgkds3.asia/blog/150512.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.jgkds3.asia/blog/790780.Doc

原标题：golang minio 对象存储接口开发
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.jgkds3.asia/blog/054735.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.jgkds3.asia/blog/590309.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.jgkds3.asia/blog/126225.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.jgkds3.asia/blog/190259.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.jgkds3.asia/blog/370662.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.jgkds3.asia/blog/349813.Doc

原标题：golang gin 静态资源访问配置
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.jgkds3.asia/blog/904724.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.jgkds3.asia/blog/856553.Doc

原标题：多环境配置中心灵活切换方案
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.jgkds3.asia/blog/660657.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.jgkds3.asia/blog/648717.Doc

原标题：快速入门消息队列基础概念模型
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.jgkds3.asia/blog/567973.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.jgkds3.asia/blog/367690.Doc

原标题：golang 熔断降级简易组件开发
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.jgkds3.asia/blog/348015.Doc

原标题：golang elasticsearch 索引设计思路
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.jgkds3.asia/blog/426486.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.jgkds3.asia/blog/484435.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.jgkds3.asia/blog/243232.Doc

原标题：golang etcd 配置中心简单使用
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.jgkds3.asia/blog/154031.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.jgkds3.asia/blog/539109.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.jgkds3.asia/blog/885108.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.jgkds3.asia/blog/552171.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.jgkds3.asia/blog/422416.Doc

原标题：预编译 SQL 防注入实现
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.jgkds3.asia/blog/182731.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.jgkds3.asia/blog/819706.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.jgkds3.asia/blog/372187.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://book.jgkds3.asia/blog/949114.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.jgkds3.asia/blog/618027.Doc

三、实战开发｜Practice
原标题：入门实战：搭建简易静态网页项目
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.jgkds3.asia/blog/311749.Doc

原标题：golang docker 部署 redis 配置要点
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.jgkds3.asia/blog/720519.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.jgkds3.asia/blog/612449.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.jgkds3.asia/blog/459843.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.jgkds3.asia/blog/679450.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.jgkds3.asia/blog/046567.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.jgkds3.asia/blog/270343.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.jgkds3.asia/blog/886535.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.jgkds3.asia/blog/466995.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.jgkds3.asia/blog/276853.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.jgkds3.asia/blog/393221.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.jgkds3.asia/blog/718108.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.jgkds3.asia/blog/159517.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.jgkds3.asia/blog/313627.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.jgkds3.asia/blog/348333.Doc

原标题：业务接口幂等完整落地案例
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.jgkds3.asia/blog/190187.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.jgkds3.asia/blog/852713.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.jgkds3.asia/blog/233412.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.jgkds3.asia/blog/792180.Doc

原标题：golang redis 过期 key 监听业务
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.jgkds3.asia/blog/480664.Doc

原标题：golang minio 分片上传断点续传
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.jgkds3.asia/blog/534310.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.jgkds3.asia/blog/036238.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.jgkds3.asia/blog/174031.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.jgkds3.asia/blog/993980.Doc

原标题：后端分页查询逻辑代码实现
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.jgkds3.asia/blog/897261.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.jgkds3.asia/blog/230518.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.jgkds3.asia/blog/631368.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.jgkds3.asia/blog/342251.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.jgkds3.asia/blog/311076.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.jgkds3.asia/blog/527294.Doc

原标题：golang k8s job 一次性任务执行
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.jgkds3.asia/blog/344308.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.jgkds3.asia/blog/578013.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.jgkds3.asia/blog/220564.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.jgkds3.asia/blog/826221.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.jgkds3.asia/blog/043001.Doc

原标题：集成测试业务流程编写示例
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.jgkds3.asia/blog/606883.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.jgkds3.asia/blog/922391.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.jgkds3.asia/blog/514302.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.jgkds3.asia/blog/189876.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.jgkds3.asia/blog/882472.Doc

四、架构设计｜Architecture
原标题：架构复盘：多实例部署业务状态无状态改造
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.jgkds3.asia/blog/717432.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.jgkds3.asia/blog/427877.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.jgkds3.asia/blog/557716.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.jgkds3.asia/blog/196522.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.jgkds3.asia/blog/821417.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.jgkds3.asia/blog/786757.Doc

原标题：开发测试生产多环境配置区分
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.jgkds3.asia/blog/972792.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.jgkds3.asia/blog/464327.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.jgkds3.asia/blog/674735.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.jgkds3.asia/blog/347649.Doc

原标题：读懂开源项目 README 实用技巧
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.jgkds3.asia/blog/781019.Doc

原标题：golang k8s cronjob 定时任务配置
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://book.jgkds3.asia/blog/000237.Doc

原标题：时间同步修复令牌提前过期
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.jgkds3.asia/blog/855657.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.jgkds3.asia/blog/959191.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.jgkds3.asia/blog/808998.Doc

原标题：快速入门简单签名校验实现思路
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.jgkds3.asia/blog/291209.Doc

原标题：对象存储上传下载权限实操
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.jgkds3.asia/blog/789522.Doc

原标题：浏览器内存泄漏排查前端页面
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.jgkds3.asia/blog/968536.Doc

?
