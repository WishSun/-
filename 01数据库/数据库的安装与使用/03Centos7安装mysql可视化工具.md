## 1. 首先下载Mysql Workbench，进入下载官网

## 2. 选择操作系统为redhat，然后下载

## 3. 下载完成后进入下载文件目录执行安装命令：  
   rpm -ivh mysql-workbench-community-8.0.17-1.el7.x86_64.rpm   
   如果有依赖包需要下载，则yum安装下载:  
   error: Failed dependencies:  

	libGLU.so.1()(64bit) is needed by mysql-workbench-community-8.0.17-1.el7.x86_64

   则执行命令： yum install libGLU.so.1\(\)\(64bit\)  //括号要加转义符号  
   然后再执行安装命令即可成功
