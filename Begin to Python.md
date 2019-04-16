# Python 行进前奏

PS：本人使用的是在 Mac OS X 系统中学习并使用 Python，为此，所有涉及到 Command 命令都仅符合 OS X 输入规格

## 1、安装

### 1.1、Python程序

要使用 Python，必需要在系统里安装程序版本（version），Python 的版本主要有 2.x 和 3.x 两个，目前主流的是 3.x 版本。

安装程序可以从 Python 官网下载，下载与操作系统相应的安装包即可完成安装。

[Python官网]: https://www.python.org/downloads/

#### Mac OS X

Mac OS X （V10.9以上版本）系统自带 Python 2.7 ，安装 3.x 的方式：

1、通过安装包直接安装；

2、借助 Homebrew (系统已安装)在 Command 窗口中直接通过命令 brew install python3.7 完成安装;

3、查看系统安装的 Python 版本，在 Command 窗口中输入 python —version ；因为 OS X 系统自带 Python 2.7 版本，所以在安装了 3.x 版本后，系统环境变量 PATH 的参数还是默认为 2.7 版本，为此，输入查看指令，得到的结果还是 2.7 版本。若要显示为 3.x 版本，则需修改环境变量 PATH 的优先参数。

#### Linux

略

#### Windows

略

### 1.2、代码解释器

当我们安装好 Python 后，系统自动获取一个官方版本的解释器：CPython。CPython 解释器由 C 语言编写。

**解释器的作用是让电脑（Computer）能执行 Python 代码，若没有解释器，则该终端无法运行 Python 代码**

常见的解释器有：IPython、PyPy、Jython、IronPython，各种解释器优劣以后再研究。

### 1.3、工具包 ( Package )

Python Package 是 Python 能如此简洁强大的主要驱动力，Python 社区为工程师提供针对不同领域的丰富、强大的方法、组件、框架、工具等，帮助工程师能快速地将工程代码实现。为此，若要高效的开发产品，必须巧妙的运用各类Package。

##### 1.3.1、Python Package 管理器 pip

Pip是Python提供的强大的包管理器，能借此通过命令直接安装各类Package。

1、安装 pip：在 Command 窗口中输入 python2/3 get-pip.py 完成 Pip 工具的安装；或在官网下载安装包安装【还得纠正，未尝试成功】。

2、使用 pip：在 Command 窗口中输入 python2/3 -m pip install PackageName ，即可完成相应 PackageName 的安装。

3、

##### 1.3.2、Python 虚拟环境

虚拟环境 ( virtual Environment )能为不同的 Project (项目)创建独立的 Python 版本及 Project 需要的 Package (工具包)，确保不同项目间开发环境的冲突，有助于不同项目间的并行代码实现、运行测试等开发工序。

Python 的虚拟环境容器/工具为 virtualenv ，借助该工具，我们就可以创建虚拟环境

1、安装容器/工具

在 Command 窗口中输入 pip3 intall virtualenv

2、创建虚拟环境

在创建虚拟环境过程中，需定义该环境名称及该环境下使用的 Python 版本

(任务：创建一个名为 nb 的虚拟环境)

A、Virtualenv 默认 Python 版本创建虚拟环境，在 CMD 窗口中输入  virtualenv —no-site-packages env-name , Example: virtualenv —no-site-packages nb 

B、自定义 Python 版本创建虚拟环境，在 CMD 窗口中输入 virtualenv —no-site-packages —python = 3.7 env-name , Example: virtualenv —no-site-packages nb

3、启动虚拟环境 ( nb )

在 CMD 窗口中输入 source env-name/bin/actinvate ，Example：source nb/bin/actinvate

4、退出虚拟环境 ( nb )



##### 1.3.3、常见的 Package/Tools/Library





## 2、Python 基础

Python 基础知识，可以选择《 Automate The Boring Stuff With Python 》 这本书入门。







