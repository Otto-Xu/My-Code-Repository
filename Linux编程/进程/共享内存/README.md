1.这个程序是不安全的，当有多个程序同时向共享内存中读写数据时，问题就会出现。  
2.共享内存没有提供同步的机制，往往借助信号量来进行进程间的同步工作。  
3.共享内存进行进程间的通信效率高，速度快，接口简单，任意进程均可通过共享内存进行通信。  
