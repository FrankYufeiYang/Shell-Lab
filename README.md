# Proxy-Lab

## 背景
* 课程: System programming
* 教材: Computer Systems: A Programmer's Perspective (CSAPP)

## 语言
C


## 环境与使用
linux下给定的实验环境
* code `tsh.c`文件
* 需要的系统函数： 
  * witpid()
  * sigemptyset()
  * sigaddset()
  * sigsuspend()
  * .......详情参考man page
 
 ## 实验目标
 * 读懂给定的code和搭建好的环境
 * 实现 `quit` - 退出shell
 * 实现 `jobs` - 列出所有后台任务
 * 实现发送与接受各类异常信号 - SIGCONT SIGCHLD SIGSTP
 * 实现回收僵尸进程
 
 ## 调试
 * 利用 `tshref` 程序进行shell完整性测试
 * 利用 `trace` 进行某个特性测试
 * 利用 `sdriver` 进行整体功能测试
 
 ## 总结
 通过实现一个shell， 来加深我们对异常信号的理解，与此同时一个具体如何管理进程，线程的好机会。
