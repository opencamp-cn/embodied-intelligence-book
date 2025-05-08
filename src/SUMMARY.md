# 具身智能系统开发与实践

[前言](./preface.md)

## 第一篇 基础架构篇

- [第1章 具身智能范式演进](./part1/ch1/_index.md)
  - [1.1 从符号主义到具身认知的范式迁移](./part1/ch1/section1.md)
  - [1.2 物理具身的四维约束（时空-能量-材料-信息）](./part1/ch1/section2.md)
  - [1.3 国产化技术生态现状（飞腾架构/Rust工具链/机器人中间件）](./part1/ch1/section3.md)
  
- [第2章 Rust系统编程精要](./part1/ch2/_index.md)
  - [2.1 所有权系统与资源管理模型](./part1/ch2/section1.md)
  - [2.2 无畏并发与实时性保障](./part1/ch2/section2.md)
  - [2.3 零成本抽象在嵌入式场景的应用](./part1/ch2/section3.md)
  - [2.4 飞腾派裸金属开发特殊考量](./part1/ch2/section4.md)

- [第3章 ArceOS组件化操作系统](./part1/ch3/_index.md)
  - [3.1 微内核架构的Rust实现](./part1/ch3/section1.md)
  - [3.2 异步驱动框架设计原理](./part1/ch3/section2.md)
  - [3.3 安全域隔离机制（TrustZone集成）](./part1/ch3/section3.md)
  - [3.4 混合关键任务调度策略](./part1/ch3/section4.md)

- [第4章 Dora-rs机器人中间件](./part1/ch4/_index.md)
  - [4.1 Actor模型在实时系统的实现](./part1/ch4/section1.md)
  - [4.2 数据流编程范式优化](./part1/ch4/section2.md)
  - [4.3 跨平台通信协议设计](./part1/ch4/section3.md)
  - [4.4 故障安全机制实现](./part1/ch4/section4.md)

## 第二篇 硬件交互篇

- [第5章 机电系统建模与控制](./part2/ch5/_index.md)
  - [5.1 双轴差速运动学模型](./part2/ch5/section1.md)
  - [5.2 机械臂D-H参数建模与逆解算法](./part2/ch5/section2.md)
  - [5.3 伺服系统电流环-速度环-位置环设计](./part2/ch5/section3.md)
  - [5.4 执行器安全边界保护策略](./part2/ch5/section4.md)

- [第6章 传感器融合体系](./part2/ch6/_index.md)
  - [6.1 多源时空标定方法](./part2/ch6/section1.md)
  - [6.2 视觉-IMU-编码器紧耦合原理](./part2/ch6/section2.md)
  - [6.3 基于Rust的卡尔曼滤波实现](./part2/ch6/section3.md)
  - [6.4 异常数据鲁棒处理机制](./part2/ch6/section4.md)

- [第7章 实时通信架构](./part2/ch7/_index.md)
  - [7.1 确定性网络协议设计](./part2/ch7/section1.md)
  - [7.2 共享内存与零拷贝技术](./part2/ch7/section2.md)
  - [7.3 基于优先级的数据通道管理](./part2/ch7/section3.md)
  - [7.4 通信完整性验证方法](./part2/ch7/section4.md)

## 第三篇 智能决策篇

- [第8章 视觉感知系统](./part3/ch8/_index.md)
  - [8.1 嵌入式视觉流水线架构](./part3/ch8/section1.md)
  - [8.2 轻量化神经网络部署（飞腾NPU加速）](./part3/ch8/section2.md)
  - [8.3 立体视觉深度估计优化](./part3/ch8/section3.md)
  - [8.4 动态目标预测算法](./part3/ch8/section4.md)

- [第9章 自主决策系统](./part3/ch9/_index.md)
  - [9.1 行为树与状态机融合架构](./part3/ch9/section1.md)
  - [9.2 基于Rust的实时规划器设计](./part3/ch9/section2.md)
  - [9.3 不确定性应对策略（蒙特卡洛方法）](./part3/ch9/section3.md)
  - [9.4 能量感知任务调度](./part3/ch9/section4.md)

- [第10章 学习型系统构建](./part3/ch10/_index.md)
  - [10.1 仿真到实物的迁移学习](./part3/ch10/section1.md)
  - [10.2 在线强化学习框架设计](./part3/ch10/section2.md)
  - [10.3 参数自整定方法](./part3/ch10/section3.md)
  - [10.4 经验回放系统实现](./part3/ch10/section4.md)

## 第四篇 系统集成篇

- [第11章 安全关键系统设计](./part4/ch11/_index.md)
  - [11.1 形式化验证方法论](./part4/ch11/section1.md)
  - [11.2 混合临界资源管理](./part4/ch11/section2.md)
  - [11.3 故障树分析与容错设计](./part4/ch11/section3.md)
  - [11.4 SIL4级系统实现路径](./part4/ch11/section4.md)

- [第12章 实时性能优化](./part4/ch12/_index.md)
  - [12.1 最坏执行时间分析](./part4/ch12/section1.md)
  - [12.2 缓存一致性控制](./part4/ch12/section2.md)
  - [12.3 中断延迟优化方法](./part4/ch12/section3.md)
  - [12.4 能源效率联合优化](./part4/ch12/section4.md)

- [第13章 驱动开发实践](./part4/ch13/_index.md)
  - [13.1 外设抽象层设计原则](./part4/ch13/section1.md)
  - [13.2 DMA安全访问机制](./part4/ch13/section2.md)
  - [13.3 异构计算驱动开发](./part4/ch13/section3.md)
  - [13.4 热插拔支持实现](./part4/ch13/section4.md)

- [第14章 系统验证方法](./part4/ch14/_index.md)
  - [14.1 硬件在环测试架构](./part4/ch14/section1.md)
  - [14.2 模糊测试用例生成](./part4/ch14/section2.md)
  - [14.3 全场景覆盖测试](./part4/ch14/section3.md)
  - [14.4 长期运行老化测试](./part4/ch14/section4.md)

## 第五篇 前沿拓展篇

- [第15章 群体智能系统](./part5/ch15/_index.md)
  - [15.1 分布式共识算法优化](./part5/ch15/section1.md)
  - [15.2 群体任务分配博弈论模型](./part5/ch15/section2.md)
  - [15.3 自组织通信协议设计](./part5/ch15/section3.md)
  - [15.4 群体涌现行为分析](./part5/ch15/section4.md)

- [第16章 自进化系统架构](./part5/ch16/_index.md)
  - [16.1 持续学习框架设计](./part5/ch16/section1.md)
  - [16.2 数字孪生与物理系统交互](./part5/ch16/section2.md)
  - [16.3 认知架构实现路径](./part5/ch16/section3.md)
  - [16.4 伦理约束机制设计](./part5/ch16/section4.md)

[附录](./appendix/_index.md)
[参考文献](./references.md)