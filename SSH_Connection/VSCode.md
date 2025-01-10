# VSCode实现远程连接服务器

## ⭐前置工作

### 1.VSCode     
  - [官网下载](https://code.visualstudio.com/)  
  
### 2.服务器账号  

### 3.下载好的Github项目文件  

### 4.传输文件Xshell和SFTP  
  - [下载和使用](https://blog.csdn.net/qq_44614026/article/details/108896217)  

##  ⭐插件安装  
打开左边工具栏的 **扩展** ，在搜索栏搜索所需安装的插件，以便远程链接与后续调试：  

- `Python`,`Pylance`,`Python Debugger`
- `Jupyter`
- `Remote SSH`
- `Chinese`

## ⭐SSH连接  
这一篇文章讲解得非常清晰，可以参考该[文章](https://blog.csdn.net/Oxford1151/article/details/137228119)  

## ⭐Python解释器  
在终端使用Conda创建好虚拟环境后，在VSCode界面右下角点击Python解释器，在页面正上面会出现`选择解释器`，我们选择刚刚创建的虚拟环境路径即可`miniconda3/envs/py38/bin/python`，点击确定后，完成配置  
后续完成项目所需包的安装即可运行项目
