配置OPC点表
OPC点表成功导出后，开始进行点表配置，大体步骤同上述vpoint点表配置的步骤相同,导出点表模板->配置点表->导入点表->保存项目，生成.s3db文件。不同点是在参数上配置不同。如下：
 
# OPC单点配置界面说明 #
【变量ID】：自定义，可根据自己的命名规则进行命名；
【点来源类型】：OPC；
【点名】：OPC变量名；
【点类型】：数据类型（VT_R4,VT_I2,VT_BSTR,VT_BOOL）；
【OPC服务名】：OPC服务名称，如：OPCServer.WinCC；
【倍率】：一般默认为1；
【OPCserverIP】：OPC服务器IP，如（192.168.1.182）；
【存储周期】：一般默认为5钟。

 
# 导入Excel点表时OPC类型点的列含义说明 #
在EXCEL表中，OPC点表配置模板中每列含义如下：
A列pointindex：序号；
B列physicalid： 变量名；
C列source：	OPC；
G列param1：OPC变量名；
H列param2：OPC变量类型（VT_I2,VT_BOOL,VT_R4,VT_BSTR）；
I列Param3：	OPC服务名（如OPCServer.WinCC）；
J列 Param4：倍率，一般默认为1；
L列 param6：OPC服务名地址（192.168.1.82）。
U列 storecycle：一般默认为5分钟，填写标识‘3’。


