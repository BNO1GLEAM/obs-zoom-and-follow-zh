Zoom and Follow
---------------
Have you ever needed to zoom in on your screen to show some fine detail work, or to make your large 4k/ultrawide monitor appear less daunting on stream? **Zoom and Follow** for OBS Studio does exactly that, zooms in on your mouse and follows it around. Configurable and low-impact, you can now do old school Camtasia zoom ***live***!

*Maintained for the [current release version of OBS](https://github.com/obsproject/obs-studio/releases/latest)*

*Built using Python 3.10*

*Inspired by [caharkness](https://obsproject.com/forum/members/caharkness.153928/)'s [Magic Window](https://obsproject.com/forum/threads/magic-window.107614/)*

*Last updated: 2023 April 16*
##中文使用说明：
原作者链接：https://github.com/tryptech/obs-zoom-and-follow

### 准备工作
1.安装OBS，Python3
2.在OBS——工具——脚本——Python设置中选择Python安装目录。

OBS好像对Python的识别有问题，需要你的Python安装文件夹目录树为：/Python/Python310

例如我的是D:/Program Files/Python/Python310

直接选择Python文件夹不能识别，必须选择Python310

3.在cmd或者PowerShell中输入

pip install pywinctl

安装PyWinCtl依赖

4.重新启动OBS

在OBS——工具——脚本中选择obs-zoom-and-follow脚本（这里你最好把脚本复制到OBS安装目录下面，以免以后不小心把脚本删除了）

#### OBS设置与脚本设置

1.在OBS采集来源里面选择你需要采集的窗口

2.打开obs-zoom-and-follow脚本设置窗口，选择需要缩放的窗口，如果没有，请点击重新加载源列表

勾选启用监视器覆盖

监视器覆盖中选择缩放源里面的窗口

3.按照需要设置缩放窗口高度宽度，以及缩放动画等。

4.在OBS采集来源里面选择你在第二步中选择窗口，按下快捷键ctrl+E

对齐点选择居中，这时候你会发现OBS预览窗口里面的画面会出现显示不完全的情况，这时候自己把窗口进行拖动，覆盖整个预览窗口。

边框对其选择等比例缩放到框内，边框内对齐方式选择居中

点击关闭

5.设置快捷键：

OBS主窗口点击文件——设置——快捷键，搜索zoom

将第一个热键设置成你习惯的热键

6.关闭设置窗口，按下你设置的热键，看预览窗口是否会进行缩放。


