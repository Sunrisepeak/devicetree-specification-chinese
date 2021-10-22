# devicetree-specification-chinese
设备树规格书中文版 v0.3

[English Version](https://github.com/devicetree-org/devicetree-specification)



#### 标题规范:

> h2 一级
>
> h4 二级
>
> h6 三级
>
> 例:
>
> ## 1 一级标题
>
> #### 1.1 二级标题
>
> ###### 1.1.1 三级标题







### 翻译

|          章节           |   翻译er    |
| :---------------------: | :---------: |
|  [ch01](./doc/ch01.md)  |    SPeak    |
|  [ch02](./doc/ch02.md)  |    SPeak    |
| [ch03](./doc/ch03.md) | invoker__qq |
| [ch04](./doc/ch04.md) | invoker__qq |
| [ch05](./doc/ch05.md) |  wil1jiang  |
| [ch06](./doc/ch06.md) |  wil1jiang  |



###  目录

##### 1.[前言](./doc/ch01.md)

> 1.1 目的和范围
>
> 1.2 IEEE^TM 1275 和 ePAPR 的关系
>
> 1.3 32bit 和 64bit 支持
>
> 1.4 术语说明

##### 2.[设备树](./doc/ch02.md)

> 2.1 概述
>
> 2.2 设备树结构和约束
>
> - 2.2.1 节点名
> - 2.2.2 推荐的通用命名
> - 2.2.3 路径名
> - 2.2.4 属性
>
> 2.3 标准属性
>
> - 2.3.1 compatible
> - 2.3.2 model
> - 2.3.3 phandle
> - 2.3.4 status
> - 2.3.5 #address-cells and #size-cells
> - 2.3.6 reg
> - 2.3.7 virtual-reg
> - 2.3.8 ranges
> - 2.3.9 dma-ranges
> - 2.3.10 name
> - 2.3.11 device_type
>
> 2.4 中断和中断映射
>
> - 2.4.1 中断发生器?属性
> - 2.4.2 中断控制器属性
> - 2.4.3 中断关联属性
> - 2.4.4 中断映射举例
>
> 2.5 关联节点和映射说明符
>
> - 2.5.1 关联节点属性
> - 2.5.2 映射说明符举例

##### 3.[设备节点规范](./doc/ch03.md)

> 3.1 基础设备节点类型
>
> 3.2 root 节点
>
> 3.3 /aliases 节点
>
> 3.4 /memory 节点
>
> 3.5 /chosen 节点
>
> 3.6 /cpus 节点属性
>
> 3.7 /cpus/cpu* 节点属性
>
> - 3.7.1 /cpus/cpu* 的通用属性
> - 3.7.2 TLB 属性
> - 3.7.3 内部缓存属性(L1)
>
> 3.8 多级共享 Cache 节点(/cpus/cpu*/1?-cache)

##### 4.[设备 bindings](./doc/ch04.md)

> 4.1 bindings 指南
>
> - 4.1.1 通用原则
> - 4.1.2 其他? 属性
>
> 4.2 串口设备
>
> - 4.2.1 串口约束?
> - 4.2.2 国际半导体 16450/16550 UART 兼容规范
>
> 4.3 网络设备
>
> - 4.3.1 网络类约束?
> - 4.3.2 以太网的特别考虑
>
> 4.4 Power ISA Open PIC 中断控制器
>
> 4.5 simple-bus 兼容

5.[扁平设备树(FBT)格式](./doc/ch05.md)

> 5.1 版本
>
> 5.2 格式头
>
> 5.3 内存保留块
>
> - 5.3.1 目的
> - 5.3.2 格式
>
> 5.4 块结构
>
> - 5.4.1 语法结构
> - 5.4.2 书结构
>
> 5.5 字符串块
>
> 5.6 对齐

##### 6.[设备树(DTS)格式(版本1)](./doc/ch06.md)

> 6.1 编译指令
>
> 6.2 标签
>
> 6.3 节点和属性定义
>
> 6.4 文件布局
