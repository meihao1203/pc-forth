1. 安装DOSBOX：运行DOSBox0.74-win32-installer.exe即可安装；
2. 将FORTH文件夹复制到计算机任意盘，例如 d:\forth;
3. 使用PCFORTH：

	(1) 启动DOSBOX

		在桌面上双击DOSBox 0.74图标；
	(2) mount d:\forth 到一个指定虚拟盘符：

		例如，将d:\forth目录mount到虚拟盘符K:下，在DOSBOX的DOS提示符下键入：
		Z:\>mount k d:\forth
	(3) 运行pcforth：

		在DOSBOX的DOS提示符下键入：
		Z:\>K:(回车)
		K:\>cd pcforth(回车)
		K:\PCFORTH>forth(回车)
