# AutoReceiveFile
A script about receive file (.eq picture,recording,attachment,video...) from wechat automatically.

------------

#自动从微信接收文件
	功能很简单,当你在终端运行的时候,如果有人给你发文件,语音,视频等,可以直接下载到本地.

------------


	这是一个很小很小的脚本,但却很实用,使用也非常简单,你只需要将代码clone到本地,然后在文件夹内,
	使用python setup.py install或者pip install(如果你安装了两种以上版本的python,使用python3).

------------


	在终端输入down_file(选定一个文件夹),然后会生成一张二维码,扫描登录,该文件夹下会生成一个.pkl文件,
	这是记录你登录信息,下次再使用,就不会再扫码了,不过注意的是,只在这个文件夹下有效,
	下载的各种文件也在这个文件夹下,如果换文件夹输入命令,需要重新登录,下载目录也是换成新的所在.

------------

	如果想要更改命令名称,需要更改两个地方,一个是down_file文件的名字,不要扩展名,
	还有就是setup.py中的script:[]中的down_file文件,然后需要重新运行上面的构建命令.

------------


	2018-11-10 00:29:57 星期六
