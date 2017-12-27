# java-concurrent-source
Java多并发编程从入门到精通源码


第一部分：线程并发基础  
  第1章  概念部分  
  1.1  CPU核心数、线程数  
  1.2  CPU时间片轮转机制  
  1.3  什么是进程和什么是线程  
  1.4  进程与线程比对  
  1.5  什么是并行运行  
  1.6  什么是并发运行  
  1.7  什么是吞吐量  
1.8  高并发编程的意义及其好处和注意事项
1.9  分布式、并行运算、并发运算
1.10  Linux和Windows对于并发采取的不同机制
第2章  认识Java里面的Thread
2.1  先来看一下线程的简单实现三种方法
2.2  Thread里面的属性和方法
2.3  关于线程的中断机制
2.4  线程的生命周期
2.5  什么是守护线程
2.6  线程组
2.7  当前线程副本：ThreadLocal
2.8  线程异常的处理
第3章  Thread安全
3.1  初识Java内存模型与多线程
3.2  什么是不安全？
3.3  什么是安全？
3.4  隐式锁，又称线程同步synchronized
3.5  显示锁Lock和ReentrantLock
3.6  显示锁ReadWriteLock和ReentrantRead WriteLock
3.7  显示锁StampedLock
3.8  什么是死锁
3.9  Java 关键字volatile修饰变量
3.10  原子操作：atomic
3.11  单利模式的写法
第4章  线程安全的集合类
4.1  java.util.Hashtable
4.2  java.util.concurrent.ConcurrentHashMap
4.3 java.util.concurrent.CopyOnWriteArrayList
4.4 java.util.concurrent.CopyOnWriteArraySet
4.5  CopyOnWrite机制介绍
4.6  Vector
4.7  常用的StringBuffer与StringBuilder
第二部分：线程并发晋级之高级部分
第5章  多线程之间交互：线程阀
5.1  阻塞队列BlockingQueue
5.2  数组阻塞队列ArrayBlockingQueue
5.3  链表阻塞队列LinkedBlockingQueue
5.4  优先级阻塞队列PriorityBlockingQueue
5.5  延时队列DelayQueue
5.6  同步队列SynchronousQueue
5.7  链表双向阻塞队列LinkedBlockingDeque
5.8  链表传输队列LinkedTransferQueue
5.9  同步计数器CountDownLatch
5.10  抽象队列化同步器AbstractQueued Synchronizer
5.11  同步计数器Semaphore
5.12  同步计数器CyclicBarrier
第6章  线程池
6.1  什么是线程池
6.2  newSingleThreadExecutor 的使用
6.3  newCachedThreadPool 的使用
6.4  newFixedThreadPool 的使用
6.5  线程池的好处
6.6  线程池的工作机制及其原理
6.7  自定义线程池与ExecutorService
6.8  线程池在工作中的错误使用
第7章  JDK7新增的Fork/Join
7.1  认识Future任务机制和FutureTask
7.2  什么是Fork/Join框架
7.3  认识Fork/Join的JDK里面的家族
7.4  Fork/Join框架的实现原理
7.5  异常处理机制和办法
7.6  Fork/Join 模式优缺点及其实际应用场景
第三部分：实际的使用与监控与拓展
第8章  线程，线程池在实际互联网 项目开发中的应用
8.1  Servlet线程的设计
8.2  线程池如何合理设计和配置
8.3  Tomcat中线程池如何合理设置
8.4  Nginx线程池
8.5  数据库连接池
8.6  如何在分布式系统中实现高并发
第9章  线程的监控及其日常工作 中如何分析
9.1  Java线程池的监控
9.2  ForkJoin如何监控
9.3  Java内存结构
9.4  可视化监控工具的使用
9.4.1  VisualVM 的使用
9.4.2  Jconsole的使用
9.4.3  Oracle Java Mission Control
9.5  Linux线程分析监控使用方法
9.6  Linux分析监控的运行脚本
9.7  Eclipse里面如何调试并发程序
9.8  如何通过压力测试来测试服务器的抗压能力
9.9  MultithreadedTC测试并发简单介绍
第10章  Android中线程的应用
10.1  Android进程基本知识
10.2  Android进程的生命周期
10.3  Android中Activity的生命周期
10.4  Android线程的运行机制
10.5  Android异步线程的处理方法
10.6  Android异步线程的原理与实现
附录1  JVM的参数
附录2  jstat的语法
附录3  jstat中一些术语的中文解释
附录4  Tomcat配置文件server.xml中Executor的参数
附录5  Thread的API
结 束 语
