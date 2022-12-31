# 🎇 使用启动脚本启动

按照下文配置`start_config.cmd`。

#### Executable Path <a href="#executable-path" id="executable-path"></a>

| 变量             | 默认值                | 备注            |
| -------------- | ------------------ | ------------- |
| JAVA\_PATH     | %JAVA\_HOME%\bin\\ | Java所在目录。     |
| MITMDUMP\_PATH | %CUR\_PATH%        | MitMDump所在目录。 |
| MONGODB\_PATH  | %CUR\_PATH%        | MongoDB所在目录。  |

#### Utility Path <a href="#utility-path" id="utility-path"></a>

| 变量                      | 默认值                           | 备注          |
| ----------------------- | ----------------------------- | ----------- |
| SERVER\_JAR\_PATH       | %CUR\_PATH%                   | 服务器可执行文件位置。 |
| DATABASE\_STORAGE\_PATH | %CUR\_PATH%resources\Database | 数据库位置。      |

#### Utility Name <a href="#utility-name" id="utility-name"></a>

| SERVER\_JAR\_NAME   | grasscutter.jar | 服务端文件名。                                     |
| ------------------- | --------------- | ------------------------------------------- |
| PROXY\_SCRIPT\_NAME | proxy           | MitMProxy代理工具启动文件名。（PROXY\_SCRIPT\_NAME.py） |

配置完成后，运行`start.cmd`启动服务端。
