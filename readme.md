
## Lu-Rpc

Lu-Rpc 是个专为学习者准备的 RPC 框架, 初始架构非常简单, 可供初学者扩展和学习.

Lu 可以认为是中文世界的撸, 即撸 Rpc--- 造个 Rpc 轮子.

Lu-Rpc 架构图如下:

![](https://upload-images.jianshu.io/upload_images/4236553-a2bf8ddf71d1a993.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



Lu-Rpc 的领域模型设计借鉴 Dubbo, 服务域没有明显的界限. 核心域就是 Invoker, 非常合适作为核心领域模型的接口.

会话域可以是Request,也可以是 Invocation. 这个问题不大.

## 快速开始

在 test 目录下: cn.thinkinjava.example

先启动 ServerTest, 再启动 ClientTest. 


## 待开发功能
1. Lu-mesh
2. 负载均衡
3. 异常处理
4. 异步调用，feature 调用。oneway 调用
5. 连接管理，心跳管理
6. 服务监控
7. 服务优雅下线
8. 无缝支持 SpringBoot
9. 服务故障转移
10. 服务链路追踪
11. 支持分布式配置中心（自建或使用第三方）
12. 欢迎提交。。。。。

