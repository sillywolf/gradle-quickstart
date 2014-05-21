### 环境要求

* `jdk1.5`以上,多个版本的jdk可以通过配置`JAVA_HOME`来指定运行时的jvm

### 准备工作

* 访问 [官方网站][1] 下载最新版本的`gradle` 或者访问公司内部的 [FTPSERVER][2]
  下载最新的版本。

* 解压缩下载的文件到本地目录，假设`D:\gradle`

* 右击我的电脑 -> 属性 -> 高级选项卡 -> 环境变量，新增环境变量`GRADLE_HOME`，值为`D:\gradle`

* 将`;%GRADLE_HOME%\bin`追加到`PATH`变量之后

### 检查安装

* 打开`cmd`，输入`gradle -v`，检查输出

>     ------------------------------------------------------------
>     Gradle 1.8
>     ------------------------------------------------------------
> 
>     Build time:   2013-09-24 07:32:33 UTC
>     Build number: none
>     Revision:     7970ec3503b4f5767ee1c1c69f8b4186c4763e3d
> 
>     Groovy:       1.8.6
>     Ant:          Apache Ant(TM) version 1.9.2 compiled on July 8 2013
>     Ivy:          2.2.0
>     JVM:          1.6.0_38 (Sun Microsystems Inc. 20.13-b02)
>     OS:           Windows 7 6.1 amd64

OK，`gradle`已经正确安装

[1]:http://gradle.org/downloads.html
[2]:ftp://192.168.97.53/gradle/