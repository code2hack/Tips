# Q&As #

**Q**:_gdb_ Missing separate debuginfos 
__A__:[stackoverflow](https://stackoverflow.com/questions/10389988/missing-separate-debuginfos-use-debuginfo-install-glibc-2-12-1-47-el6-2-9-i686) 
> yum install yum-utils 
> debuginfo-install glibc 
> if the warning's still there, edit /etc/yum.repos.d/CentOS-Debuginfo.repo, set enabled=1 

