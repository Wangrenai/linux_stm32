- libs目录放stm32固件库，src放用户源码，inc放用户头文件
- Makefile.common文件，这个是通用Makefile文件
- 编译固件库，将固件库编译成静态库，应用程序可以直接使用 `startup.c`
- 建立`linker.ld`文件，根据芯片的内存以及flash容量
- 将用户应用程序也编译成静态库
- 主目录下，建立主Makefile文件，将固件库和用户应用程序编译成可执行文件


参考链接：https://blog.csdn.net/zhangxuechao_/article/details/79422529
