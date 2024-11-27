# Low-latency-control-robot-with-webtransport
Merge webtransport RUST library into Dora-rs framework

## 项目描述
Dora-rs 是基于 RUST所打造的开源机器人应用框架，其意义重大，旨在简化基于 AI 的机器人应用程序创建流程。它具备出色的性能表现，提供低延迟、可组合以及分布式的数据流功能，能将应用程序建模为有向图（也就是管道）的形式，利用零拷贝 Apache Arrow 消息实现快速的数据传输，且支持 Python、C、C++ 以及 ROS2 等多语言，方便开发者参与开发，还拥有热重载等实用功能，虽目前处于实验阶段，但已在机器人控制、自主导航、计算机视觉、人机交互等诸多领域展现出应用潜力，为机器人开发领域带来了高效且极具创新性的新选择.  目前通信层支持 TCP， zenoh, DDS 等通信框架。

 WebTransport的迅速发展在一定程度上使得端云协同变得更加容易。WebTransport 支持客户端与服务器之间的双向通信，这对于端云协同至关重要。端侧设备可以主动向云侧发送数据，如用户的操作记录、设备状态信息等；云侧也能够及时地向端侧推送数据，如更新的模型参数、新的任务指令等，实现了端云之间信息的实时同步和交互，WebTransport 能够穿透 NAT 和防火墙以及多路复用，让协同更加紧密和高效。

我们的目标是在DORA-RS 通信层增加 WebTransport, Dora-rs 端云节点可以无缝通信。

## 所属赛道
2025全国大学生操作系统比赛的“OS功能设计”赛道

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求


## 项目导师

- 丁心民
- email ding@nnupylot.com

## 赛题分类
未归类的应用（如机器人、无人机等）

## 难度
中等

## 特征
- 理解ERDOS的代码实现和 Dora-rs 代码实现
- 移植watermark 部分代码到 Dora-rs 框架

- 
## 文档
https://dora-rs.ai/
https://github.com/BiagioFesta/wtransport

## License

Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标

不要求一定完成。选择本项目的同学也可提出自己的新想法，得到导师任何支持后亦可加入预期目标或进阶特性。
