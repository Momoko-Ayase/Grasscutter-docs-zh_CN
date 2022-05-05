# 📜 Startup Script Config

{% hint style="info" %}
本文针对使用start.cmd启动服务端的用户。
{% endhint %}

### Executable Path

| 变量             | 默认值                                       | 备注            |
| -------------- | ----------------------------------------- | ------------- |
| JAVA\_PATH     | C:\Program Files\Java\jdk1.8.0\_202\bin\\ | Java所在目录。     |
| MITMDUMP\_PATH | %CUR\_PATH%                               | MitMDump所在目录。 |
| MONGODB\_PATH  | %CUR\_PATH%                               | MongoDB所在目录。  |

{% hint style="warning" %}
对于Development分支，请更改JAVA\_PATH至`C:\Program Files\Eclipse Adoptium\jdk-17.0.3.7-hotspot\bin\`（默认安装位置，请根据实际情况更改），否则将无法启动。
{% endhint %}

### Utility Path

| 变量                      | 默认值                           | 备注          |
| ----------------------- | ----------------------------- | ----------- |
| SERVER\_JAR\_PATH       | %CUR\_PATH%                   | 服务器可执行文件位置。 |
| DATABASE\_STORAGE\_PATH | %CUR\_PATH%resources\Database | 数据库位置。      |

### Utility Name

|                     |                 |                                             |
| ------------------- | --------------- | ------------------------------------------- |
| SERVER\_JAR\_NAME   | grasscutter.jar | 服务端文件名。                                     |
| PROXY\_SCRIPT\_NAME | proxy           | MitMProxy代理工具启动文件名。（PROXY\_SCRIPT\_NAME.py） |
