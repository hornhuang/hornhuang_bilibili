#### 什么是 JVM ？JVM 的主要作用是什么？

JVM 有针对不同系统的特定实现（Windows，Linux，macOS），目的是使用相同的字节码，它们都会给出相同的结果。字节码和不同系统的 JVM 实现是 Java 语言“一次编译，随处可以运行”的关键所在。

**JVM 并不是只有一种！只要满足 JVM 规范，每个公司、组织或者个人都可以开发自己的专属 JVM。** 也就是说我们平时接触到的 HotSpot VM 仅仅是是 JVM 规范的一种实现而已。

除了我们平时最常用的 HotSpot VM 外，还有 J9 VM、Zing VM、JRockit VM 等 JVM 。维基百科上就有常见 JVM 的对比：[Comparison of Java virtual machines](https://en.wikipedia.org/wiki/Comparison_of_Java_virtual_machines) ，感兴趣的可以去看看。并且，你可以在 [Java SE Specifications](https://docs.oracle.com/javase/specs/index.html) 上找到各个版本的 JDK 对应的 JVM 规范。



今天给大家带来一道
java必考面试题
面试官问
什么是JVM？
我们回答
JVM全称是Java-Virtual-Machine
也就是Java虚拟机的缩写
是运行Java字节码的什么
虚拟机
面试官点头
突然嘿嘿一笑
那JVM的主要作用是什么？
我们答道
JVM针对不同操作系统
比如Windows、Linux和macOS
制定了不同的
规范
来保证相同的字节码编写
能运行出相同的结果
面试官皱眉
问道
这里的字节码是Java代码吗？
我们赶紧继续补充
字节码是Java语言编译出来的
目标代码
用来在Java虚拟机上运行的
这样一来
Java程序只要编译成字节码
就能在不同的平台上运行
这正是Java语言
一次编译，处处运行的
关键所在
面试官听完眉头舒展
点头问到
JVM只有一种吗？
我们嘿嘿一笑
当即答道
只要满足JVM规范
每个公司、组织甚至个人
都可以开发出自己的JVM
所以JVM并不只有一种
我们平时接触到的HotSpot
仅仅是JVM的一种实现而已
面试官听完来劲了
那除了HotSpot之外
你还知道哪些JVM实现？
我们不怂
直接答到
还有J9、Zing和JRockit三种
面试官很满意
这时轮到我们
嘿嘿一笑
看我怎么吊打你
继续补充道
HotSpot是被使用最多
最广泛的虚拟机
目前属于Oracle
JDK1.3以及之后的JDK版本中
都是默认的虚拟机
而J9是IBM力推的虚拟机
主要应用在IBM自己的软件和服务器
Zing是从HoSpot复制出来的
但是
对于那些要求低延迟
或者需要快速预热的场景
Zing的表现秒杀HotSpot
因此
与其说它是HotSpot的一个变种
不如把它看作一个全新的JVM
只是凑巧
与HotSpot很像
论不要脸
还是程序员最强
JRockit、HotSpot与J9并称
三大JVM
他三性能不分伯仲
相互之间内卷严重
本来公平竞争第一的宝座
结果Oracle直接把HotSpot收购
HotSpot当场变成
亲儿子
JRockit只能沦为炮灰
所以想成功
还是得
拼爹
面试官受不了
拍案叫绝
直接满分