# Part 1 JAVA虚拟机

| 区域名称   | 作用                                                         |
| ---------- | ------------------------------------------------------------ |
| 虚拟机栈   | 虚拟机栈用于存储局部变量等。用于存储正在执行的每个Java方法的局部变量表等。局部变量表存放了编译期可知长度的各种基本数据类型、对象引用，方法执行完，自动释放。 |
| 堆内存     | 此内存区域的唯一目的就是存放对象实例，几乎所有的对象实例都在这里分配内存。存储对象（包括数组对象），new来创建的，都存储在堆内存。 |
| 方法区     | 存储已被虚拟机加载的类信息、常量、（静态变量）、即时编译器编译后的代码等数据。 |
| 本地方法栈 | 当程序中调用了native的本地方法时，本地方法执行期间的内存区域 |
| 程序计数器 | 程序计数器是CPU中的寄存器，它包含每一个线程下一条要执行的指令的地址 |

![image-20240228164709180](C:\Users\86158\AppData\Roaming\Typora\typora-user-images\image-20240228164709180.png)

