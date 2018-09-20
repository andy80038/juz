# Juz

juz全称是桔子网关，是我们为了解决企业的痛点，专门研发的一套完全开源的网关。

对于传统的开源网关，存在几个主要的问题：
- 可配置性和可管理性不好
- 性能不够高
- 功能不够丰富
- 没有完善的管理权限控制
- 监控缺失

有鉴于此，我们重新开发了一套企业级别的网关，并且已经在内部使用2年之久，受到广泛好评，因此特地开源出来，让大家都能享受到优秀的API网关带来的便利性。

### 项目状态
Beta version: 0.5.0, 当前还不推荐在生产使用(虽然已经可以使用)，我们还需做更多的测试

### 安装
访问http://mafanr.com/lab/docs/juz/install获取更多信息

### 文档
http://mafanr.com/lab/docs/juz


![Juz简图](https://upload-images.jianshu.io/upload_images/8245841-09ab7c05653b1bfd.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

桔子具有以下功能和特性(部分还在开发中)
1. 流量代理
- 支持HTTP1.1/HTTP2/HTTPS/Websocket
- 请求调度
- 版本控制
- 鉴权、验签 
- 黑白名单
- 限速、限额 
- 熔断 
- 请求重试 
- 结果缓存
- 流量路由(金丝雀)

2. 应用防火墙WAP
- 拦截Web入侵：SQL注入/命令注入/XSS/Webshell上传等等
- 应用层DDOS防范
- 应对CC攻击和刷量场景
- 联动检测

3. 数据分析
- 访问日志
- 数据统计
- 开发数据接口
- 流量深度分析

4. 监控告警
- 流量异常监控
- 基于Jaeger的全链路监控
- 全链路日志
- 应用健康检查

