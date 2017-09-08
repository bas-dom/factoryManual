
# OPC本地测试与远程测试的区别 #
网络环境测试正常后，进行OPC通讯测试，OPC通讯测试分为本地测试和远程连接测试两种，两者区别在于远程连接需要配置DCOM，而本地不需要。本地测试：

# OPC本地测试 #
在本地打开OPCClient.exe,
 
点击OPCConnect
 
点击“Refresh list”
 
双击“Available servers”里的Opc Server的名称，如果未能成功进入以下界面，可能是由于DCOM配置出现问题，此时检查DCOM配置，或者重新配置DCOM。（本地OPC通讯测试不存在）点击OPC下面的“Add Item…”
 
双击右侧的点名，比如AI10_01：
 
添加后如下:
 
在OPCClient所在服务器上添加点后，生成点的值有变化，若数据值有变法，说明通讯成功。

# OPC远程通讯测试 #

OPC远程连接测试的DCOM配置请参考3.3.1OPC环境配置，前期准备工作完成后打开OPCClient.exe,
 
点击OPC-〉Connect
 
Server Node：Opc Server所在的机器，可以填 IP 也可以填机器名，如果不输入就默认Opc Server在本机。
 

输入完IP后点击“Refresh list”
 
双击“Available servers”里的Opc Server的名称，如果未能成功进入以下界面，可能是由于DCOM配置出现问题，此时检查DCOM配置，或者重新配置DCOM。点击OPC下面的“Add Item…”
 
双击右侧的点名，比如AI10_01
 

添加后如下:
 
在OPCClient所在服务器上添加点后，生成点的值有变化，通讯成功。 
















