> 首先，感谢每一个为书籍贡献的小伙伴~~~
>
> 这里是对Gitbook简单使用的一个介绍，为了方便不太熟悉伙伴快速上手~

### 什么是Gitbook？

- 它是一个基于Node.js的命令行工具
- 可以使用Github/Git和Markdown来制作精美的电子书。

### 为什么使用Gitbook？

- 便于多人协作构建内容文档
- 可以在线查看
- 可以导出电子书，如PDF、mobi等，在kindle等设备上查看

### 如何安装Gitbook？

1. 运行环境：因为是基于Node.js，所以要有Node环境。[点击下载Node.js](http://nodejs.cn/download/)，选择自己的系统。
2. 安装：可以使用npm后，在终端安装Gitbook工具.
   1. 命令是： `npm install gitbook-cli -g`
   2. 检测安装是否成功：`gitbook -V`， 会列出cli和Gitbook的版本信息。

### 关于Git

- Git是一个版本管理工具
- 此项目或者很多项目，都选择使用Git进行版本管理
- 链接：[学习使用Git-廖雪峰](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

### 在这个项目中使用Gitbook

1. 在获取开发权限后，clone此仓库。
2. 在终端打开clone的本地仓库，使用`gitbook serve`命令可以开启本地服务。
3. 在 grammar 目录下，选择自己负责的模块，进行Markdown语法编写。同时记得更新SUMMARY.md文件，此文件为电子书的目录。
4. 编写OK后，请在本地服务器自测编写部分，链接是否正确，字段格式等等是否符合。
5. 进行提交。

---

感谢阅读，希望能有所帮助~

如有建议或者出入的地方，欢迎提出~