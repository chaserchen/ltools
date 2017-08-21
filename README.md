## 目的  
将Linux中常用的重复的命令组合在一起，提高程序员生产效率。  

## 功能  
### 运行c语言代码  
> 所用脚本 run_c

使用:  
```c
run_c test.c
```
为在全局环境中使用，可将脚本配置在alias中，如：
```c
alias run_c='cd $HOME/projects/ltools;./run_c'
```
