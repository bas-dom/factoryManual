配置Bacnet点表 
Bacnet点表成功导出后，开始进行点表配置，大体步骤同上述vpoint点表配置的步骤相同,导出点表模板->配置点表->导入点表->保存项目，生成.s3db文件。不同点是在参数上配置不同。如下：
 
需要填写以下信息：
【变量ID】：自定义，可根据自己的命名规则进行命名；
【点来源类型】：Bacnet 
【Bacnet Server ID】：Bacnet所在服务器IP；
【点类型】：数据类型，如：AI/AO/BI/BO/AV/BV/MI/MO/MV;
【点相对地址】：所在服务器名；
【倍率】：一般默认为1；
【存储周期】：一般默认为5钟。

在EXCEL表中配置各种类型点的参数如下：
  
需要填写内容如下：
		A列pointindex：序号；
		B列physicalid：点名；
		C列source：点源类型Bacnet；
		G列param1：Bacnet Server IP；
		H列param2：点类型（AI/AO/BI/BO/AV/BV/MI/MO/MV）；
		I列Param3：	相对点地址；
		J列 Param4：倍率，一般默认为1。
U列 storecycle：一般默认为5分钟，填写标识‘3’。


