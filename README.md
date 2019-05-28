# androidANR
android solve anr problem

当app出现anr黑屏无响应时，解决方法如下：

1. adb shell 进入 data/anr
2. 打开该文件夹下trace.txt文件
3. 在android studio logcat中查看报错信息，找到占用cpu最多的进程号
4. 在trace文件中找到该进程描述
5. 根据描述可以获知该进程正在执行的代码
6. 修改代码
