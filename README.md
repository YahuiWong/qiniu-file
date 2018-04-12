七牛云上传插件
===========

### 支持功能

* 文件路径前缀添加　　
* 生成文件下载链接


### 设置

1.系统管理－系统设置,添加七牛`AccessKey`和`SecertKey`。

![](img/system_setting.png)

2.在任务中添加`构建后操作`

![](img/bucket_setting.png)

如上图，`上传文件路径前缀`和`保存下载链接文件`支持环境变量配置。
`生成下载路径前缀`注意后面需要添加`/`，以便生成完整下载链接。

### 已经编译文件下载

[qinniu-file.hpi](qinniu-file.hpi)

### 手动编译
```
mvn package -DskipTests
```


> 项目参考[七牛云上传插件](https://github.com/ipy/qiniu-plugin)，并增加新功能。

