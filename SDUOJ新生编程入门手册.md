# SDUOJ新生编程入门手册

2021年8月

如有建议或意见，请发送邮件至：huangyl1024@outlook.com

## 目录

[TOC]

## 1.学科简介

### 1.1 什么是计算机科学与技术？

* 百度百科的解释如下：

  > 计算机科学与技术是一个计算机系统与网络兼顾的计算机学科宽口径专业，旨在培养具有良好的科学素养，具有自主学习意识和创新意识，科学型和工程型相结合的计算机专业高水平工程技术人才。

* 通俗点来讲就是既能敲代码又能研究怎么敲好代码。

* 与软件工程的区别在于，他们只用敲代码，不必深入研究代码背后的原理。

### 1.2 计算机科学与技术学什么？

* 每年学院的教学计划都有所改动，但是大体相同。
* 专业课有：计算导论与程序设计，高级语言程序设计，计算机系统原理，数据结构与算法，数据库系统，计算机组成与设计，程序设计思维与实践，计算机网络，计算机图形学，操作系统，算法设计与分析，编译原理与技术，计算机体系结构，软件工程与实践等。
* 除了一些基础学科例如高数英语外，基本都是在学如何写代码，如何理解计算机等。

## 2.编程环境配置

### 2.1 C/C++环境配置

* C语言内容比较简单，新生学习C语言有利于以后学习其他主流语言。大一上学期的计算导论主要学习C语言。
* C++语法以C为基础内容，功能强大，“C++无所不能”。大一下学期的高级语言程序设计初步学习C++语言。

* 写在文件中的源代码是人类可读的语言。它需要"编译"，转为机器能够读懂的语言，这样 CPU 可以按给定指令执行程序。

* C 语言**编译器**用于把源代码编译成最终的可执行程序，就是将C源代码文件编译成exe文件。

* **文本编辑器**就是简单的编辑一些文本文件，当然你可以用来写代码，记事本就是几乎最简单的编辑器。

* 而**IDE**是**集成开发环境**的英文缩写，简单点说它包含了编译器和文本编辑器，当然还有其他更强大的功能。

* 所以如果我们想写能运行的代码，就可以选择编译器+文本编辑器或者IDE。两个组合选一个就行。

* ~~我们能用的主流编译器有两种，VC++和GCC。它们分别对应Windows和Linux两种操作系统。我们也可以在Windows上使用GCC的移植版，MinGW就是一个GCC的Windows移植版。你可以在官网下载并安装相应的包。解压之后，你还要设置环境变量，环境变量的设置可以自行百度。~~

* 下面介绍两个拆箱即用的IDE和一个进阶适用的文本编辑器：

  ~~网上教程很多，也可以自行搜索文字或视频教程安装。~~

#### 2.1.1 Dev-C++ 安装使用

* Dev-C++是学院老师推荐的一款IDE，优点在于小巧方便，不需要多余配置，缺点是这个IDE已经很久没有更新了，内置的编译器非常老旧，界面也很朴素，~~甚至可以直接使用动态数组~~。建议编程0基础或者感觉学习编程略有困难的同学使用。

