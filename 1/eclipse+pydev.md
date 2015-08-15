# 配置eclipse+pydev
在Ubunt下开发的工具有很多，比如常见的sublime text,pycharm,vim,eclipse等等，但是在这些工具当中，sublime和vi虽然有较好的扩展性，但是对于新手来说，配置极为繁琐，而pycharm则是收费的软件，对于学生来说购买这样昂贵的产品用来学习显然不可能，好吧，你说可以破解，但是笔者不支持这样的举动。

所以这里笔者选择了eclipse作为开发工具，下面进入正题：
首先我们需要打开[eclipse的官方下载地址](https://eclipse.org/downloads/)，在这里我们下载Eclipse IDE for Java Developers版本即可，因为我的系统是64位的，所以就选择64bit版本下载，下载完毕之后我们进入到下载目录解压压缩文件：
```
sudo tar -zxvf eclipse-java-mars-R-linux-gtk-x86_64.tar.gz
```
这里的解压文件名需要以实际文件名为标准，不要照搬笔者的所有命令，因为版本更新还是很快的。解压之后，进到解压的目录，执行下列命：
```
ls
```
我们这时候会看到好多个文件名，其中有一个是绿色的eclipse，那就是我们的启动文件，在这里我们可以输入：
```
./eclipse
```
启动eclipse，在菜单栏中找到Help选项卡，点击选中Install New Software...,点击work with最右的Add...，Name一栏填入Pydev，Location一栏输入:
<pre>http://pydev.org/updates</pre>

![截图1.1](/home/troll/图片/2015-08-15 18:01:47屏幕截图.png)
![截图1.2](/home/troll/图片/2015-08-15 18:02:09屏幕截图.png)

然后就是一路next了，在这期间可能会报time out错误，多尝试几次就好了，安装成功之后我们还要为pydev配置pytho解释器，选择eclips菜单选项卡上的windows选项卡，然后选择Preferences，展开Pyde-Interpreters-Pytho Interpreter。在右上角点击点击New,输入解释器名字和解释器路径即可，这里的我的设置如下：

![截图1.3](/home/troll/图片/2015-08-15 18:08:18屏幕截图.png)

至此为止，我们的开发环境已经搭建完毕，下面我们就将进入Django的正式学习了。

