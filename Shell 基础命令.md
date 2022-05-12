`whatis ls`:查看 `ls` 这个命令是用来做什么的；

`ls`：列出当前目录的内容

`pwd`：打印当前工作目录；

`cd`：切换工作目录

`cd..`：返回上级目录

`cp`：复制文件和目录

```shell
// 复制文件
cp Hello.txt Hello1.txt
// 复制目录
cp -r 桌面 桌面2
```

`vi`：查看文件

`head`：查看前几行代码

`tail`：查看后几行代码

```shell
// 查看
vi test.txt
// 查看前面三行
head -n 3 text.txt
// 查看后面三行
tail -n 3 text.txt
```

`find`：查找文件

```shell
// 查找后缀为 mp3 的文件
find *.mp3
// 查找后缀为 txt 的文件
find *.txt
```

`cat`：连接和打印

```shell
// 将两个文件合并为一个文件
cat hello.txt word.txt > merge.txt
// 打印这个文件
cat merge.txt
```

`which`：查看命令的路径

`whereis`：详细版的 which

`touch`：改变访问、修改文件的时间戳，如果没有该文件，就新建文件

`rm`：删除文件、目录

```shell
// 删除文件
rm Hello.txt
// 删除文件夹
rm -r Hello/
```

`mv`：剪切、复制

```shell
// 在当前目录给文件重命名
mv test.txt hello.txt
// 剪切到其他目录
mv hello.txt ./桌面/desktop.txt
```

`mkdir`：创建目录