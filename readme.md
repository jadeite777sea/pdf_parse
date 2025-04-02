
推荐在王老师服务器上运行,python 版本 3.9.13(python 3.10 可能不行), 运行报错 pip 安装包即可

使用前,先用命令行,sudo docker run --rm -p 8070:8070 grobid/grobid:0.8.1

之后在files放入pdf,运行可得到不同格式的解析的文件

不在服务器运行需要在docker 安装 grobid (20GB),
官网 https://grobid.readthedocs.io/en/latest/Configuration/



