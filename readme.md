# 简介
Django 是一个由 Python 编写的一个开放源代码的 Web 应用框架。

使用 Django，只要很少的代码，Python 的程序开发人员就可以轻松地完成一个正式网站所需要的大部分内容，并进一步开发出全功能的 Web 服务 Django 本身基于 MVC 模型，即 Model（模型）+ View（视图）+ Controller（控制器）设计模式，MVC 模式使后续对程序的修改和扩展简化，并且使程序某一部分的重复利用成为可能。

# 安装

Django 下载地址：https://www.djangoproject.com/download/

下载 Django 压缩包，解压并和 Python安装目录放在同一个根目录，进入 Django 目录，执行 python setup.py install，然后开始安装，Django 将要被安装到 Python 的 Lib下site-packages。

然后是配置环境变量，将这几个目录添加到系统环境变量中： C:\Python33\Lib\site-packages\django;C:\Python33\Scripts。 添加完成后就可以使用Django的django-admin.py命令新建工程了。

或者直接使用pip的方式
```bash
sudo pip3 install Django==3.0.6 -i https://pypi.tuna.tsinghua.edu.cn/simple
```