# Introduction

- gitbook 初始化书籍

  README.md —— 书籍的介绍写在这个文件里
  SUMMARY.md —— 书籍的目录结构在这里配置 



- `gitbook serve` 来预览这本书籍，执行命令后会对 Markdown 格式的文档进行转换，默认转换为 html 格式 


- sublime text3程序，然后点击file->open folder


目录写成中文写法

* \[介绍\]\(README.md)

- 添加图片 url格式

	\!\[图片解释]\(https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=2777181041,585246209&fm=26&gp=0.jpg)

![imgur](https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=2777181041,585246209&fm=26&gp=0.jpg)
- 设置图片位置， 放大缩小
	通过html格式进行运用
	\<\img src='https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=2777181041,585246209&fm=26&gp=0.jpg' width="200" height="200">

	<img src='https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=2777181041,585246209&fm=26&gp=0.jpg' width="200" height="200">
- 设置视频

<\iframe height="400" width="400" src="//player.bilibili.com/player.html?aid=455161493&bvid=BV1g5411t7HG&cid=174553298&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </\iframe>

<iframe height="400" width="400" src="//player.bilibili.com/player.html?aid=455161493&bvid=BV1g5411t7HG&cid=174553298&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

- 跳转链接
[\baidu]\(\http://www.baidu.com)
[跳转的文字超链接](http://www.baidu.com)

增加目录
* \[介绍]\(README.md)
	-\[子目录](zimulu.md)
	-\[子目录](zimulu.md)
	-\[子目录](zimulu.md)
	-\[子目录-跳转链接]\(\http://www.baidu.com\)
* \[介绍]\(README.md)
* \[介绍]\(README.md)
* \[介绍]\(README.md)

创建目录后gitbook init 会自动创建文件与文件夹

- 代码块\`\`\` \`\`\`



	```
	<?python 
	for i in range(10):
		print(i)

	```
- 行内代码 `hello world`
	\`hello world\`


- 修改文字颜色
	\<\font color="red"> 红色</\font>
	<font color="red"> 红色</font>



- 跳转链接










































































