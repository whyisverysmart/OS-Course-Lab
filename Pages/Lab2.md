# Lab 2：内存管理

本实验主要目的在于让同学们熟悉内核启动过程中对内存的初始化和内核启动后对物理内存和页表的管理，包括三个部分。

1. [物理内存管理](./Lab2/physical.html): 理解并完成伙伴系统以及SLAB系统
2. [虚拟页表管理](./Lab2/pte.html): 深入理解页表分配机制以及页表项权限机制，并完成页表分配函数。
3. [缺页异常处理](./Lab2/page_fault.html): 理解aarch64架构下的异常处理机制，并按照页表项的配置完成按需分配以及写时拷贝的缺页管理设置。

> [!WARNING]
> 本Lab不包括代码导读

跟先前的Lab相同，本实验代码包含了基础的 ChCore 操作系统镜像，除了练习题相关部分的源码以外（指明需要阅读的代码），其余部分通过二进制格式提供。
在正确完成本实验的练习题之后，你可以在树莓派3B+QEMU或开发板上进入 ChCore shell。