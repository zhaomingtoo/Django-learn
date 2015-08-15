# 配置Django
在配置Django之前，当然要先配置pytho了，不配置pytho还玩个毛的Djang啊，等等，，但是Ubuntu自带pytho，当然就不需要安装pytho了，而且Ubunt内置好几个版本的python，这里我们默认使用pytho2.7版本。

- 首先我们需要先安装pip，通过pip来安装Django，输入以下命令：
```
sudo apt-get install python-pip
```
- 当我们安装好pip之后，就需要通过pip来安装Django了，输入以下命令：
```
sudo pip install Django
```

这样Django就算已经安装完毕了，当然，还有好几种安装方法，这里就不再一一列举了，大家可以移步这里看其他的安装方法[Djang安装的其他几种方法](https://docs.djangoproject.com/en/1.8/topics/install/#installing-official-release)

既然我们已经安装完毕Djang，那么看看我们是否已经安装成功，打开一个terminal(Ctrl+Alt+T),输入pytho，然后输入以下代码：
```
>>> import django
>>> print(django.get_version())
```
如果输出数字的话就表示安装成功，如果报错的话就表示可能有什么地方做错，这里就靠各位googl解决了。
