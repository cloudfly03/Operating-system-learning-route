# **操作系统学习路线，学完不一定考试能考100分，但是一定可以找到工作**

# 系统结构
## 内核态与用户态
[【linux】10分钟搞懂用户态与内核态_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV16J411p7f1/)

[用户态到内核态切换 - kk Blog —— 通用基础 (abcdxyzk.github.io)](https://abcdxyzk.github.io/blog/2015/06/02/kernel-sched-user-to-kernel/)

[14 用户态和内核态：用户态线程和内核态线程有什么区别？ (lianglianglee.com)](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E9%87%8D%E5%AD%A6%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-%E5%AE%8C/14%20%20%E7%94%A8%E6%88%B7%E6%80%81%E5%92%8C%E5%86%85%E6%A0%B8%E6%80%81%EF%BC%9A%E7%94%A8%E6%88%B7%E6%80%81%E7%BA%BF%E7%A8%8B%E5%92%8C%E5%86%85%E6%A0%B8%E6%80%81%E7%BA%BF%E7%A8%8B%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB%EF%BC%9F.md)

## 中断
[认认真真的聊聊中断](https://mp.weixin.qq.com/s/bTfeI5p4eO5j6I9edeV73g)

[认认真真的聊聊"软"中断](https://mp.weixin.qq.com/s/g9rGKRQofAlWjdq8lDTTkQ)

## 系统调用
[系统调用 | Liuye Notebook (liuyehcf.github.io)](https://liuyehcf.github.io/2017/08/20/%E7%B3%BB%E7%BB%9F%E8%B0%83%E7%94%A8/)

# 进程管理
## 进程与线程
[进程与线程的一个简单解释 - 阮一峰的网络日志 (ruanyifeng.com)](https://www.ruanyifeng.com/blog/2013/04/processes_and_threads.html)

[5.1 进程、线程基础知识 | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/4_process/process_base.html)

[17 进程和线程：进程的开销比线程大在了哪里？ (lianglianglee.com)](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E9%87%8D%E5%AD%A6%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-%E5%AE%8C/17%20%20%E8%BF%9B%E7%A8%8B%E5%92%8C%E7%BA%BF%E7%A8%8B%EF%BC%9A%E8%BF%9B%E7%A8%8B%E7%9A%84%E5%BC%80%E9%94%80%E6%AF%94%E7%BA%BF%E7%A8%8B%E5%A4%A7%E5%9C%A8%E4%BA%86%E5%93%AA%E9%87%8C%EF%BC%9F.md)

## 进程上下文切换
[进程上下文切换讲解_1](https://www.bilibili.com/video/BV1CV411v7NW/?spm_id_from=333.788.recommend_more_video.0&vd_source=1b73846804f44008716a3e40edd6b32d)

[进程上下文切换讲解_2](https://www.bilibili.com/video/BV12U4y1p7n3/?spm_id_from=333.788.recommend_more_video.0&vd_source=1b73846804f44008716a3e40edd6b32d)

[进程上下文切换讲解_3（总结）](https://www.bilibili.com/video/BV1GA411T7qU/?spm_id_from=333.788.recommend_more_video.0&vd_source=1b73846804f44008716a3e40edd6b32d)

[深入理解Linux内核进程上下文切换-腾讯云开发者社区-腾讯云 (tencent.com)](https://cloud.tencent.com/developer/article/1710837)

[上下文切换开销 · GitBook (hitzhangjie.pro)](https://www.hitzhangjie.pro/libmill-book/basics/context-switching-cost.html)

## 协程
[【协程第一话】协程到底是怎样的存在？_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1b5411b7SD/)

[大白话说协程 (qq.com)](https://mp.weixin.qq.com/s?__biz=MzUxODAzNDg4NQ==&mid=2247488003&idx=2&sn=cc32dee02330123d9f4081cefa531271&chksm=f98e56a9cef9dfbf1bb6b3a1e0f23ed07f37a541c9b0092d929049fcb67f1b80896575fa35ba&token=1339272147&lang=zh_CN#rd)

[从头到尾理解有栈协程实现原理 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/94018082)

[【后端开发必备知识】协程原理 函数栈_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1y3411u7Me/)

[一文读懂什么是进程、线程、协程-腾讯云开发者社区-腾讯云 (tencent.com)](https://cloud.tencent.com/developer/article/1546730)

## 进程间通信
[5.2 进程间有哪些通信方式？ | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/4_process/process_commu.html)

## 僵尸进程、孤儿进程、守护进程
[孤儿进程与僵尸进程[总结] - Rabbit_Dale - 博客园 (cnblogs.com)](https://www.cnblogs.com/anker/p/3271773.html)

[技术|什么是僵尸进程，如何找到并杀掉僵尸进程？ (linux.cn)](https://linux.cn/article-9143-1.html)

[Linux 之守护进程、僵死进程与孤儿进程 | LiuYongbin (liubigbin.github.io)](https://liubigbin.github.io/2016/03/11/Linux-%E4%B9%8B%E5%AE%88%E6%8A%A4%E8%BF%9B%E7%A8%8B%E3%80%81%E5%83%B5%E6%AD%BB%E8%BF%9B%E7%A8%8B%E4%B8%8E%E5%AD%A4%E5%84%BF%E8%BF%9B%E7%A8%8B/)

## 进程与线程调度算法
[14｜调度算法：操作系统中的进程是如何调度的？.md | Leon406资源站](http://121.43.36.222:5244/%E8%B5%84%E6%BA%90/14-%E6%9E%81%E5%AE%A2%E6%97%B6%E9%97%B4/%E4%B8%93%E6%A0%8F%E8%AF%BE/179%E4%B8%9A%E5%8A%A1%E5%BC%80%E5%8F%91%E7%AE%97%E6%B3%9550%E8%AE%B2/14%EF%BD%9C%E8%B0%83%E5%BA%A6%E7%AE%97%E6%B3%95%EF%BC%9A%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%AD%E7%9A%84%E8%BF%9B%E7%A8%8B%E6%98%AF%E5%A6%82%E4%BD%95%E8%B0%83%E5%BA%A6%E7%9A%84%EF%BC%9F.md)

[20 线程的调度：线程调度都有哪些方法？ (lianglianglee.com)](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E9%87%8D%E5%AD%A6%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-%E5%AE%8C/20%20%20%E7%BA%BF%E7%A8%8B%E7%9A%84%E8%B0%83%E5%BA%A6%EF%BC%9A%E7%BA%BF%E7%A8%8B%E8%B0%83%E5%BA%A6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95%EF%BC%9F.md)

## 多线程
[5.3 多线程冲突了怎么办？ | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/4_process/multithread_sync.html)

[18 锁、信号量和分布式锁：如何控制同一时间只有 2 个线程运行？ (lianglianglee.com)](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E9%87%8D%E5%AD%A6%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-%E5%AE%8C/18%20%20%E9%94%81%E3%80%81%E4%BF%A1%E5%8F%B7%E9%87%8F%E5%92%8C%E5%88%86%E5%B8%83%E5%BC%8F%E9%94%81%EF%BC%9A%E5%A6%82%E4%BD%95%E6%8E%A7%E5%88%B6%E5%90%8C%E4%B8%80%E6%97%B6%E9%97%B4%E5%8F%AA%E6%9C%89%202%20%E4%B8%AA%E7%BA%BF%E7%A8%8B%E8%BF%90%E8%A1%8C%EF%BC%9F.md)

[线程同步 | 爱编程的大丙 (subingwen.cn)](https://subingwen.cn/linux/thread-sync/)

[5.5 什么是悲观锁、乐观锁？ | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/4_process/pessim_and_optimi_lock.html)

[19 乐观锁、区块链：除了上锁还有哪些并发控制方法？ (lianglianglee.com)](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E9%87%8D%E5%AD%A6%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-%E5%AE%8C/19%20%20%E4%B9%90%E8%A7%82%E9%94%81%E3%80%81%E5%8C%BA%E5%9D%97%E9%93%BE%EF%BC%9A%E9%99%A4%E4%BA%86%E4%B8%8A%E9%94%81%E8%BF%98%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B6%E5%8F%91%E6%8E%A7%E5%88%B6%E6%96%B9%E6%B3%95%EF%BC%9F.md)

[5.4 怎么避免死锁？ | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/4_process/deadlock.html)

[计算机操作系统 - 死锁 | CS-Notes 面试笔记 (cyc2018.xyz)](https://cyc2018.xyz/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%20-%20%E6%AD%BB%E9%94%81.html#%E5%BF%85%E8%A6%81%E6%9D%A1%E4%BB%B6)

# 内存管理
## 虚拟内存
[4.1 为什么要有虚拟内存？ | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/3_memory/vmem.html#%E8%99%9A%E6%8B%9F%E5%86%85%E5%AD%98)

[24 虚拟内存 ：一个程序最多能使用多少内存？ (lianglianglee.com)](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E9%87%8D%E5%AD%A6%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-%E5%AE%8C/24%20%20%E8%99%9A%E6%8B%9F%E5%86%85%E5%AD%98%20%EF%BC%9A%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F%E6%9C%80%E5%A4%9A%E8%83%BD%E4%BD%BF%E7%94%A8%E5%A4%9A%E5%B0%91%E5%86%85%E5%AD%98%EF%BC%9F.md)

[4.4 在 4GB 物理内存的机器上，申请 8G 内存会怎么样？ | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/3_memory/alloc_mem.html)

## 内存回收
[4.3 内存满了，会发生什么？ | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/3_memory/mem_reclaim.html)

## 内存页面置换算法
[6.1 进程调度/页面置换/磁盘调度算法 | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/5_schedule/schedule.html#%E8%BF%9B%E7%A8%8B%E8%B0%83%E5%BA%A6%E7%AE%97%E6%B3%95)

[26 缓存置换算法： LRU 用什么数据结构实现更合理？ (lianglianglee.com)](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E9%87%8D%E5%AD%A6%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-%E5%AE%8C/26%20%20%E7%BC%93%E5%AD%98%E7%BD%AE%E6%8D%A2%E7%AE%97%E6%B3%95%EF%BC%9A%20LRU%20%E7%94%A8%E4%BB%80%E4%B9%88%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E5%AE%9E%E7%8E%B0%E6%9B%B4%E5%90%88%E7%90%86%EF%BC%9F.md)

## 写时复制
[linux-kernel - Linux 写时复制机制原理 - 个人文章 - SegmentFault 思否](https://segmentfault.com/a/1190000039869422)

## mmp
[Linux系统mmap内存映射机制原理_mmap 多进程读写流程-CSDN博客](https://blog.csdn.net/wmq880204/article/details/115163244)

[Linux 中 mmap() 函数的内存映射问题理解？ - 知乎 (zhihu.com)](https://www.zhihu.com/question/48161206)

[微信公众平台 (qq.com)](https://mp.weixin.qq.com/s/sLoiOevTxIonrgLa7yWJkw)

# 文件系统
## 预读失效和缓存污染
[4.5 如何避免预读失效和缓存污染的问题？ | 小林coding (xiaolincoding.com)](https://link.csdn.net/?target=https%3A%2F%2Fxiaolincoding.com%2Fos%2F3_memory%2Fcache_lru.html)

## Pachage
[7.2 进程写文件时，进程发生了崩溃，已写入的数据会丢失吗？ | 小林coding (xiaolincoding.com)](https://xiaolincoding.com/os/6_file_system/pagecache.html)

# I/O系统
## 零拷贝
[9.1 什么是零拷贝？ | 小林coding (xiaolincoding.com)](https://link.csdn.net/?target=https%3A%2F%2Fxiaolincoding.com%2Fos%2F8_network_system%2Fzero_copy.html)

## 五大I/O模型
[100%弄明白5种IO模型 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/115912936)

[​网络 IO 演变发展过程和模型介绍 (qq.com)](https://link.csdn.net/?target=https%3A%2F%2Fmp.weixin.qq.com%2Fs%2FEDzFOo3gcivOe_RgipkTkQ)

## I/O多路复用
[9.2 I/O 多路复用：select/poll/epoll | 小林coding (xiaolincoding.com)](https://link.csdn.net/?target=https%3A%2F%2Fxiaolincoding.com%2Fos%2F8_network_system%2Fselete_poll_epoll.html)

[你管这破玩意叫 IO 多路复用？-电子工程专辑 (eet-china.com)](https://link.csdn.net/?target=https%3A%2F%2Fwww.eet-china.com%2Fmp%2Fa93867.html)

[select - 彻底搞懂IO多路复用 - 个人文章 - SegmentFault 思否](https://link.csdn.net/?target=https%3A%2F%2Fsegmentfault.com%2Fa%2F1190000043369626)

[select poll epoll之间该如何决择 (cxd2014.github.io)](https://link.csdn.net/?target=https%3A%2F%2Fcxd2014.github.io%2F2018%2F01%2F10%2Fepoll%2F)

[Epoll在LT和ET模式下的读写方式 – 平凡的世界 (kimi.pub)](https://link.csdn.net/?target=https%3A%2F%2Fkimi.pub%2F515.html)

[Epoll之ET、LT模式 | 第七根弦的技术博客 (junzimu.com)](https://link.csdn.net/?target=https%3A%2F%2Flove.junzimu.com%2Farchives%2F2109)


## Reator网络模型
[9.3 高性能网络模式：Reactor 和 Proactor | 小林coding (xiaolincoding.com)](https://link.csdn.net/?target=https%3A%2F%2Fxiaolincoding.com%2Fos%2F8_network_system%2Freactor.html)

# Linux命令
## Linux目录结构
[29 Linux 下的各个目录有什么作用？ (lianglianglee.com)](https://link.csdn.net/?target=https%3A%2F%2Flearn.lianglianglee.com%2F%25E4%25B8%2593%25E6%25A0%258F%2F%25E9%2587%258D%25E5%25AD%25A6%25E6%2593%258D%25E4%25BD%259C%25E7%25B3%25BB%25E7%25BB%259F-%25E5%25AE%258C%2F29%2520%2520Linux%2520%25E4%25B8%258B%25E7%259A%2584%25E5%2590%2584%25E4%25B8%25AA%25E7%259B%25AE%25E5%25BD%2595%25E6%259C%2589%25E4%25BB%2580%25E4%25B9%2588%25E4%25BD%259C%25E7%2594%25A8%25EF%25BC%259F.md)

## 查看CPU、内存、进程、磁盘相关的命令
[微信公众平台 (qq.com)](https://link.csdn.net/?target=https%3A%2F%2Fmp.weixin.qq.com%2Fs%2FpgPCgnv3VrzpUtauz0okSg)

## CPU占用100%的场景
[技术|如何在 Linux 中找出 CPU 占用高的进程](https://link.csdn.net/?target=https%3A%2F%2Flinux.cn%2Farticle-11678-1.html)

[线上cpu使用率100%如何排查-腾讯云开发者社区-腾讯云 (tencent.com)](https://link.csdn.net/?target=https%3A%2F%2Fcloud.tencent.com%2Fdeveloper%2Farticle%2F2142464)
