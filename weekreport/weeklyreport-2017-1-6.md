#System weeklyreport
## 王建兴
## 1.修复bug:
版本管理问题bug,  
unrar集成,  
seafile集成,  
OTA升级的issue.  
## 2.调查问题:
1.pinyin输入法存在大量的错误日志,几乎把logcat占满了,对于依赖logcat调查问题的存在很大问题.  
已经查到原因移交给李兵  
2.周生强的PC机存在"睡眠"->"唤醒"之后重启的问题.  
复现多次均未出现,暂时cancled该任务  
## 3.正在进行中的任务
1.android中原生的volume管理存在很多问题:  
U盘多次插拔就没有可用的挂载点,  
多个U盘插入时如何分辨U盘    
2.第一次启动时注册界面会存在开始时10s没有反应的问题,比较影响使用体验.

## Weekly plan:  
Volume的自动挂载和自动卸载功能梳理完,解决多次插拔之后没有可用挂载点的问题.  
ISO9660文件系统支持
