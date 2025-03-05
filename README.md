# 小林 x 图解计算机基础

![](https://cdn.jsdelivr.net/gh/xiaolincoder/ImageHost4@main/网站封面.png)

👉 **点击**：[图解计算机基础在线阅读](docs/content/)

本站所有文章都是我[公众号：小林 coding](https://mp.weixin.qq.com/s/FYH1I8CRsuXDSybSGY_AFA)的原创文章，内容包含图解计算机网络、操作系统、计算机组成、数据库，共 1000 张图 + 50 万字，破除晦涩难懂的计算机基础知识，让天下没有难懂的八股文（口嗨一下，大家不要当真哈哈）！🚀

曾经我也苦恼于那些晦涩难弄的计算机基础知识，但在我啃了一本又一本的书，看了一个又一个的视频后，终于对这些“家伙”有了认识。我想着，这世界上肯定有一些朋友也跟我有一样的苦恼，为此下决心，用图解 + 通熟易懂的讲解来帮助大家理解，利用工作之余，坚持输出图解文章两年之久，这才有了今天的网站！



## :open_book:《图解网络》
- **介绍**:point_down:：
  - [图解网络介绍](docs/content/network/)
- **网络基础篇** :point_down:
  - [TCP/IP 网络模型有哪几层？](docs/content/network/1_base/tcp_ip_model) 
  - [键入网址到网页显示，期间发生了什么？](docs/content/network/1_base/what_happen_url) 
  - [Linux 系统是如何收发网络包的？](docs/content/network/1_base/how_os_deal_network_package) 
- **HTTP 篇** :point_down:
  - [HTTP 常见面试题](docs/content/network/2_http/http_interview) 
  - [HTTP/1.1 如何优化？](docs/content/network/2_http/http_optimize) 
  - [HTTPS RSA 握手解析](docs/content/network/2_http/https_rsa) 
  - [HTTPS ECDHE 握手解析](docs/content/network/2_http/https_ecdhe) 
  - [HTTPS 如何优化？](docs/content/network/2_http/https_optimize) 
  - [HTTP/2 牛逼在哪？](docs/content/network/2_http/http2) 
  - [HTTP/3 强势来袭](docs/content/network/2_http/http3) 
  - [既然有 HTTP 协议，为什么还要有 RPC？](docs/content/network/2_http/http_rpc) 
  - [既然有 HTTP 协议，为什么还要有 WebSocket？](docs/content/network/2_http/http_websocket) 
- **TCP 篇** :point_down:
  - [TCP 三次握手与四次挥手面试题](docs/content/network/3_tcp/tcp_interview) 
  - [TCP 重传、滑动窗口、流量控制、拥塞控制](docs/content/network/3_tcp/tcp_feature) 
  - [TCP 实战抓包分析](docs/content/network/3_tcp/tcp_tcpdump) 
  - [TCP 半连接队列和全连接队列](docs/content/network/3_tcp/tcp_queue) 
  - [如何优化 TCP?](docs/content/network/3_tcp/tcp_optimize) 
  - [如何理解是 TCP 面向字节流协议？](docs/content/network/3_tcp/tcp_stream) 
  - [为什么 TCP 每次建立连接时，初始化序列号都要不一样呢？](docs/content/network/3_tcp/isn_deff) 
  - [SYN 报文什么时候情况下会被丢弃？](docs/content/network/3_tcp/syn_drop) 
  - [四次挥手中收到乱序的 FIN 包会如何处理？](docs/content/network/3_tcp/out_of_order_fin) 
  - [在 TIME_WAIT 状态的 TCP 连接，收到 SYN 后会发生什么？](docs/content/network/3_tcp/time_wait_recv_syn) 
  - [TCP 连接，一端断电和进程崩溃有什么区别？](docs/content/network/3_tcp/tcp_down_and_crash) 
  - [拔掉网线后，原本的 TCP 连接还存在吗？](docs/content/network/3_tcp/tcp_unplug_the_network_cable) 
  - [tcp_tw_reuse 为什么默认是关闭的？](docs/content/network/3_tcp/tcp_tw_reuse_close) 
  - [HTTPS 中 TLS 和 TCP 能同时握手吗？](docs/content/network/3_tcp/tcp_tls) 
  - [TCP Keepalive 和 HTTP Keep-Alive 是一个东西吗？](docs/content/network/3_tcp/tcp_http_keepalive) 
  - [TCP 协议有什么缺陷？](docs/content/network/3_tcp/tcp_problem)
  - [如何基于 UDP 协议实现可靠传输？](docs/content/network/3_tcp/quic)
  - [TCP 和 UDP 可以使用同一个端口吗？](docs/content/network/3_tcp/port)
  - [服务端没有 listen，客户端发起连接建立，会发生什么？](docs/content/network/3_tcp/tcp_no_listen)
  - [没有 accept，可以建立 TCP 连接吗？](docs/content/network/3_tcp/tcp_no_accpet) 
  - [用了 TCP 协议，数据一定不会丢吗？](docs/content/network/3_tcp/tcp_drop)
  - [TCP 四次挥手，可以变成三次吗？](docs/content/network/3_tcp/tcp_three_fin)
  - [TCP 序列号和确认号是如何变化的？](docs/content/network/3_tcp/tcp_seq_ack)
- **IP 篇** :point_down:
  - [IP 基础知识全家桶](docs/content/network/4_ip/ip_base) 	
  - [ping 的工作原理](docs/content/network/4_ip/ping) 	
  - [断网了，还能 ping 通 127.0.0.1 吗？](docs/content/network/4_ip/ping_lo)
- **学习心得** :point_down:
  - [计算机网络怎么学？](docs/content/network/5_learn/learn_network) 	
  - [画图经验分享](docs/content/network/5_learn/draw) 	

## :open_book:《图解系统》
- **介绍**:point_down:：
  - [图解系统介绍](docs/content/os/)
- **硬件结构** :point_down:
  - [CPU 是如何执行程序的？](docs/content/os/1_hardware/how_cpu_run) 
  - [磁盘比内存慢几万倍？](docs/content/os/1_hardware/storage) 
  - [如何写出让 CPU 跑得更快的代码？](docs/content/os/1_hardware/how_to_make_cpu_run_faster) 
  - [CPU 缓存一致性](docs/content/os/1_hardware/cpu_mesi) 
  - [CPU 是如何执行任务的？](docs/content/os/1_hardware/how_cpu_deal_task) 
  - [什么是软中断？](docs/content/os/1_hardware/soft_interrupt) 
  - [为什么 0.1 + 0.2 不等于 0.3？](docs/content/os/1_hardware/float) 
- **操作系统结构** :point_down:
  - [Linux 内核 vs Windows 内核](docs/content/os/2_os_structure/linux_vs_windows) 
- **内存管理** :point_down:
  - [为什么要有虚拟内存？](docs/content/os/3_memory/vmem) 
  - [malloc 是如何分配内存的？](docs/content/os/3_memory/malloc)
  - [内存满了，会发生什么？](docs/content/os/3_memory/mem_reclaim)
  - [在 4GB 物理内存的机器上，申请 8G 内存会怎么样？](docs/content/os/3_memory/alloc_mem)
  - [如何避免预读失效和缓存污染的问题？](docs/content/os/3_memory/cache_lru)
  - [深入理解 Linux 虚拟内存管理](docs/content/os/3_memory/linux_mem)
  - [深入理解 Linux 物理内存管理](docs/content/os/3_memory/linux_mem2)
- **进程管理** :point_down:
  - [进程、线程基础知识](docs/content/os/4_process/process_base) 
  - [进程间有哪些通信方式？](docs/content/os/4_process/process_commu) 
  - [多线程冲突了怎么办？](docs/content/os/4_process/multithread_sync) 
  - [怎么避免死锁？](docs/content/os/4_process/deadlock) 
  - [什么是悲观锁、乐观锁？](docs/content/os/4_process/pessim_and_optimi_lock) 
  - [一个进程最多可以创建多少个线程？](docs/content/os/4_process/create_thread_max) 
  - [线程崩溃了，进程也会崩溃吗？](docs/content/os/4_process/thread_crash)
- **调度算法** :point_down:
  - [进程调度/页面置换/磁盘调度算法](docs/content/os/5_schedule/schedule)
- **文件系统** :point_down:
  - [文件系统全家桶](docs/content/os/6_file_system/file_system) 	
  - [进程写文件时，进程发生了崩溃，已写入的数据会丢失吗？](docs/content/os/6_file_system/pagecache)
- **设备管理** :point_down:
  - [键盘敲入 A 字母时，操作系统期间发生了什么？](docs/content/os/7_device/device) 
- **网络系统** :point_down:
  - [什么是零拷贝？](docs/content/os/8_network_system/zero_copy) 
  - [I/O 多路复用：select/poll/epoll](docs/content/os/8_network_system/selete_poll_epoll) 
  - [高性能网络模式：Reactor 和 Proactor](docs/content/os/8_network_system/reactor) 
  - [什么是一致性哈希？](docs/content/os/8_network_system/hash) 
- **学习心得** :point_down:
  - [如何查看网络的性能指标？](docs/content/os/9_linux_chtml/linux_network) 	
  - [画图经验分享](docs/content/os/9_linux_chtml/pv_uv) 	
- **学习心得** :point_down:
  - [计算机网络怎么学？](docs/content/os/10_learn/learn_os) 	
  - [画图经验分享](docs/content/os/10_learn/draw) 

## :open_book:《图解 MySQL》
- **介绍**:point_down:：
  - [图解 MySQL 介绍](docs/content/mysql/)
- **基础篇**:point_down:：
  - [执行一条 select 语句，期间发生了什么？](docs/content/mysql/base/how_select)
  - [MySQL 一行记录是怎么存储的？](docs/content/mysql/base/row_format)
- **索引篇** :point_down:
  - [索引常见面试题](docs/content/mysql/index/index_interview)
  - [从数据页的角度看 B+ 树](docs/content/mysql/index/page)
  - [为什么 MySQL 采用 B+ 树作为索引？](docs/content/mysql/index/why_index_chose_bpuls_tree)
  - [MySQL 单表不要超过 2000W 行，靠谱吗？](docs/content/mysql/index/2000w)
  - [索引失效有哪些？](docs/content/mysql/index/index_lose)
  - [MySQL 使用 like“%x“，索引一定会失效吗？](docs/content/mysql/index/index_issue)
  - [count(\*) 和 count(1) 有什么区别？哪个性能最好？](docs/content/mysql/index/count)
- **事务篇** :point_down:
  - [事务隔离级别是怎么实现的？](docs/content/mysql/transaction/mvcc)
  - [MySQL 可重复读隔离级别，完全解决幻读了吗？](docs/content/mysql/transaction/phantom) 		
- **锁篇** :point_down:
  - [MySQL 有哪些锁？](docs/content/mysql/lock/mysql_lock) 	
  - [MySQL 是怎么加锁的？](docs/content/mysql/lock/how_to_lock) 	
  - [update 没加索引会锁全表](docs/content/mysql/lock/update_index) 	
  - [MySQL 死锁了，怎么办？](docs/content/mysql/lock/deadlock) 
  - [字节面试：加了什么锁，导致死锁的？](docs/content/mysql/lock/show_lock)
- **日志篇** :point_down:
  - [MySQL 日志：undo log、redo log、binlog 有什么用？](docs/content/mysql/log/how_update)
- **内存篇** :point_down:
  - [揭开 Buffer Pool 的面纱](docs/content/mysql/buffer_pool/buffer_pool) 	

##  :open_book: 《图解 Redis》

- **面试篇** :point_down:
   - [Redis 常见面试题](docs/content/redis/base/redis_interview)
- **数据类型篇** :point_down:
   - [Redis 数据类型和应用场景](docs/content/redis/data_struct/command)
   - [图解 Redis 数据结构](docs/content/redis/data_struct/data_struct)
- **持久化篇** :point_down:
  - [AOF 持久化是怎么实现的？](docs/content/redis/storage/aof) 	
  - [RDB 快照是怎么实现的？](docs/content/redis/storage/rdb) 
- **功能篇**:point_down:
   - [Redis 过期删除策略和内存淘汰策略有什么区别？](docs/content/redis/module/strategy) 
- **高可用篇** :point_down:
   - [主从复制是怎么实现的？](docs/content/redis/cluster/master_slave_replication) 	
   - [为什么要有哨兵？](docs/content/redis/cluster/sentinel)
- **缓存篇** :point_down:
   - [什么是缓存雪崩、击穿、穿透？](docs/content/redis/cluster/cache_problem) 	
   - [数据库和缓存如何保证一致性？](docs/content/redis/architecture/mysql_redis_consistency) 


## :muscle: 学习心得

- [计算机基础学习路线](docs/content/cs_learn/) ：计算机基础学习书籍 + 视频推荐，全面且清晰。
- [互联网校招心得](docs/content/reader_nb/) ：小林神仙读者们的校招和学习心得，值得学习。

##  :books:  图解系列 PDF 下载

- [图解网络 + 图解系统 PDF 下载](https://mp.weixin.qq.com/s/02036z-FMOCLpZ_otwMwBg)

## 勘误及提问
如果有疑问或者发现错误，可以在相应的 Issues 进行提问或勘误，也可以在[图解计算机基础网站](docs/content/)对应的文章底部留言。

如果喜欢或者有所启发，欢迎 Star，对作者也是一种鼓励。


## 公众号


最新的图解文章都在公众号首发，强烈推荐关注！如果你想加入百人技术交流群，扫码下方二维码回复「加群」。

![](https://cdn.jsdelivr.net/gh/xiaolincoder/ImageHost3@main/其他/公众号介绍.png)

 
