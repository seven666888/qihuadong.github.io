# Windows JDK环境变量配置

## 配置JAVA_HOME

* 打开 此`电脑` -> `属性` -> `高级系统设置` -> `高级` -> `环境变量` -> `系统变量``

* `新建`  变量名`JAVA_HOME` 变量值 `D:\Program Files\Java\jdk1.8.0_151`


## 配置CLASSPATH

* `新建`  变量名`CLASSPATH` 变量值 `.;%JAVA_HOME%\jre\bin`

## 配置Path

* Win10系统 

  * 新建 `%JAVA_HOME%\bin`

  * 新建 `%JAVA_HOME%\jre\bin`

## 验证

+ 打开 `cmd`

+ 输入java -version

+ 提示如下信息 表示配置成功

![1548381469737](C:\Users\46488\AppData\Roaming\Typora\typora-user-images\1548381469737.png)