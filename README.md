# 关于这个仓库
- 这是一个适用于Unity3D的Package.
- 可以利用此Package,从Modbus TCP Server中,读取数据 或 写入数据.
<br/>

# 如何使用？
- 打开包管理器(Unity Package Manager).
- 点击左上角的“+”图标.
- 选择“添加来自 git URL 的包……”.
- 填入此仓库的URL.
- 在你的CSharp文件开头加入“using MirrorModbus”.
- 在你的CSharp文件中实例化一个MirrorModbusClient对象,并使用该对象包含的方法,对Modbus TCP Server进行读写操作.
<br/>

# 关于核心文件
- EasyModbus.dll 是基础文件.
- MirrorModbusClient.cs 是封装后的类,提供了易于调用的方法.
- 上述两个文件也可以直接下载,并导入Unity Project的Asset文件夹中使用.
<br/>

# 如果你也想创建一个自定义的Package(文件夹)
- 在文件夹中额外添加"*.asmdef"和"package.json",该文件夹的所有内容即可被Unity Package Manager识别.
<br/>
