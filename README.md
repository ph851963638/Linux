# Linux
mv命令
移动或更名现有的文件或目录。
语法：mv [源文件或目录] [目标文件或目录]
需求：将t3目录移动到abc目录下
mv t3 abc
ll abc
mv同样是递归的移动。

注意：如果存在同名目录，会提示“是否覆盖？”。

命令中如果添加了参数-f，则直接覆盖，不会提示：mv -f t3 abc


rm(remove)功能：删除文件或目录。

rm 文件名：
rm -f 文件名：强制删除，不会提示“是否删除”。
rm -rf 目录名：强制删除，不会提示“是否删除”。（非空或空目录都会删除，递归）

* 查找文件或目录。
*  find [目录...] [参数]
-name 指定字符串作为寻找文件或目录的范本样式。





Windows有记事本功能。
Linux也有类似的记事本功能。

Vim命令
	输入“vim 文件名”进入“一般模式”
	按下“i”从一般模式，进入“插入模式”
	按下“esc”从“插入模式”退出到“一般模式”
	在“一般模式”下，输入“:wq”，退出编辑





