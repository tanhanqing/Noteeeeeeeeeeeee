卸载VMware
----------------
	控制面板-->vmware->卸载。

安装VMware
----------------
	1.VMware-workstation-full-11.1.2-windows-x86_64.exe
		以管理员身份运行.
	2.自定义安装
		指定安装目录(没有空格，没有中文)
		...

在vmware中安装centos客户机
---------------------------
	1.vware文件菜单-->新建虚拟机->典型安装
	2.安装程序光盘镜像文件，指定CentOS-7-DVD-1503-01-x86_64.iso
	3.个性化linux
		全名	:centos
		用户名	:centos
		密码	:123456
		确认密码:123456


centos基本命令
---------------------------
	CentOS						Windows
	$>ls						cmd>dir				//
	$>ls --help										//查看命令帮助
	$>man ls										//查看命令帮助
	
	$>clear						cmd>cls				//清屏
	$>cd /home					cmd>cd d:/			//切换目录
	$>cd .						cmd>cd .			//进入当前目录
	$>cd ..						cmd>cd ..			//进入上级目录
	$>cd /home/centos			cmd>cd d:/xx/x/x	//进入绝对路径

	$>pwd											//显式当前目录
	$>whoami										//显式当前用户名

	$>su root										//切换用户,输入密码
	$>passwd										//修改当前用户的密码

	$>ifconfig					cmd>ipconfig			//查看ip地址
	$>ping localhost			cmd>ping localhost		//查看网络连通情况
	$>ping www.baidu.com		cmd>ping www.baidu.com	//查看网络连通情况

	$>启动桌面版的网卡
		on.
	$>su centos											//
	$>cd /home/centos									//
	$>cd ~												//回到主目录
	$>cd -												//回到上次的目录
	$>ll												//别名,ls -l --autocolor...
	$>alias												//查看所有的别名
	$>ls -a -l -h										//查看当前目录-h:人性化 -l:列表 -a:显式.开头
	$>mkdir ~/Downloads/a								//创建目录
	$>touch ~/Downloads/a/1.txt							//创建文件
	$>echo helloworld > 1.txt							//重定向输出
	$>cat 1.txt											//查看文件
	$>cp 1.txt 2.txt									//复制文件
	$>rm 1.txt											//删除文件
	$>rm -rf tmp										//强行递归删除
	$>mv a.txt tmp/										//强行递归删除
