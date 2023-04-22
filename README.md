# devicetree-specification-chinese

设备树规格书  中文版 (第一遍粗翻中)

[English Version](https://github.com/devicetree-org/devicetree-specification)

---

#### 别名(For Index)

> 设备树规格书 中文版
>
> 设备树规范 中文版
>
> 设备树文档 中文版
>
> DTS文档 中文版

###  目录

##### 1.[前言](./doc/ch01.md)

> 1.1 [目的和应用](doc/ch01.md#11目的和应用)
>
> 1.2 [IEEE^TM 1275 和 ePAPR 的关系](doc/ch01.md#12-ieeetm-1275-和-epapr的关系)
>
> 1.3 [32bit 和 64bit 支持](doc/ch01.md#13-3264位支持)
>
> 1.4 [术语说明](doc/ch01.md#14-术语说明)

##### 2.[设备树](./doc/ch02.md)

> 2.1 [概述](doc/ch02.md#21概述)
>
> 2.2 [设备树结构与其规范](doc/ch02.md#22-设备树结构与其规范)
>
> - 2.2.1 [结点名](doc/ch02.md#221-结点名)
> - 2.2.2 [推荐的通用命名](doc/ch02.md#222-推荐的通用命名)
> - 2.2.3 [路径名](doc/ch02.md#223-路径名)
> - 2.2.4 [属性](doc/ch02.md#224-属性)
>
> 2.3 [标准属性](doc/ch02.md#23-标准属性)
>
> - 2.3.1 [compatible](doc/ch02.md#231-compatible)
> - 2.3.2 [model](doc/ch02.md#232-model)
> - 2.3.3 [phandle](doc/ch02.md#233-phandle)
> - 2.3.4 [status](doc/ch02.md#224-status)
> - 2.3.5 [#address-cells and #size-cells](doc/ch02.md#225-address-cells-和-size-cells)
> - 2.3.6 [reg](doc/ch02.md#226-reg)
> - 2.3.7 [virtual-reg](ch02.md#237-virtual-reg)
> - 2.3.8 [ranges](doc/ch02.md#238-ranges)
> - 2.3.9 [dma-ranges](ch02.md#239-dma-ranges)
> - 2.3.10 [name](doc/ch02.md#2310-name-弃用)
> - 2.3.11 [device_type](doc/ch02.md#2310-name-弃用)
>
> 2.4 [中断和中断映射](doc/ch02.md#24-中断和中断映射)
>
> - 2.4.1 [中断发生器属性](doc/ch02.md#241-中断生成设备的属性)
> - 2.4.2 [中断控制器属性](doc/ch02.md#242-中断控制器属性)
> - 2.4.3 [中断级联属性](doc/ch02.md#243-中断级联属性)
> - 2.4.4 [中断映射举例](doc/ch02.md#244-中断映射举例)
>
> 2.5 [级联节点和映射说明符](doc/ch02.md#25-级联节点和描述符映射)
>
> - 2.5.1 [关联节点属性](doc/ch02.md#251-级联节点属性)
> - 2.5.2 [映射说明符举例](doc/ch02.md#25-级联节点和描述符映射)

##### 3.[设备节点规范](./doc/ch03.md)

> 3.1 [基础设备节点类型](doc/ch03.md#31-基础设备节点类型)
>
> 3.2 [root 节点](doc/ch03.md#32-根节点-root)
>
> 3.3 [/aliases 节点](doc/ch03.md#33-aliases-节点)
>
> 3.4 [/memory 节点](doc/ch03.md#34-memory节点)
>
> 3.5 [/chosen 节点](doc/ch03.md#35-chosen-节点)
>
> 3.6 [/cpus 节点属性](doc/ch03.md#37-cpuscpu-节点属性)
>
> 3.7 [/cpus/cpu* 节点属性](doc/ch03.md#37-cpuscpu-节点属性)
>
> - 3.7.1 [/cpus/cpu* 的通用属性](doc/ch03.md#371-cpuscpu-节点的通用属性)
> - 3.7.2 TLB 属性
> - 3.7.3 内部缓存属性(L1)
>
> 3.8 多级共享 Cache 节点(/cpus/cpu*/1?-cache)

##### 4.[设备绑定(bindings)](./doc/ch04.md)

> 4.1 [bindings 指南](doc/ch04.md#41-绑定指南)
>
> - 4.1.1 [一般原则](doc/ch04.md#411-一般原则)
> - 4.1.2 [其他(杂项)属性](doc/ch04.md#412-杂项属性)
>
> 4.2 [串行设备](doc/ch04.md#42-串行设备)
>
> - 4.2.1 [串行设备类绑定](doc/ch04.md#421-串行设备类绑定)
> - 4.2.2 [国际半导体 16450/16550 UART 兼容规范](doc/ch04.md#422-national-semiconductor-1645016550-兼容-uart-要求)
>
> 4.3 [网络设备](doc/ch04.md#43-网络设备)
>
> - 4.3.1 [网络类绑定](doc/ch04.md#431-网络类绑定)
> - 4.3.2 [以太网特殊考虑事项](doc/ch04.md#432-以太网特定考虑事项)
>
> 4.4 [Power ISA Open PIC 中断控制器](doc/ch04.md#44-power-isa-open-pic中断控制器)
>
> 4.5 [simple-bus 兼容](doc/ch04.md#45-simple-bus兼容节点属性)

5.[扁平设备树(FBT)格式](./doc/ch05.md)

> 5.1 [版本](doc/ch05.md#51-版本控制)
>
> 5.2 [格式头](doc/ch05.md#52-头部)
>
> 5.3 [内存保留块](doc/ch05.md#53-内存保留块)
>
> - 5.3.1 [目的](doc/ch05.md#531-目的)
> - 5.3.2 [格式](doc/ch05.md#532-format)
>
> 5.4 [块结构](doc/ch05.md#54-结构块)
>
> - 5.4.1 [语法结构](doc/ch05.md#541-词法结构)
> - 5.4.2 [树结构](doc/ch05.md#542-树结构)
>
> 5.5 [字符串块](doc/ch05.md#55-字符串块)
>
> 5.6 [对齐](doc/ch05.md#56-对齐)

##### 6.[设备树(DTS)格式(版本1)](./doc/ch06.md)

> 6.1 [编译指令](doc/ch06.md#61-编译器指令)
>
> 6.2 [标签](doc/ch06.md#62-标签)
>
> 6.3 [节点和属性定义](doc/ch06.md#63-节点和属性定义)
>
> 6.4 [文件布局](doc/ch06.md#64-文件布局)