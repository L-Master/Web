#Servlet教程学习

> http://www.runoob.com/servlet/servlet-tutorial.html

##Servlet简介

### 1. Servlet是什么? ###

1. Java servlet是运行在Web服务器或应用服务器上的程序.
2. 它是作为web浏览器或其他HTTP客户端的请求和HTTP服务器上的数据库或应用程序之间的中间层.

**Servlet能用来干什么?**

1. 收集来自网页表单的用户输入.
2. 呈现来自数据库或者其他源的记录数据.
3. 动态创建网页.

**Servlet的优点.**

1. Java Servlet通常使用CGI(Common Gateway Interface,公共网管接口)实现程序可以达到的异曲同工的效果.
2. 性能明显比CGI更好.
3. Servlet在Web服务器的地址空间内执行.这样就没必要在创建一个单独的进程来处理每个客户端的请求.
4. Servlet是独立于平台的,因为他们使用Java编写的.
5. 服务器上的Java安全管理器执行了一系列的限制,以保护服务器上的资源,因此,Servlet是可信的.
6. Java类库的全部功能对Servlet来说都是可用的.他可以通过sockets和RMI机制与applets\数据库或其他软件进行交互.

### Servlet架构 ###

![图片](/servlet-arch.jpg)

### Servlet 任务 ###

1. 读取客户端数据.
2. 处理数据.
3. 发送数据到客户端.

### Servlet包 ###

1. Servlet使用**javax.servlet**和**javax.servlet.http**包创建.它是Java企业版本的标准组成比分,Java企业版是支持大型开发项目的Kava类库的扩展版本.