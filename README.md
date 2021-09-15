# 《凤凰架构：构建可靠的大型分布式系统》勘误

本工程为《凤凰架构：构建可靠的大型分布式系统》纸质书的勘误，根据读者反馈持续更新，可通过[issues](https://github.com/fenixsoft/fenix_architecture_book/issues)提交新的勘误。
本仓库仅作勘误之用，如对书籍具体内容有建议或疑惑，欢迎到本书主页（[https://icyfenix.cn/](https://icyfenix.cn/)）对应章节的页面中提出。

### 勘误列表：

- **Page 201**：表8-1：一定时间【类】
<br>更正：一定时间【内】

- **Page 320-321**：# 访问模式为【RXO】\\ # 支持【RXO】访问模式
<br>更正：# 访问模式为【RWO】 \\ # 支持【RWO】访问模式

- **Page 363-364**：有3处【UDPA】笔误写成了【UDAP】，请编辑下次重印时修正一下。

#### 以下勘误内容已在第2次重印版（2021-8-25日）修正
------

- **Page 231**：通过财报上的营收、净利、毛利、资产、【负载】
<br>更正：通过财报上的营收、净利、毛利、资产、【负债】

- **Page 40**：Google API 【Deign】 Guide
<br>更正：Google API 【Design】 Guide

#### 以下勘误内容已在第1次重印版（2021-8-15日）修正
------

- **Page 28**：笔者曾经在“原始分布式时代”中介绍过 【DEC】，这是历史上第一次对分布式有组织的探索尝试，由于 【DEC】 本身是基于 UNIX 操作系统的，所以 【DEC】/RPC 通常也仅适合于 UNIX 系统程序之间使用
<br>更正：笔者曾经在“原始分布式时代”中介绍过 【DCE】，这是历史上第一次对分布式有组织的探索尝试，由于 【DCE】 本身是基于 UNIX 操作系统的，所以 【DCE】/RPC 通常也仅适合于 UNIX 系统程序之间使用

- **Page 30**：【DEC】/RPC 与 ONC RPC 都有很浓厚的 Unix 痕迹
<br>更正：【DCE】/RPC 与 ONC RPC 都有很浓厚的 Unix 痕迹

- **Page 42**：POST /appointmentService?action=【comfirm】 HTTP/1.1
<br>更正：POST /appointmentService?action=【confirm】 HTTP/1.1

- **Page 76**：同时依【然能够或者在】绝大多数时候保证处理结果的准确性
<br>更正：同时依然【能够在】绝大多数时候保证处理结果的准确性

- **Page 269**：这个容器是整个 Pod 中第一个启动的容器，只有【几十万字节】大小（代码只有很短的几十行，
<br>更正：这个容器是整个 Pod 中第一个启动的容器，只有【几百 KB】大小（代码只有很短的几十行，
<br>（上面这些英文都不应该进行翻译，我复审的时候没有检查出来）

- **Page 212**：TCP 协议的【阻塞控制（Congestion Control）】
<br>更正：TCP 协议的【流量控制（Flow Control）】

- **Page 234**：再譬如，当前方法的返回值是个【映射】，开发期的调试数据只做了三五个【实体】，觉得遍历一下把具体内容打到日志里面没什么问题，到了生产期，这个【映射】里面有可能存放了成千上万个【实体】，这时候打印日志就相当于引用慢操作
<br>更正：再譬如，当前方法的返回值是个【Map】，开发期的调试数据只做了三五个【Entity】，觉得遍历一下把具体内容打到日志里面没什么问题，到了生产期，这个【Map】里面有可能存放了成千上万个【Entity】，这时候打印日志就相当于引用慢操作
<br>（上面这些英文都不应该进行翻译，我复审的时候没有检查出来）

- **Page 279**：从 2018 年起，Helm 项目被托管到 【CNFC】
<br>更正：从 2018 年起，Helm 项目被托管到 【CNCF】

- **Page 351**：或者代理主动从【约定的好的】位置获取
<br>更正：或者代理主动从【约定好的】位置获取

- **Page 378**：可见族群运作的复杂度【就越高】，治理难度也越高。
<br>更正：可见族群运作的复杂度【越高】，治理难度也越高。
