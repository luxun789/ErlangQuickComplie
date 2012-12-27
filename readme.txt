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
