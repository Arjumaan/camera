先升级u－boot
将升级包放在和tftpserv相同的文件目录下
设备检测到有升级包时就开始升级
升级完后自动启动系统

tftpserv.ini中通过设置
rc=tftprc_en.dll 使用英文版本
rc=tftprc_cn.dll 使用中文版本
没有该配置文件时默认使用中文版本