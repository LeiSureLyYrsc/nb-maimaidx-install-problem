# nb-maimaidx-install-problem
插件仓库指路 [Yuri-YuzuChaN/nonebot-plugin-maimaidx](https://github.com/Yuri-YuzuChaN/nonebot-plugin-maimaidx)

在 Windows Python3.13.X 中，安装此插件可能会出现以下报错

<a><img src='https://raw.githubusercontent.com/LeiSureLyYrsc/nb-maimaidx-install-problem/master/NumPy-Install-Field.png'></a>

~~*我不知道原因，但我找到了解决方案，不要问我什么原因导致的T.T*~~

### Windows 解决方案

##### 方法一

卸载 Python 3.13.X，安装 ＜3.13.X 版本的Python并重新安装插件(最高效)

##### 方法二

下载 [Visual Studio Installer]([Visual Studio: 面向软件开发人员和 Teams 的 IDE 和代码编辑器](https://visualstudio.microsoft.com/zh-hans/))，安装 `Visual Studio Enterprise 2022`，选择 使用 `C++ 的桌面开发`，可选项选择 `MSVC` 和 `Windows SDK`，如下图



<a><img src='https://raw.githubusercontent.com/LeiSureLyYrsc/nb-maimaidx-install-problem/master/Visual-Studio-Install.png'></a>

等待安装完后，重新打开命令行窗口并重新执行插件安装命令，即可安装成功



~~等 Linux 用户在使用 Python 3.13 安装出问题的时候我再考虑出 Linux 的解决方案(bushi)~~



若有部分讲解错误 欢迎对此文本进行 Pull Request
