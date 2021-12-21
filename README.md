# RPC-Go-
## Go进阶训练营-极客大学-（新）
![25acb0bda2f5692bbf5b7cc93d661f1](https://user-images.githubusercontent.com/41461298/146961020-1fd67ee7-7286-4ffb-8e32-261559194136.png)
## 模块一：Go 架构实践 - 微服务（微服务概览与治理）
### 教学目标
1. 了解微服务的演进历史及它的优缺点

2. 了解微服务的设计方法

3. 了解微服务中 RPC 的底层原理

4. 多集群、多租户的概念

学习和工作中的痛点
1. 不理解微服务的服务角色：API Gateway、BFF 还是 Service？

2. 不知道怎么做微服务拆分

3. 不理解 RPC 的原理，不知道如何进行微服务 RPC 框架的选型

详细内容
1. 微服务的原理、概念，以及微服务的实现细节

2. API Gateway、BFF、Service 等概念精讲

3. 微服务通讯 RPC 框架的细节和选型

4. 多集群、多租户解决全链路压测、多测试环境等

本周领教直播内容
1. 梳理微服务基本概念

2. 落地微服务的一般步骤

3. 微服务的面试考点

4. 服务注册与发现模型
## 模块二：Go 语言实践 - 异常处理
### 教学目标
1. 了解 Go 语言中 error 的处理方法

2. 了解 Go 语言中业务错误的处理方法

学习和工作中的痛点
1. error 的处理复杂，不会正确使用

2. 业务错误定义和 error 整合难度较高

详细内容
1. Go 语言中的 error 处理实践：检查错误、定义错误、追加上下文

2. Go 项目中的业务错误码如何结合 error 的最佳实践

本周领教直播内容
1. 如何设计一个 error 处理机制

2. Kratos 错误处理

3. 错误处理原则补充
## 模块三：Go 语言实践 - 并行编程
### 教学目标
1. 了解 Go 语言中的 Memory Model

2. 了解 Go 语言的并发特性并发编程模式：Timeout、Pipeline、Cancellation、Fanout、errgroup 等模式

3. 了解 Go 语言中 Context 的原理并掌握其使用方法

学习和工作中的痛点
1. 搞不清楚 Go 中内存模型和同步语义

2. 无法熟练使用基于 channel 通讯方式的并行编程模式

3. 不明白 Context 传播式传递有什么意义

详细内容
1. 内存模型：Happens Before、同步语义、channel 通讯、锁

2. 利用 channel 完成并行开发的设计模式，包含超时控制、管道、扇出、errgroup 并发

3. 使用 Go 标准库 Context 的原理和最佳实践，包含超时控制、元数据传递、生命周期控制

本周领教直播内容
1. 演示各种并发代码

2. 常见并发错误

3. 进程、线程和协程的面试考点
## 模块四：Go 工程化实践
### 教学目标
1. 了解 Go 项目中良好的项目目录组织原则和规范

2. 了解 Go 项目中 API 的设计方法和规范

3. 了解 Go 项目中 Package 的管理和设计方法

4. 了解 Go 项目中的单元测试方法

学习和工作中的痛点
1. 不知道怎么做 Go 项目的标准化管理

2. 总是设计出各种不合理的 API

3. 不知道怎么做包管理

详细内容
1. 良好的 Go 项目中的分层目录结构组织和代码规范

2. Go 项目中 API 的设计原则和方法：定义、状态和业务错误码处理

3. Go 项目中包的设计和最佳实践、go mod 的使用

4. go test 工具链的使用方法、单元测试的最佳实践以及 Mock 技术

本周领教直播内容
1. Go 项目布局实践

2. Protobuf 和 Wire 入门
## 模块五：Go 架构实践 - 微服务（可用性设计）
### 教学目标
1. 掌握可用性设计的最佳实践

2. 了解可用性设计的几大关键点：隔离、超时控制、过载保护、限流、容错&重试

学习和工作中的痛点
1. 不知道如何设计高可用的分布式服务

2. 不清楚如何提升服务自愈能力

详细内容
1. 微服务的隔离实现，以及架构设计中的隔离实现

2. 进程内超时控制和跨进程超时控制
3. ![微信图片_20210928112223](https://user-images.githubusercontent.com/41461298/146962063-5eab7569-119e-4425-9c3f-d975a22c90c9.jpg)


3. 程序自保护避免过载，抛弃一定的流量完成自适应限流

4. 单机限流、多租户场景的分布式限流

5. 节点故障的容错逻辑、重试容错的策略和设计

本周领教直播内容
1. 实践中的重试方案

2. RPC 框架中链路超时控制实现原理

3. 微服务可用性的面试考点

4. 服务治理：故障检测、故障处理和故障恢复
## 模块六：评论系统架构设计
### 教学目标
1. 评论系统的存储、缓存设计

2. 评论系统的可用性设计

3. 评论系统的架构设计

学习和工作中的痛点
1. 缓存的单飞加载，缓存的流控，缓存的优化技巧

2. 缓存和存储的数据一致性设计，多级缓存的设计，热点缓存的应对

3. 异步消息队列消峰设计

详细内容
1. 评论系统设计中结合消息队列如何做存储优化

2. 评论系统设计中缓存、存储设计的方案

本周领教直播内容
1. 实践中树形数据的表设计：以评论系统为例

2. 缓存模式
## 模块七：播放历史架构设计
### 教学目标
1. 掌握极高 TPS，高 QPS 系统的架构设计思路

2. 掌握消息队列在海量数据持久化场景中的最佳实践

学习和工作中的痛点
1. 极高 TPS，高 QPS 系统在设计和优化中如何做取舍

2. 对于海量写入如何消峰，提高系统吞吐

详细内容
1. 历史记录系统如何做架构设计和技术选型

2. 历史记录系统设计中缓存、存储设计的方案

3. 如何结合消息队列做数据持久化的优化

4. 提升系统可用性的核心思想和技巧

本周领教直播内容
1. 缓存写模式，本地缓存

2. 高并发问题的一般解决思路

3. Redis 面试考点
## 模块八：Go 架构实践 - 中间件（缓存、数据库）
### 教学目标
![微信图片_20210928112223](https://user-images.githubusercontent.com/41461298/146962078-146d59e7-7954-424a-83eb-e8c6e5aa740f.jpg)

1. 了解 Redis、Memcache 的原理和实战使用

2. 了解 MySQL 的常用设计和优化

学习和工作中的痛点
1. Redis、Memcache 的应用场景、最佳实践，以及缓存的一致性设计

2. MySQL 的表设计，常用优化手段，如何解决分布式事务

详细内容
1. Redis、Memcache 的应用场景、最佳实践，以及缓存的一致性设计

2. MySQL 的表设计、常用优化手段，以及如何解决分布式事务

本周领教直播内容
1. 实践中解决分布式事务一致性的一般方法

2. 分布式事务基本概念、规范

3. Even Sourcing 和 SAGA
## 模块九：Go 语言实践 - 网络编程
### 教学目标
1. 熟练掌握 Go 语言中的 TCP 网络编程

2. 熟练掌握 Go 语言中的 HTTP 网络编程

学习和工作中的痛点
1. 不知道怎么用 Go 实现高性能的 TCP Server

2. HTTP 框架有不少，但不知道怎样做选型

3. 不会针对业务需求对 HTTP 框架做针对性的扩展

详细内容
1. 结合 goim 项目了解 Go 语言中 TCP Server 的基础库和性能优化方案

2. 结合 gin 项目了解 Go 语言中的 HTTP Server 的基础库和框架

本周领教直播内容
1. epoll 和 select

2. RPC 网络通信协议的设计思路

3. 如何设计一个简单的通信协议
## 块十：Go 架构实践 - 中间件（日志、指标、链路追踪）
### 教学目标
![微信图片_20210928112223](https://user-images.githubusercontent.com/41461298/146962081-6160e119-b28c-4508-96c7-ba2e3fe3ea77.jpg)

1. 了解 Go 项目中的日志收集

2. 了解 Go 项目中的监控指标体系

3. 了解 Go 项目中的分布式链路追踪

学习和工作中的痛点
1. 不知道如何解决微服务的可观测性难题

2. 不清楚怎么做微服务的可视化和标准化

3. 出故障后，难以对微服务进行问题诊断

详细内容
1. 实现一个可以集中收集所有微服务实例的日志，并能统一查看和检索的日志采集架构

2. 指标监控、使用 Prometheus 解决监控可视化、指标采集

3. 微服务中的跨服务性能问题诊断，结合 Jaeger 实现分布式链路追踪

## 本周领教直播内容
![微信图片_20210928112223](https://user-images.githubusercontent.com/41461298/146962093-d95d2772-e8cc-41ec-96bf-e4af14b950e0.jpg)

1. 可观测性

2. opentracing、prometheus 入门

3. HTTP 和 RPC 可观测性实践
## 模块十一：Go 架构实践 - 分布式架构（前端负载均衡）
### 教学目标
1. 掌握高可用 DNS 的最佳实践

2. 了解 CDN 的架构和应用场景

3. 深入理解 4/7 层负载均衡的原理

学习和工作中的痛点
1. 缺乏对在线服务的全链路视野

2. 不了解应用服务上层的负载均衡

详细内容
1. DNS 的原理、防劫持的方法、HTTPDNS + IP 长连接

2. CDN 的系统架构、应用领域以及保证数据一致性的方法

3. LVS、Nginx 4/7 层负载均衡的原理和实践

本周领教直播内容
1. 分库分表基本概念

2. 从中间件设计的角度理解分库分表

3. 分库分表面试：以案例为核心
## 模块十二：Go 架构实践 - 中间件（消息队列、服务发现）
### 教学目标
1. 深入理解消息队列的原理，掌握基于消息队列的架构设计方法

2. 服务发现原理、选型策略，以及服务发现实现的微服务多租户架构

学习和工作中的痛点
1. 不会做消息解耦的架构设计

2. 不清楚如何实现服务发现对平滑发布的支持

3. 不知道怎样利用多租户实现多测试环境

详细内容
1. Kafka 的实现原理、异步消息系统的架构设计

2. RPC 服务发现、动态地址的选型和实现原理，以及基于服务发现的平滑重启和多租户架构

本周领教直播内容
1. Kafka 典型场景

2. Kafka 面试准备要点

3. 中间件设计的通用技术
## 模块十三：Go 语言实践 - Runtime
### 教学目标
![微信图片_20210928112223](https://user-images.githubusercontent.com/41461298/146962103-684f9eb7-62bb-46bf-bb3b-4c604cc8179c.jpg)

1. 了解 Go 语言中 Goroutine 的调度原理

2. 了解 Go 语言中的内存模型

3. 了解 Go 语言中 GC（垃圾回收）的原理

4. 了解 Go 语言中 channel 的消息通讯原理

学习和工作中的痛点
1. 分不清 Goroutine 和线程的区别

2. 不熟悉 Go 的内存分配机制

3. 搞不懂 GC 三色标记算法

4. 不了解 channel 的底层实现

详细内容
1. Goroutine 的实现、GPM 调度模型、调度状态及流转、调度原理、协作式抢占以及和网络库的协作

2. Go 内存分配的内部结构和分配机制

3. Go GC 介绍、三色标记的实现原理、GC 的流程以及 GC 的一些优化方案

4. Go channel 的通讯机制、环形队列的结构、调度和唤醒的原理

本周领教直播内容
1. 内存管理的一般模式：以 Go、Java、Linux 内核为例
