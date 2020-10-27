## Java 高阶
-------------------

#### 无锁化编程有哪些常见方法？
- [ ] `全都正确`
- [ ] `只有一个生产者和一个消费者，那么就可以做到免锁访问环形缓冲区（Ring Buffer）`
- [ ] `CAS (Compare-and-Swap)，如无锁栈，无锁队列等待`
- [ ] `RCU (Read-Copy-Update)，新旧副本切换机制，对于旧副本可以采用延迟释放的做法`

#### 一个线程在任何时刻都处于某种线程状态（thread state），例如运行状态、阻塞状态、就绪状态等。一个线程可以由选项中的哪种线程状态直接到达运行状态？
- [ ] `阻塞状态（对象 lock 池内）`
- [ ] `死亡状态`
- [ ] `就绪状态`
- [ ] `阻塞状态（对象 wait 池内）`

#### 随机文件访问是由（）类实现的？
- [ ] `RandomAccessFile`
- [ ] `File`
- [ ] `BufferedWriter`
- [ ] `BufferedInputStream`

#### 在 Java 多线程中，请用下面哪种方法不会使线程进入阻塞状态？
- [ ] `sleep()`
- [ ] `Suspend()`
- [ ] `yield()`
- [ ] `wait()`

#### 哪个选项能够构造一个 BufferedInputStream 流？
- [ ] `new BufferedInputStream(new File("in.txt"));`
- [ ] `new BufferedInputStream("in.txt");`
- [ ] `new BufferedInputStream(new FileInputStream("in.txt"));`
- [ ] `new BufferedInputStream(new VIHter("in.txt"));`