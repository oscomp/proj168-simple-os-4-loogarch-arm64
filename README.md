# 168-simple-os-4-loogarch-arm64

Loogarch/ARM64平台上的教学操作系统

## 自研简单操作系统的构建与测试验证

### 标题

自研简单操作系统的构建与测试验证

### 项目描述

基于特定计算机指令集及体系架构【鼓励基于LoongArch架构、或者鲲鹏处理器指令集系统及ARM64体系架构】，研究操作系统内核的设计方法技术及交叉编译手段，完成白手起家式（可以仿照现有内核但不能完全照搬照抄）简单操作系统内核（至少包括计算机系统启动引导过程及内核进程管理机制）及命令接口的设计与构建，并在本地虚拟机（VMware或QEMU等）开展必要的测试验证。如果能够基于实体机或开发板实现测试验证，则更好。

### 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 每位参赛学生只能参加一支参赛队，不可重复报名
* 每个参赛团队最多两位指导老师
* 2022年5月30日前可调整一名参赛队员，5月30日后只能减少参赛队员，不能更换或增加。
* 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

	翟高寿

* Email  [gszhai@bjtu.edu.cn](mailto:gszhai@bjtu.edu.cn)
* githubid  gsZhongHuaXiaoZi

### 难度

中等到高难等级

### 特征

* LoongArc或ARM64或MIPS或x86或riscv或...

### License

* GPL3

### 预期目标

* 调研目标系统指令集体系架构，特别是处理器特权指令、中断机制、内存管理支撑机制等；
* 搭建编译开发环境，熟悉编程语言（C、汇编、Rust等）及调试技巧，包括虚拟机内核开发调试技巧；
* 研究计算机系统启动引导过程，设计开发引导程序，支持操作系统内核的装入和初始化；
* 研究和设计内存管理方法，实现基本的内存及进程管理机制；
* 研究和设计最基本的系统调用及一组系统内部命令，完成系统调用机制及有关系统调用和命令解释器的实现；
* 本地虚拟机（VMware或QEMU等）开展原型系统有关功能的测试验证。鼓励基于实体机或开发板实现测试验证。

### 参考资源

1）QEMU模拟器 可以在PC上模拟运行LoongArch架构的操作系统

[https://github.com/yangxiaojuan-loongson/qemu/blob/tcg-dev/target/loongarch/README](https://github.com/yangxiaojuan-loongson/qemu/blob/tcg-dev/target/loongarch/README)

2）关于LoongArch架构的工具链及文档

[https://github.com/loongson](https://github.com/loongson)

3）ARM体系架构参考手册

Arm Architecture Reference Manual Armv8, for Armv8-A architecture profile. [https://developer.arm.com/documentation/ddi0487/fc.2020.](https://developer.arm.com/documentation/ddi0487/fc.2020.)

4）x86体系架构可选用NASM汇编器和C或Rust进行开发

5）UEFI固件参考资料（维基百科）：Unified Extensible Firmware Interface. [https://en.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface.](https://en.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface.) 2020.

6）Linux内核源码. [https://www.kernel.org/](https://www.kernel.org/)

