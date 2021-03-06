# 关于学习C语言的一些方法论
## 明白C语言的重要性
**1. 首先，就计算机初学者而言，C语言能够让你和操作系统、底层硬件走得更近。**
 * 学习C语言时，你不得不去了解一些内存管理，系统调用等相对底层的知识，而这些同样是操作系统和计算机组成原理课程的重要知识
 * C语言所见即所得，你可以知道一行C代码背后，CPU，内存等发生了哪些事情，而python等高级语言则不可能。理解自己写的代码，是写出好的代码的前提。

**2. 其次，就应用领域而言，C语言多用于高性能领域，或资源紧张的嵌入式设备领域**
 * 如linux内核，作为公司服务器操作系统的主流，高性能是最基本要求
 * web服务器nginx以及redis（remote dictionary service），单台服务器每秒能够处理数十万的并发请求
 * 一些移动智能设备，可能内存很少，只有几十KB，需要C语言直接管理内存的能力。

**3. 最后，考研要考**

## 知晓C语言的缺点和难点
**1. 开发效率** C语言是一门相对底层的语言，比起python，java更高级的语言，在开发效率上没有优势。在对性能要求不高的场景，选择其它语言，能够快速完成开发，快速验证你的设计方案的有效性，缩短整个项目周期。

**2. 难** C语言虽然语法简单，要学会并不难，但要学好，非常不容易。这就相当于只会用C语言写学生管理系统的人 和 用C开发linux内核的人的差别。内存管理、系统调用、指针三块内容，是很多人学习使用C语言的三座大山，但其实这些知识穿插在操作系统、计算机组成原理课程的学习中，学好了这两门课，对这三块内容会有一个更加深入的理解。

**3. 容易错** 这里主要是指内存和指针错，C/C++程序员最常碰到的词汇：空指针，内存泄漏，段错误，都与这有关。

## 学好C语言，要做些什么？
**1. 学习语法** 第一阶段，当然是学习C语言本身的基本语法和使用，能够快速编写一些简单的小程序。这个阶段相对简单，主要方法是学习课本知识，每天完成几道编程练习。

**2. 数据结构和算法** 数据结构和算法是程序的灵魂，也是考研408的基础，除课本，公开课，考研题集外，还会有三项附加任务：
 * **数据结构编程项目** 自己实现一遍所学的数据结构，对理解数据结构原理和过程至关重要。
 * **案例学习** 主要来自于linux内核，redis 和 nginx三个顶级项目的数据结构实现，知道数据结构在工业界的应用，在哪些场景下用。学习别人的优秀代码，也是很重要的能力和学习途径。
 * **附加主题** 来自于数据结构课程外的补充内容，比如函数的渐进增长。

**3. leetcode** 在数据结构学习一段时间后，到专题刷题前，会有一些leetcode上面的编程练习，对于理解基础数据结构很有帮助。另外，由于复试有上机编程考试，在初试结束后，还需要用它做大量编程练习。

**4. 回顾** 简单说，在学习C语言阶段无法深入理解的内容，比如内存原理，系统调用等，在学了操作系统和组成原理的同时，会定期回顾，知其然并知其所以然。

## 遇到困难怎么办？
**1. 借助搜索引擎** 你遇到的很多问题，肯定有很多人遇到过，并且大概率有人在搜索引擎上搜索过。常用的比如CSDN等技术博客，stackoverflow等

**2. 看书** 比如数据结构，你需要看懂原理，甚至是对着标准实现去理解，然后再去自己实现它

**3. 问我** 我应该也能解决你一部分问题

**4. 最重要的是，不要放弃！**
