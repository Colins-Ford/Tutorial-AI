# 2.1 环境配置

## 一、 下载Anaconda安装包：

下载地址：[https://www.anaconda.com/download/](https://www.anaconda.com/download/)

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2vhix47j30ut0sbn34.jpg)

根据所使用操作系统选择对应版本的Anaconda

## 二、 下载PyCharm安装包：

下载地址：[http://www.jetbrains.com/pycharm/download/](http://www.jetbrains.com/pycharm/download/)

 选择对应操作系统的Professional版安装包

![](https://ws3.sinaimg.cn/large/006tKfTcgy1ftj2qyke5vj30ty0e6ac4.jpg)

## 三、 下载完成后开始安装：

Anaconda安装： 

![](https://ws3.sinaimg.cn/large/006tKfTcgy1ftj2r8h5jwj30ds0apgmo.jpg)

进入安装界面，点击Next按钮： 

![](https://ws3.sinaimg.cn/large/006tKfTcgy1ftj2r9eq0zj30dr0apq4d.jpg)

同意使用条款，点击I Agree按钮： 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2r3f5mej30ds0apdgf.jpg)

选择仅为当前用户安装，以便在后续配置PyCharm中为Python环境选择路径，点击Next按钮： 

![](https://ws4.sinaimg.cn/large/006tKfTcgy1ftj2rc2q5uj30ds0apmy4.jpg)

选择安装路径，建议使用默认路径，点击Next按钮： 

![](https://ws1.sinaimg.cn/large/006tKfTcgy1ftj2rwtckqj30ds0apgmz.jpg)

在选择额外安装选项的页面建议勾选“将Anaconda添加到我的PATH环境变量”以及“注册Anaconda作为我的默认Python3环境”，点击Install按钮： 

![](https://ws3.sinaimg.cn/large/006tKfTcgy1ftj2r220cnj30dv0asdh7.jpg)

在完成安装后，会有如下提示，Skip完成安装：

PyCharm安装： 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2rv8g71j30dt0apwfb.jpg)

进入安装界面，点击Next按钮： 

![](https://ws4.sinaimg.cn/large/006tKfTcgy1ftj2rcvfosj30ds0ap0tk.jpg)

建议选择默认安装路径，点击Next按钮： 

![](https://ws4.sinaimg.cn/large/006tKfTcgy1ftj2rdkte8j30ds0aqt9a.jpg)

选择添加到桌面的快捷方式，点击Next按钮： 

![](https://ws1.sinaimg.cn/large/006tKfTcgy1ftj2rw3k6zj30ds0apab2.jpg)

添加到开始菜单，选择Install： 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2s1e590j30ds0aqdgd.jpg)

安装完成，点击Finish按钮。

## 四、 环境配置检测：

1. 安装完成后，在命令行中启用Python解释器，有如下提示则表示Anaconda环境配置完成：

![](https://ws1.sinaimg.cn/large/006tKfTcgy1ftj2s0kxcqj30r70e8wft.jpg)

2. 测试conda管理环境：在控制台输入命令`conda list`查看是否出现下面的结果：

![](.gitbook/assets/image.png)

## 五、 编译器内环境配置：

检测环境通过后，使用PyCharm配置编译器内Python环境：

打开PyCharm，选择不导入设置文件： 

![](https://ws4.sinaimg.cn/large/006tKfTcgy1ftj2ra9c8rj30dw04vjrs.jpg)

阅读完使用条款后，点击Accept按钮： 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2rzvxn1j30dp0aqwgf.jpg)

选择不分享使用数据： 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2rxqpxlj30i207kmy1.jpg)

选择Evaluate for free： 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2r00868j30bf0a4jrx.jpg)

同意注册条款： 

![](https://ws1.sinaimg.cn/large/006tKfTcgy1ftj2qzdkcxj30db036t8y.jpg)

选择界面主题，点击Next按钮： 

![](https://ws1.sinaimg.cn/large/006tKfTcgy1ftj2qx5z4dj30ku0hjq4s.jpg)

默认不选择插件，点击Start按钮： 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2r71q5xj30ku0hjjsh.jpg)

进入界面： 

![](https://ws3.sinaimg.cn/large/006tKfTcgy1ftj2r4a4s8j30hp0b1dhv.jpg)

进入设置界面： 

![](https://ws4.sinaimg.cn/large/006tKfTcgy1ftj2ryob0sj30ij0ibjsb.jpg)

选择Project Interpreter，点击Add按钮: 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2r5yiphj30tl0jw400.jpg)

选择Virtualenv Environment-Exsisting environment-Select Python Interpreter，并选择“Anaconda的安装路径\python.exe”，点击OK按钮： 

![](https://ws1.sinaimg.cn/large/006tKfTcgy1ftj2ru0a3vj30nb0lgtav.jpg)

在正确完成环境配置后，会显示如下界面，点击OK保存更改： 

![](https://ws2.sinaimg.cn/large/006tKfTcgy1ftj2rbcps3j30so0jvwh2.jpg)

至此，PyCharm的Python环境配置完成。

