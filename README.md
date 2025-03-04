# zhaoDataMining
# 一、注册Github账户并登录

1.首先进入Github[官网](https://github.com/)

2.点击右上角注册按钮Sign up，来到注册页面

![图片1](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/6fd40822-a930-46fb-8ad5-0c984a3cc28f)


3.在注册页面填写注册信息（邮箱，密码以及用户名）点击Continue


![图片2](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/6fe8042f-7351-40d4-9e39-7cc807b9538b)



4.进入到验证账户页面

![图片3](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/6feb426a-357e-41eb-8160-b57e463c2d17)

5.按照要求进行验证，出现Create account时证明完成了验证，点击Create account后网页会发送验证码到你先前注册的邮箱，将验证码输入后会到达这几个页面，根据自己的需求选择相应的个性化设置或者直接跳过即可
![图片4](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/28312a64-842b-4be2-8aac-f01c0a8086bb)

![图片5](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/5f10e250-fc3b-4192-ba93-4791c43dd875)

![图片6](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/c6273bd6-23b2-48ed-b1b8-fb018c217baa)

6.出现这个页面时，表明Github注册成功

![图片7](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/fa81f6da-9002-40ae-a2a0-80c56b2a98b4)


7.下次登录时，需要点击Sigh in，输入用户名或邮箱，输入密码即可进入

![图片8](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/b455b66b-c8ca-4fb7-aa0c-18c8eb6272f9)


# 二、创建库zhaoDataMining

1.登录Github后，显示这个页面

![图片9](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/cc451c90-077b-4ddd-ae3a-af83a1678e43)


2.点击右上角橘黄色标记，出现下面这个页面，找到your repositories并点击

![图片10](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/feaeff31-432f-4589-981c-72b5d69d75de)


3.点击后进入下面这个页面，点击New开始创建一个新的库

![图片11](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/02cd77f8-9c39-45e3-8ac3-22f0afa9dda9)


4.点击New后，进入下面这个页面，在repository name下方输入所要创建的仓库的名称zhaoDataMining，然后点击Create repository

![图片12](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/fabb5305-0b68-4a88-970e-e21aa6a51c48)


5.出现这个页面时，表明仓库创建成功

![图片13](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/54c6153e-aa4e-48a8-ae9a-79f35a33e10b)


6.使用拖拽的方式或者点击上方方框中蓝色标记choose your files，将PPT上传到zhaoDataMining仓库中出现这个页面表明PPT上传成功
![图片14](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/343cb2b2-db5a-41d0-917b-7efbca0f77cc)



# 三、我想学习的计算机技能

## Python的异步编程

### 1 什么是异步编程

#### 1.1 阻塞

程序未得到所需计算资源时被挂起的状态。
程序在等待某个操作完成期间，自身无法继续干别的事情，则称该程序在该操作上是阻塞的。
常见的阻塞形式有：网络I/O阻塞、磁盘I/O阻塞、用户输入阻塞等。

#### 1.2 非阻塞

程序在等待某操作过程中，自身不被阻塞，可以继续运行干别的事情，则称该程序在该操作上是非阻塞的。
非阻塞并不是在任何程序级别、任何情况下都可以存在的。
仅当程序封装的级别可以囊括独立的子程序单元时，它才可能存在非阻塞状态。
非阻塞的存在是因为阻塞存在，正因为某个操作阻塞导致的耗时与效率低下，我们才要把它变成非阻塞的。

#### 1.3 同步

不同程序单元为了完成某个任务，在执行过程中需靠某种通信方式以协调一致，称这些程序单元是同步执行的。
例如购物系统中更新商品库存，需要用“行锁”作为通信信号，让不同的更新请求强制排队顺序执行，那更新库存的操作是同步的。简言之，同步意味着有序。

#### 1.4 异步

为完成某个任务，不同程序单元之间过程中无需通信协调，也能完成任务的方式。
不相关的程序单元之间可以是异步的。简言之，异步意味着无序。

#### 1.5 并发

并发描述的是程序的组织结构。指程序要被设计成多个可独立执行的子任务。
以利用有限的计算机资源使多个任务可以被实时或近实时执行为目的。

#### 1.6 并行

并行描述的是程序的执行状态。指多个任务同时被执行。
以利用富余计算资源(多核CPU)加速完成多个任务为目的。
并发提供了一种程序组织结构方式，让问题的解决方案可以并行执行，但并行执行不是必须的。

#### 1.7 概念总结

并行是为了利用多核加速多任务完成的进度
并发是为了让独立的子任务都有机会被尽快执行，但不一定能加速整体进度
非阻塞是为了提高程序整体执行效率
异步是高效地组织非阻塞任务的方式
要支持并发，必须拆分为多任务，不同任务相对而言才有阻塞/非阻塞、同步/异步。所以，并发、异步、非阻塞三个词总是如影随形的。

#### 1.8 异步编程

以进程、线程、协程、函数/方法作为执行任务程序的基本单位，结合回调、事件循环、信号量等机制，以提高程序整体执行效率和并发能力的编程方式。

## 关于DNA计算

最近看了一篇论文是关于利用DNA链置换实现汉明码，可以用于在数据传输过程中对于错误数据的检测和纠正，从而达到实现信息安全的目的。在现代通信系统中，准确可靠的数据传输是至关重要的。然而，数据传输可能会受到各种因素的阻碍，包括噪声、干扰和信道衰落。因此，必须采用错误检测和纠正技术来确保传输数据的准确性和完整性。下图是关于所设计的系统用于错误数据检测的简图。
![图片15](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/5387d70c-b59b-41df-9ad9-fb40ed685281)

一种常用的错误检测技术是奇偶校验，其添加单个奇偶校验位以检测数据传输中的错误。虽然简单有效，但奇偶校验纠正错误的能力有限。然而本问它通过利用计算机网络中汉明码的知识，汉明码是一种更先进的错误检测和纠正技术，不仅可以检测错误，还可以纠正错误。汉明码通过向数据添加额外的奇偶校验位来实现这一点，这允许在传输中纠正错误。因此，与奇偶校验相比，汉明码是一种更可靠和更有效的错误检测和纠正技术。

基于DNA纳米结构的错误检测和校正的过程以数据“1011”的传输为例，我们首先需要将这些数据编码成汉明码，然后使用汉明码进行纠错。要首先确定奇偶校验位P1,P2,P3的数值，下图就是通过DNA计算的方法，实现了对于奇偶校验位数值以及位置的确定。

![图片16](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/3d3029b5-c00c-4df9-852f-2da9781ffc89)

![图片17](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/2395d7ca-e986-48ce-8200-a861438a0ba7)

下图是关于系统实现的详细介绍

![图片18](https://github.com/Zhaowei2000/zhaoDataMining/assets/168163127/ddd6d873-35f3-4aa6-9e7e-818aabe317b8)


通过利用基于DNA的纳米结构，这项研究成功地实现了汉明码，并展示了其在通信系统中进行高级错误检测和纠正的潜力。设计的DNA纳米结构执行逻辑操作，包括计算校验码，定位错误数据，并根据荧光信号进行校正。基于DNA的计算元件的利用为开发有效和可靠的数据传输技术提供了可能性。通过这种方法实现了对于在传输数据的过程中的错误数据检测和错误数据位置的纠错，这是一种很新奇的形式，与计算机中的汉明码相结合，通过DNA链置换展现汉明码并且用于信息安全中。未来的研究可以集中在进一步提高基于DNA的纠错系统的性能和可扩展性，并探索其在各个领域的应用。因此想了解更多的计算机方法，也可以通过DNA链置换的方式去实现它。