* 下载地址：[Dev-C++ 中文主页 (gitee.io)](https://devcpp.gitee.io/)

* 安装：

  * 打开文件

  * ![20210806210458](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806210458.png)

  * 这里的语言是安装时使用的语言，不需要更改。

    ![20210806210520](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806210520.png)

  * 同意

    ![20210806210529](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806210529-16282613294071.png)

  * 默认配置即可

    ![20210806210539](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806210539.png)

  * 读条结束之后运行程序，进行初次配置。
    ![20210806210627](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806210627.png)

  * 这时候将语言改成中文

    ![20210806210647](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806210647.png)

  * 接下来是简单的编程体验时间

    ![20210806211352](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806211352.png)

    点击保存

    ![20210806211452](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806211452-16282614992632.png)

    输入代码

    ```C
    #include<stdio.h>
    int main() {
        printf("Hello world!");
    }
    ```

    ![20210806211806](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806211806.png)

    依次进行编译运行

    ![20210806211625](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806211625.png)

    点击运行后会弹出黑框，输出”Hello world！“，程序运行成功。

    ![20210806211951](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806211951.png)

#### 2.1.2Visual Studio安装使用

* 如果电脑存储空间足够（一般新电脑都没问题），并且具备一定通过搜索引擎解决问题的能力的话，我个人建议大一第一年还是使用Visual Studio(简称VS)。

* 如果工作相关的话，Visual Studio是可以一直使用的IDE，优点在于功能非常全面，界面和功能也是可以高度自定义的，缺点在于比较臃肿，想要平时随便敲一点代码的话并不方便。

* 同时由于VS面向工程开发，出于安全性的考虑，在学习C语言时，使用输入输出函数可能会报错。可以自行百度，通过修改设置关闭奇怪的报错。

* 官方下载地址：[Visual Studio 2019 IDE - 适用于 Windows 的编程软件 (microsoft.com)](https://visualstudio.microsoft.com/zh-hans/vs/)

* 安装使用：

  * 选择免费的community版本下载

    ![20210806204121](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806204121.png)

  * 之后需要下载一段时间

    ![20210806204255](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806204255.png)

  * 只需要选择一个，其他功能有可能这辈子都用不到。可以更改存储位置，换一个空间比较大的硬盘分区。

    ![20210806210357](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806210357.png)

  * 下载可能比较耗时，下载完之后重启

    <img src="SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806212011.png" alt="20210806212011" style="zoom: 67%;" />

  * 可以不登陆微软账号直接使用

    <img src="SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806212249.png" alt="20210806212249" style="zoom:50%;" />

  * 简单使用：

    VS以项目为单位，想要敲代码的话需要先创建项目

    ![20210806212601](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806212601.png)

    一般选择空项目

    ![20210806212630](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806212630.png)

    在源文件中添加cpp文件

    ![20210806212658](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806212658.png)

    

    ![20210806212710](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806212710.png)

    输入代码然后运行
    
    ![20210806212804](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/20210806212804.png)

#### 2.1.3 Visual Studio Code环境配置

* 简称为VSCode，微软开发的强大的文本编辑器，推荐有一定编程基础或者是实践能力比较强的新生使用。

* 轻便快捷，功能强大，插件丰富，外观漂亮，支持各种主流操作系统。适合写前端和项目不大的后端代码时使用，可能唯一的缺点是环境配置和文件管理方式对新手不友好。

* 官方下载地址：[Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/)

  ![image-20210807143047270](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807143047270.png)

* 接下来是常规安装操作，这里不做介绍。

* 安装完之后打开，建议新手按照下图安装中文插件，有编程基础的新生可以挑战一下英语。

  ![image-20210807143856186](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807143856186.png)

* 根据前文介绍，文本编辑器需要搭配编译器，一般来讲安装的是MinGW编译器。因为墙的存在，一般的同学可能偶尔访问不了下面的网站。

  官网下载地址：[MinGW - Minimalist GNU for Windows Project Top Page - OSDN](https://osdn.net/projects/mingw/)

  其他下载地址：[MinGW-w64 - for 32 and 64 bit Windows - Browse /mingw-w64/mingw-w64-release at SourceForge.net](https://sourceforge.net/projects/mingw-w64/files/mingw-w64/mingw-w64-release/)

  安装时要留意安装路径。

  安装完之后需要进行环境配置才能正常使用：右击计算机（我的电脑） -> 属性 -> 高级系统设置 -> 环境变量，编辑Path系统环境变量，增加MinGW的安装路径\bin，例如：MinGW安装在C:\MinGW中，则需要添加C:\MinGW\bin。

  <img src="SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807145224982.png" alt="image-20210807145224982" style="zoom:50%;" />

  接着同时按win+R键，输入cmd打开控制台，输入gcc -v，回车后能成功看到版本信息则安装完毕。

  环境配置比较重要，如果想要在软件开发方面走得更远的话一定要熟练掌握。在这里详细提一下。

* 接下来的具体操作配置比较繁琐，推荐按照[VSCode配置C/C++环境 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/87864677)这篇教程进行操作。
* 需要注意的是VSCode一般以文件夹为工作单位，先在VSCode中打开一个文件夹才方便自由敲代码。

#### 2.1.4 其他

* 适合C/C++的文本编辑器和IDE还有很多，例如Clion、Codeblocks、Sublime、vim等，这里面除了Codeblocks比较适合新生入门，其他或多或少都需要进行配置，在这里就不详细介绍了。

### 2.2 Python环境配置

* Python是一门简单且使用的语言，上手快，功能丰富，并且处在人工智能和大数据的风口上，适合编写一些小项目。同时也建议无论什么专业，最好都学一下python，用很多可以帮助办公的功能，非常实用。

* 官方下载地址：[Python Releases for Windows | Python.org](https://www.python.org/downloads/windows/)（可能连接不上）

  <img src="SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807150737198.png" alt="image-20210807150737198" style="zoom:50%;" />

  划到最下方，

  ![image-20210807151117485](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807151117485.png)

  注意要勾选Add Python to PATH，然后直接安装即可。

  ![image-20210807152450958](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807152450958.png)

* 接下来验证安装，win+R打开命令行窗口，输入python -v回车,命令行有反应说明安装成功。

* Python的编辑器推荐VSCode和Pycharm，推荐使用VSCode，熟悉之后再接触Pycharm。

* 在VSCode中使用python需要先安装基础pyhton插件，其他插件可以视自己情况安装。

  ![image-20210807153453036](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807153453036.png)

### 2.3 Java环境配置

* Java作为一门主流的工程开发语言，java比C++好学，容易上手。在完成一些大型项目时有得天独厚的优势。

  同时，软件工程专业和部分学校的计科专业都选取Java作为入门语言，对于培养学生的编程能力很有帮助。

  对网站开发，软件开发有兴趣，或者以就业为目标的同学可以自学Java。

* SDUOJ后端选用的语言就是Java。
* Java使用的开发工具在这里只推荐IDEA，至于Eclipse、VSCode等也可以进行Java开发，留待自己探索。

#### 2.3.1 IDEA安装配置

* Java环境配置首先需要下载java开发工具包JDK：[Java SE Development Kit 16 - Downloads (oracle.com)](https://www.oracle.com/java/technologies/javase-jdk16-downloads.html)

  <img src="SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807155017026.png" alt="image-20210807155017026" style="zoom:67%;" />

* 接下来配置环境变量

  * 新增`JAVA_HOME`变量，变量值为jdk路径，例如`C:\Program Files (x86)\Java\jdk1.8.0_91`
  * 新增`CLASSPATH`变量，变量值为`.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;`
  * 在Path变量中新增`%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;`
  * 验证：win+R输入cmd，打开控制台，输入`java -version`命令，回车后出现版本信息说明安装成功。

* 官方下载地址：[Download IntelliJ IDEA: The Capable & Ergonomic Java IDE by JetBrains](https://www.jetbrains.com/idea/download/#section=windows)

  ![image-20210807160204053](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/image-20210807160204053.png)

  新生在拿到学校邮箱后可以申请学生认证，这样在校期间便可以免费使用IDEA付费版。

  学生认证地址：[Free Educational Licenses - Community Support (jetbrains.com)](https://www.jetbrains.com/community/education/#students)

* 接下来直接安装启动即可正常使用。

## 3.学习建议

* 学好每一门课。

* 如果感觉学习吃力，可以去mooc网：https://www.icourse163.org/和B站：[哔哩哔哩 (゜-゜)つロ 干杯~-bilibili](https://www.bilibili.com/)搜索学习视频。

* 在学好学校课程的基础上进行自我提升：

  * 只要喜欢这个专业，就可以加入oops社团。
  * 喜欢开发的可以加入兴趣开放实验室，喜欢挑战的可以加入ACM实验室。
  * 自学Qt（内卷神器）
  * 自学其他编程语言
  * 致力于项目开发，加入SDUOJ。

* 推荐学习资源：

  网站：

  * github：[GitHub](https://github.com/)

  * CSDN:[ CSDN - 专业开发者社区](https://www.csdn.net/)
  * 各语言帮助文档

  视频：

  * [【零基础 快速学Java】韩顺平 零基础30天学会Java_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1fh411y7R8)（很详细，适合入门）
  * [黑马程序员匠心之作|C++教程从0到1入门编程,学习编程不再难_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1et411b73Z?from=search&seid=4746946888851676103)
  * [黑马程序员Python教程_600集Python从入门到精通教程（懂中文就能学会）_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1ex411x7Em?from=search&seid=11480842024250165908)

  其他：

  * [计科学习常见术语简介](https://github.com/HYLazy/introduction-to-commom-terms-in-CS)

## 4.关于SDUOJ

* 网址：https://oj.qd.sdu.edu.cn

### 4.1 SDUOJ简介

#### 4.1.1 什么是OJ？

* OJ，即 Online Judge 系统。
* 最初使用于 ICPC 国际大学生程序设计竞赛和 OI 信息学奥林匹克竞赛中的自动判题和排名。
* 现广泛用于世界高校学生的程序设计训练、竞赛、课程实验、研究生复试、工作面试中的代码自动化评测中

#### 4.1.1 什么是SDUOJ？

* SDUOJ，**S**han**d**ong **U**niversity **O**nline **J**udge即山东大学在线评测系统，是山东大学计算机学院自主研发的自动化、客观性的代码评测系统。
* SDUOJ基于现阶段计算机学院的本科专业课的程序设计类实验现状，对OJ 的概念进行推广，演变为对"程序设计产出"(算法代码、工程项目、甚至一张代码生成的图片等类型)进行自动化客观性的"评价"(正确性、性能、重复率、安全性等指标)。
* SDUOJ正致力于为计算机学院本科教学的程序设计类实验提供更多的创新机会、转化学院课程的教学成果、陪伴计算机学院学子的成长、将有价值的数据做本地化沉淀。
### 4.2 SDUOJ操作示范

* 打开网站：https://oj.qd.sdu.edu.cn

  点击右上角Register注册账号

  ![Snipaste_2021-08-07_12-01-04](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_12-01-04.png)

  注册成功并登录后，再进行学号绑定，需要先登出账号。

  ![Snipaste_2021-08-07_11-58-38](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-58-38.png)

  再点击右上角Login，使用统一认证登录。

  <img src="SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-02-57.png" alt="Snipaste_2021-08-07_11-02-57" style="zoom:50%;" />

  统一认证登录成功后，系统会自动提醒你绑定账号，按照提示操作。

  <img src="SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-59-18.png" alt="Snipaste_2021-08-07_11-59-18" style="zoom:50%;" />

* 账号注册并绑定成功后，点击Problem或Contest，选择题目，开始做题。

  ![Snipaste_2021-08-07_11-22-19](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-22-19.png)

* 阅读题目要求和输入输出示例。

  ![Snipaste_2021-08-07_11-21-32](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-21-32.png)
  
  页面划到最下方为提交代码区域。

![Snipaste_2021-08-07_11-22-30](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-22-30.png)

计算导论课程一般选择C11进行提交。

![Snipaste_2021-08-07_11-38-50](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-38-50.png)

* 在自己的IDE或文本编辑器中写好代码并测试，复制粘贴到提交代码区域进行提交。

  ![Snipaste_2021-08-07_11-41-08](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-41-08.png)

* 提交完毕之后，SDUOJ会给出评测结果，如果正确无误，会全部显示Accept，如果不全为Accepted，则代表代码错误，需要重新修改测试再提交。

  ![Snipaste_2021-08-07_11-24-53](SDUOJ%E6%96%B0%E7%94%9F%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8%E6%89%8B%E5%86%8C.assets/Snipaste_2021-08-07_11-24-53.png)

### 4.3 SDUOJ代码提交说明

* 结合上文的操作示范阅读

* 选手使用 OJ 评测一般经过以下步骤：
  1. 阅读题目，理解题意；
  2. 思考问题，编写程序；
  3. 提交程序，动态评测；
  4. 实时反馈，思考问题。若评测结果不为 `Accepted` 则回到 1. 或 2.

* IO 评测的原理介绍：
  * 评测系统会使用标准输入输出（standard input & output）来测试你的程序。
  * 类比说明：当你在控制台运行你的程序时，你可以手动按动键盘来输入（input）一些字符到控制台（比如 C 语言中可使用 `scanf` 进行读入），你写的程序会读入这些字符，并进行运算，最后可以输出（output。比如 C 语言中使用 `printf` 进行打印）结果。
  * 而在评测系统中同样如此，选手提交源代码，评测系统会使用事先准备好一些 `输入数据` 和相应的 `输出数据` 作为 `测试点`。将选手提交的源代码编译后，让选手程序读入 `输入数据`，通过将选手程序 `输出数据` 与事先准备好的 `输出数据` 比较，来判断选手程序是否正确。这种评测方式被称之为 `黑盒评测`。
  * 对于一个测试点，往往还会设置时间限制和空间限制。
  * 时间限制，指的是程序运行时间的限制。选手程序在一个测试点上的运行时间不能超过给定的时间限制
  * 空间限制，指的是程序使用的内存量的限制。选手程序在运行时占用的最大空间不能超过给定的空间限制。
  * 在程序正常运行结束后，选手程序的 `输出` 会和 `测试点输出` 进行比对。这种比对一般在过滤文末换行和行末空格后，使用全文比对（文本比对）的方式来判定匹配与否。
    所以，请不要在程序中输出多余的类似 `请输入 a 和 b: ...` 、`答案为: ...` 等 这种友好提示！
  * 对于某些特殊的有多组解的题目，会使用一个特定的程序（Special Judge）来进行比对。
  * 这一过程结束后，评测系统会根据程序的运行状态，给出不同的 `评测结果 (Judge Result)`：

|     Judge Result (Alias)     |                         说明                         |                一般情况                |
| :--------------------------: | :--------------------------------------------------: | :------------------------------------: |
|        Accepted（AC）        |                    选手程序被接受                    |                                        |
|     Compile Error（CE）      |                 选手程序无法正常编译                 |                                        |
|      Wrong Answer（WA）      | 选手程序正常结束，但是选手程序的输出与测试点输出不符 |                                        |
|   Presentation Error（PE）   |         选手程序正常结束，但是格式不符合要求         |         一般是多输出空格和空行         |
|     Runtime Error（RE）      |  选手程序非正常结束（选手程序结束时的返回值不为零）  | 一般是程序异常，如下标越界、除零异常等 |
|  Time Limit Exceeded（TLE）  |        选手程序运行的时间超过了给定的时间限制        |                                        |
| Memory Limit Exceeded（MLE） |      选手程序占用的最大空间超过了给定的空间限制      |                                        |
| Output Limit Exceeded（OLE） |         选手程序输出的内容的量超过了最大限制         |                                        |

> ## 示例
>
> * **Description 题目描述**
>
> 给定两个整数 x 和 y，打印它们的和
>
> * **Input 输入标准**
>
> 两个整数 x 和 y，满足 0 <= x, y <= 32767.
>
> * **Output 输出要求**
>
> 一个整数，代表 x 和 y 的和
>
> * **Sample 样例**
>
> > 样例数据，是指来用辅助描述题目的 `标准输入数据` 和 `标准输出答案`，旨在帮助读者更好地理解题意。
> > 题目最终的自动化评测数据可能并不包含样例数据，这需要你编写的程序符合题意并且逻辑正确。
>
> * **Sample Input 样例输入**
>
> ```
> 1381 529
> ```
>
> * **Sample Output 样例输出**
>
> ```
> 1910
> ```
>
> * **Hint 提示**
>
> 以下给出一些常见编程语言的 `A+B Problem` 代码示例：
>
> - C:
>
> ```c
> #include <stdio.h>
> int main(void)
> {
>     int a, b;
>     scanf("%d%d", &a, &b);
>     printf("%d\n", a + b);
>     return 0;
> }
> ```
>
> - C++:
>
> ```c++
> #include <iostream>
> using namespace std;
> int main()
> {
>     int a, b;
>     cin >> a >> b;
>     cout << a + b << endl;
>     return 0;
> }
> ```
>
> - Python2:
>
> ```python
> a, b = [int(i) for i in raw_input().split()]
> print(a + b)
> ```
>
> - Python3:
>
> ```python
> a, b = [int(i) for i in input().split()]
> print(a + b)
> ```
>
> - Java:
>
> ```java
> import java.io.*;
> import java.util.Scanner;
> public class Main {
>     public static void main(String[] args) {
>         Scanner sc = new Scanner(System.in);
>         int a = sc.nextInt(), b = sc.nextInt();
>         System.out.println(a + b);
>     }
> }
> ```
>
> - Java With Buffer IO:
>
> ```java
> import java.io.*;
> import java.util.StringTokenizer;
> public class Main
> {
>     public static void main(String[] args)
>     {
>         int a = nextInt(), b = nextInt();
>         out.println(a + b);
>         out.flush();
>     }
>     static BufferedReader in=new BufferedReader(new InputStreamReader(System.in));
>     static StringTokenizer tok;
>     static String next() {hasNext();return tok.nextToken();  }
>     static String nextLine() {try{return in.readLine();}catch (Exception e) {return null;}}
>     static long nextLong() {return Long.parseLong(next());}
>     static int nextInt() {return Integer.parseInt(next());}
>     static PrintWriter out=new PrintWriter(new OutputStreamWriter(System.out));
>     static boolean hasNext()
>     {
>         while(tok==null||!tok.hasMoreTokens()) try{tok=new StringTokenizer(in.readLine());}catch(Exception e){return false;}
>         return true;
>     }
> }
> ```

