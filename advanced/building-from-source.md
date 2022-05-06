# 🏗 Building from source

首先，下载适宜的JDK版本。

{% hint style="info" %}
对于Stable分支，需要JDK8（[在此下载](https://mirrors.huaweicloud.com/java/jdk/8u202-b08/)）
{% endhint %}

其次，使用`git clone https://github.com/grasscutters/grasscutter.git`获取源代码或者直接下载**（不推荐）**

{% hint style="info" %}
如果GitHub访问速度过慢，可以尝试使用镜像（e.g. githubfast.com）
{% endhint %}

在命令行下运行

{% tabs %}
{% tab title="Windows" %}
```shell
cd Grasscutter
.\gradlew.bat #设置环境
.\gradlew jar #编译
```
{% endtab %}

{% tab title="Linux" %}
```shell
cd Grasscutter
chmod +x gradlew #添加可执行标记
.\gradlew jar #编译
```
{% endtab %}
{% endtabs %}

坐和放宽。你会得到一个文件为`grasscutter.jar`。

{% hint style="info" %}
如果你使用Windows CMD，请**不要**加入`./`前缀。

如果编译时自动使用了错误的JDK版本，请检查JAVA\_HOME环境变量。
{% endhint %}
