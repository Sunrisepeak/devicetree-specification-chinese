# devicetree-specification-chinese
设备树规格书中文版 v0.3

[English Version](https://github.com/devicetree-org/devicetree-specification)

> 第一遍粗翻中

###  目录

##### 1.[前言](./doc/ch01.md)

> 1.1 [目的和范围](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch01.md#11%E7%9B%AE%E7%9A%84%E5%92%8C%E5%BA%94%E7%94%A8)
>
> 1.2 [IEEE^TM 1275 和 ePAPR 的关系](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch01.md#12-ieeetm-1275-%E5%92%8C-epapr%E7%9A%84%E5%85%B3%E7%B3%BB)
>
> 1.3 [32bit 和 64bit 支持](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch01.md#13-3264%E4%BD%8D%E6%94%AF%E6%8C%81)
>
> 1.4 [术语说明](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch01.md#14-%E6%9C%AF%E8%AF%AD%E8%AF%B4%E6%98%8E)

##### 2.[设备树](./doc/ch02.md)

> 2.1 [概述](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#21%E6%A6%82%E8%BF%B0)
>
> 2.2 [设备树结构与其规范](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#22-%E8%AE%BE%E5%A4%87%E6%A0%91%E7%BB%93%E6%9E%84%E4%B8%8E%E5%85%B6%E8%A7%84%E8%8C%83)
>
> - 2.2.1 [结点名](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#221-%E7%BB%93%E7%82%B9%E5%90%8D)
> - 2.2.2 [推荐的通用命名](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#222-%E6%8E%A8%E8%8D%90%E7%9A%84%E9%80%9A%E7%94%A8%E5%91%BD%E5%90%8D)
> - 2.2.3 [路径名](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#223-%E8%B7%AF%E5%BE%84%E5%90%8D)
> - 2.2.4 [属性](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#224-%E5%B1%9E%E6%80%A7)
>
> 2.3 [标准属性](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#23-%E6%A0%87%E5%87%86%E5%B1%9E%E6%80%A7)
>
> - 2.3.1 [compatible](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#231-compatible)
> - 2.3.2 [model](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#232-model)
> - 2.3.3 [phandle](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch02.md#233-phandle)
> - 2.3.4 [status](https://github.com/Sunrisepeak/devicetree-specification-chinese/blob/main/doc/ch02.md#224-status)
> - 2.3.5 [#address-cells and #size-cells](https://github.com/Sunrisepeak/devicetree-specification-chinese/blob/main/doc/ch02.md#225-address-cells-%E5%92%8C-size-cells)
> - 2.3.6 [reg](https://github.com/Sunrisepeak/devicetree-specification-chinese/blob/main/doc/ch02.md#226-reg)
> - 2.3.7 [virtual-reg](doc/ch02.md)
> - 2.3.8 [ranges](doc/ch02.md)
> - 2.3.9 [dma-ranges]()
> - 2.3.10 [name]()
> - 2.3.11 [device_type]()
>
> 2.4 [中断和中断映射](./doc/ch02.md)
>
> - 2.4.1 [中断发生器属性]()
> - 2.4.2 [中断控制器属性]()
> - 2.4.3 [中断级联属性]()
> - 2.4.4 [中断映射举例]()
>
> 2.5 [级联节点和映射说明符](./doc/ch02.md)
>
> - 2.5.1 [关联节点属性](doc/ch02.md)
> - 2.5.2 [映射说明符举例](https://github.com/Sunrisepeak/devicetree-specification-chinese/blob/main/doc/ch02.md#25-级联节点和描述符映射)

##### 3.[设备节点规范](./doc/ch03.md)

> 3.1 [基础设备节点类型](doc/ch03.md)
>
> 3.2 [root 节点](doc/ch03.md)
>
> 3.3 [/aliases 节点](doc/ch03.md)
>
> 3.4 [/memory 节点](doc/ch03.md)
>
> 3.5 [/chosen 节点](doc/ch03.md)
>
> 3.6 [/cpus 节点属性](doc/ch03.md)
>
> 3.7 [/cpus/cpu* 节点属性](doc/ch03.md)
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

> 5.1 [版本](https://github.com/UnknownBugs/devicetree-specification-chinese/blob/main/doc/ch05.md#51-%E7%89%88%E6%9C%AC%E6%8E%A7%E5%88%B6)
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
