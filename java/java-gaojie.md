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

#### 下面哪个基于 Unicode 字符的输出流？
- [ ] `OutputStream`
- [ ] `Reader`
- [ ] `InputStream`
- [ ] `Writer`

#### 下面哪一个不属于多线程相较于多进程的特点？
- [ ] `线程间的通信和切换成本较低`
- [ ] `基于线程应用所需的开锁较小`
- [ ] `线程可以并行`
- [ ] `线程共享进程的地址空间`

#### 下面关于 ServerSocket 的描述错误的是？
- [ ] `ServerSocket 表示服务器的倾听 Socket，等待客户机发起 TCP 连接`
- [ ] `ServerSocket 通过 accept() 方法监听等待客户端的请求，未收到客户端的连接请求之前当前线程处于阻塞状态`
- [ ] `一个 ServerSocket 只能在一个端口监听，因此一个 ServerSocket 只能接收到一个客户端请求`
- [ ] `ServerSocket 仅用于监听客户端的发起的连接请求，一旦受到客户端请求即返回一个 Socket 于客户端通信。ServerSocket 并不负责与客户单通信`

#### 下面的哪个关键词和方法不是线程同步所需要的？
- [ ] `notify()`
- [ ] `wait()`
- [ ] `synchronized`
- [ ] `sleep()`

#### （）描述了该 Java 语句 `File f = new File("d:\src\Hello.txt");` 中出现的错误？
- [ ] `文件类表示的是目录而不是文件`
- [ ] `文件类的构造方法不需要参数`
- [ ] `文件类的构造方法的参数不能是字符串`
- [ ] `文件类的构造方法的字符串参数必须有转义`

#### 通过 ObjectInputStream 的 readObject() 方法读取数据，如何判断流结尾？
- [ ] `返回 null 表示流结尾`
- [ ] `遇到流结尾将抛出异常`
- [ ] `返回 2 表示流结尾`
- [ ] `返回 -1 表示流结尾`

#### 关于 RandomAccessFile 类的说法正确的是？
- [ ] `RandomAccessFile 类对象可读写 Java 原始类型数据`
- [ ] `RandomAccessFile 类继承自 File 类`
- [ ] `RandomAccessFile 类对象只能从文件读 Java 原始类型数据`
- [ ] `随机读写流的指针所计算的是字符的个数`

#### 在 Java 中关于 File 类的说法正确的是？
- [ ] `File 表示文件路径和文件内容`
- [ ] `File 表示路径`
- [ ] `File 表示文件，不能表示文件夹`
- [ ] `通过 File 不能删除文件`

#### 当线程调用 start() 后，其所处状态为？
- [ ] `新建状态`
- [ ] `就绪状态`
- [ ] `阻塞状态`
- [ ] `运行状态`

#### 下列哪些语句关于 Java 内存回收的说明是正确的？
- [ ] `内存回收程序可以在指定的时间释放内存对象`
- [ ] `内存回收程序允许程序员直接释放内存`
- [ ] `内存回收程序负责释放无用内存`
- [ ] `程序员必须创建一个线程来释放内存`

#### 下面所述步骤中，是创建进程做必须的步骤是？
- [ ] `全部不对`
- [ ] `建立一个进程控制块`
- [ ] `为进程分配文件描述符`
- [ ] `由调度程序为进程分配 CPU`

#### （）方法表示获取一个字节数据？
- [ ] `flush()`
- [ ] `read()`
- [ ] `write()`
- [ ] `close()`

#### 实现字符流的读操作的类的是？
- [ ] `FileInputStream`
- [ ] `FileOutputStream`
- [ ] `Writer`
- [ ] `FileReader`

#### 下面哪种流可以用于字符输出？
- [ ] `java.io.EncodeWriter`
- [ ] `java.io.OutputStreamWriter`
- [ ] `java.io.EncodeOutputStream`
- [ ] `java.io.OutputStream`

#### 下面关于 Java 主线程的说法错误的是？
- [ ] `主线程结束，整个应用将结束`
- [ ] `主线程与其他线程是平等的`
- [ ] `在多线程应用中，主线程的主要作用是启动其他线程`
- [ ] `主方法所在的线程即主线程`