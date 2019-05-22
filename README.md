# go_lab_1
go实现一系列web通信机制
## 简介  
go实现socket编程，分别编写服务端和客户端程序，支持ping,echo,quit三种命令，当客户端输入ping,服务端返回pong,当客户端输出echo ***,返回字符串 
当客户端输入quit退出通信。
## 使用  
```
$ go build server.go
$ go build client.go 
$ ls
* client  client.go  server  server.go
$ ./server
$ ./client   
```
结果展示 
![image](https://github.com/birdmanwings/picture/raw/master/images/7.png)
