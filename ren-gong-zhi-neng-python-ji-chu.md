# 2.2 Python基础\(简介&编程模式&注释\)

## Python 教程

![](http://www.runoob.com/wp-content/uploads/2014/05/python3.png)

本教程中使用的Python的3.0版本，常被称为Python 3000，或简称Py3k。相对于Python的早期版本，这是一个较大的升级。为了不带入过多的累赘，Python 3.0在设计的时候没有考虑向下兼容。

本教程主要针对Python 3版本的学习。

## Python 解释器

在Linux和Mac下对环境配置完成后，通过环境变量的配置，就可以通过 shell 终端输入下面的命令来启动 Python3 。

```text
$ PATH=$PATH:~/Anaconda3/bin/python3    # 设置环境变量
$ python
```

在Window系统下我们已经通过之前的环境配置勾选了环境变量的配置以及将Anaconda设置为默认的Python管理器，在此无需手动添加环境变量。

在Python中，Python解释器拥有两种编程模式：

### 01. 交互式编程

我们可以在命令提示符中输入"Python"命令来启动Python解释器：

```bash
$ python
```

执行以上命令后，出现如下窗口信息：

```bash
$ python
Python 3.6.4 |Anaconda custom (x86_64)| (default, Jan 16 2018, 12:04:33)
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

在 python 提示符中输入以下语句，然后按回车键查看运行效果：

```bash
print ("Hello, Python!");
```

以上命令执行结果如下：

```text
Hello, Python!
```

当键入一个多行结构时，续行是必须的。我们可以看下如下 if 语句：

```bash
$ pythonPython 3.6.4 |Anaconda custom (x86_64)| (default, Jan 16 2018, 12:04:33)
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> flag = True
>>> if flag :
...     print("flag 条件为 True!")
... 
flag 条件为 True!
```

### 02. 脚本式编程

将如下代码拷贝至 **hello.py**文件中：

{% code-tabs %}
{% code-tabs-item title="hello.py" %}
```python
print ("Hello, Python!");
```
{% endcode-tabs-item %}
{% endcode-tabs %}

通过以下命令执行该脚本：

```bash
python3 hello.py
```

输出结果为：

```text
Hello, Python!
```

在Linux/Mac系统中，可以在脚本顶部添加以下命令让Python脚本可以像SHELL脚本一样可直接执行：

```python
#! /usr/bin/env python3
```

然后修改脚本权限，使其有执行权限，命令如下：

```bash
$ chmod +x hello.py
```

执行以下命令：

```bash
./hello.py
```

输出结果为：

```text
Hello, Python!
```

## Python注释

确保对模块, 函数, 方法和行内注释使用正确的风格

Python中的注释有单行注释和多行注释：

### 01.单行注释

Python中单行注释以 \# 开头，例如：：

```python
# 这是一个注释
print("Hello, World!") 
```

### 02. 多行注释

多行注释用三个单引号 ''' 或者三个双引号 """ 将注释括起来，例如:

1、单引号（'''）

```python
#!/usr/bin/python3 
'''
这是多行注释，用三个单引号
这是多行注释，用三个单引号 
这是多行注释，用三个单引号
'''
print("Hello, World!") 
```

2、双引号（"""）

```python
#!/usr/bin/python3 
"""
这是多行注释，用三个双引号
这是多行注释，用三个双引号 
这是多行注释，用三个双引号
"""
print("Hello, World!") 
```

