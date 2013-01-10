1. 安装.net Framwok 4.0支持.(已经有装的同学可免)
2. 更换Erlang.sublime-build.
	2.1 点击 Preferences -> Browse Packages
	2.2 打开 Erlang\Erlang.sublime-bulid文件(注意备份文件)
	2.3 将压缩包中Erlang.sublime-bulid复制到刚才打开的路径.
3. 设置
	i) 设置环境变量
		PATH=<emc.exe所在路径>
		eg:c:\emc.exe
    	ii) 复制emc.exe到system32目录下.
4. 编译
	i) 编译单个文件:
		打开sublime-text2选中一个erl文件.然后Ctrl + B
	ii)编译整个project: 
		选一个emc文件, 然后按Ctrl +B, 进行整个工程编译.
5.emc文件格式:
	每行一句指令, 指令内容请查看emc /?

2013-01-10 V1.3版 更新说明:

1. 增加"i+", "i-"指令, 以便支持多个include目录.

2. 增加emc文件行注释功能, 在行首添加%则表示该行为注释, 本行内容不作处理.

3. 增加sublime text2中, 编译出错后, 增加错误文件与对应行定位功能.

4. 简化了 sublime text2 -> Erlang.sublime-build 指令设定.