### Centos7安装ngrep
  1. 直接在Centos7下使用yum install ngrep 会返回  
  “No package ngrep available.Error:Nothing to do”  
  2. 这个时候，我们首先下载安装最近的epel软件源（EPEL是yun的一个软件源，里面包含了许多基本源里面没有软件）：  
  rpm -ivh http://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm  
  3. 然后，再执行yum install ngrep即可
