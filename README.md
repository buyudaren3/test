# test

1：win+r，输入regedit打开注册表
2：打开注册表的这个路径：
计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings
右键空白的地方新建DWORD值命名为：FlightSettingsMaxPauseDays
3：双击FlightSettingsMaxPauseDays,修改里面的值为100000,右边基数设置为十进制。
设置为100000就是最多暂停100000天,这个值可以自己定义
