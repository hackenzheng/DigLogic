### 哈尔滨工业大学（深圳）《数字逻辑设计》课程实验指导书

在线访问地址：[https://hitsz-cslab.gitee.io/diglogic/](https://hitsz-cslab.gitee.io/diglogic/)


### 项目仓库文件说明
本指导书使用mkdocs构建，采用material主题，项目主要目录及文件如下

- docs：md格式的指导书源文件，用于编译生成静态html文件
- pkg: 实验用到的课件、开发板手册、代码框架等不便于用md编辑的文档文件
- site: mkdocs生成的静态html文件，用于在线访问
- mkdocs.yml: 整个项目配置文件

### 指导书本地部署
需安装好python和pip，python使用3.6及以上版本

1、先安装python依赖包

    pip install mkdocs

    pip install setuptools

    pip install pymdown-extensions

    pip install mkdocs-material

    pip install python-markdown-math

2、编译并启动http服务提供对外访问

    mkdocs serve 

3、通常会提示在浏览器中输入以下地址进行访问

    http://127.0.0.1:8000/

4、mkdocs安装说明
https://www.mkdocs.org/user-guide/installation/