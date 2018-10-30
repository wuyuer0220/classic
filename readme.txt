解决方案
java打包中文乱码问题
1、修改Eclipse中文本文件的默认编码：
windows->Preferences->general->Workspace->Text file encoding设置为UTF-8

2、修改JAVA源文件的默认编码：
windows->Preferences->general->Content Types->右侧Context Types树，点开Text，选择Java Source File，在下面的Default encoding输入框中输入UTF-8，点Update

3、重新导出源代码jar包，上传到Nexus上；
4、引用的项目执行Maven Update；
