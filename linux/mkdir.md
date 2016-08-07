文件夹创建命令

-p 参数
一次创建多个层级文件夹，即使文件夹不存在
e.g. mkdir -p /a/b/c
 
wrong demo:
mkdir a/b/c 
➜  linux git:(master) ✗ mkdir a/b/c
mkdir: 无法创建目录"a/b/c": 没有那个文件或目录
