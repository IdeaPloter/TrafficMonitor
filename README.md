# Traffic Monitor 11Patch
Traffic Monitor 是一款用于 Windows 平台的网速监控悬浮窗软件，可以显示当前网速、CPU 及内存利用率，支持嵌入到任务栏显示，支持更换皮肤、历史流量统计等功能。

修改，增加了 Windows 11 新任务栏的一点支持。

![pic](https://user-images.githubusercontent.com/36418285/125168871-284a2500-e1da-11eb-80f7-692c026b97e5.png)

# [下载](https://github.com/ZetaSp/TrafficMonitor/releases/latest)：

修改自 1.80.3，点击上面下载

# 主要特性
* 显示当前实现网络传输速率、CPU和内存占用率
* 如果电脑有多个网卡，支持自动和手动选择网络连接
* 查看网络详细信息
* 支持嵌入到任务栏显示
* 支持更换皮肤和自定义皮肤
* 历史流量统计
* ＊增加对 Windows 11 的特别适配
* ＊其他系统可能会失去适配

# 使用指南

√ 任务栏窗口现在已经支持【最左边】【任务栏左边】【任务栏右边】【最右边】，设置里调节左右位置后会弹出对话框选择。没看懂可以随意试试。设置可保存。

√ 可以在配置文件里手动调节左右偏移值（task_bar_wnd_offset），默认0，向右为正。

如果打开了 **背景透明** ，Traffic Monitor 任务栏会不可点击，如果没开则可以点击，但是不能透明。

如果 Traffic Monitor 任务栏的交互对你很重要，不妨先关闭背景透明，开启 **根据任务栏颜色设置背景色** ，这个效果近似透明；如果你只看个数据，那么可以继续透明。

关闭桌面图标，修改一些任务栏设置等，会导致 Traffic Monitor 消失，需要关闭重新打开。

另外很抱歉，技术有限，任务栏弹窗是硬编码的简体中文，其他语言用户如有需要请自行修改 TaskBarSettingsDlg.cpp 编译。

### 更多信息请访问原储存库 [Traffic Monitor](https://github.com/zhongyang219/TrafficMonitor)
