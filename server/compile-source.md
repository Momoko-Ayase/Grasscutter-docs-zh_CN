# 🏗 编译服务端

在开始前，请确保已安装 [Git](https://git-scm.com/downloads) 与 [JDK17](https://mirrors.tuna.tsinghua.edu.cn/Adoptium/17/jdk/)。

其次，在终端运行`git clone https://github.com/grasscutters/grasscutter.git`获取源代码。

{% hint style="info" %}
在中国大陆地区，执行此操作可能较慢或无法完成，此时请使用镜像完成操作，

例如`git clone https://githubfast.com/Grasscutters/Grasscutter.git`
{% endhint %}

{% hint style="danger" %}
请务必确保路径不含任何**非ASCII字符（如中文）**，否则会编译失败。
{% endhint %}

运行

{% tabs %}
{% tab title="Windows" %}
{% code lineNumbers="true" %}
```shell
cd Grasscutter
.\gradlew.bat #设置环境
.\gradlew jar #编译
```
{% endcode %}
{% endtab %}

{% tab title="Linux" %}
{% code lineNumbers="true" %}
```shell
cd Grasscutter
chmod +x gradlew #添加可执行标记
.\gradlew jar #编译
```
{% endcode %}
{% endtab %}
{% endtabs %}

坐和放宽。你会得到一个文件为`grasscutter-VERSION-BRANCH.jar`。

{% hint style="warning" %}
如果你使用Windows CMD，请**不要**加入`./`前缀。

如果编译时自动使用了错误的JDK版本，请检查JAVA\_HOME环境变量。
{% endhint %}
