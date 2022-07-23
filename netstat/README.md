## netstat解决的问题
* 查看本机有哪些tcp通讯
  > 通讯信息包括： 协议名、本机ip、本机端口、远程主机ip、远程主机端口、通讯状态、数据接收队列、数据发送队列。

* 查看本机有哪些udp通讯

* 查看本机有哪些unix domain socket 通讯
  > 学习过unix系统知识的人应该知道，套接字socket既可以用于本机进程和远程主机进程接发数据，也**可以用于本机两个进程之间接发数据**。

---

## 用法

`netstat`
查看正在发生的所有tcp udp网络连接信息
效果：
> ![](./netstat.png)


`netstat -r`
查看主机路由表
效果：
> ![](./netstat_r.png)

`netstat -l`
查看正在发生的所有tcp udp网络连接信息、unix domain socket 通讯
效果： 
> ![](./netstat_l.png)

`netstat -i`
查看所有网络接口信息（网卡、网桥、蓝牙）
效果：
> ![](./netstat_i.png)


`netstat -I en0`
查看网络接口en0的信息
效果：
> ![](./netstat__I.png)

`netstat -t 80`
查看tcp协议下80端口的信息
效果：
> ![](./netstat_t.png)
> 同理，`netstat -u 80`查看的是udp协议下80端口的信息