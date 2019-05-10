# aria2
aria2超高速下载

# 服务器安装aria2
## 1.ubuntu直接安装

* 1. sudo apt-get install aria2 - y
* 2. 安装完毕之后启动 aria2c --dir=/usr/develop/aria2/downloads --conf-path=/usr/develop/aria2/aria2.conf(在上面conf文件夹里) --input-file=/usr/develop/aria2/.config/aria2.session --save-session=/usr/develop/aria2/.config/aria2.session       --max-tries=0 --retry-wait=5 -D(相应的改为自己的)

## 2.安装BaiduExporter.crx(https://github.com/Forest10/aria2/tree/master/crx)

* 1.  ![第一步](http://public-img.forest10.com/aria2/baiduexporter1.png)
* 2.  ![第二步](http://public-img.forest10.com/aria2/baidue2.png)
* 3.   设置server.点击测试 ![第三步](http://public-img.forest10.com/aria2/baiduexpoter3.jpg)
## 3.本地gui监视

下载https://github.com/Forest10/aria2/tree/master/gui/mac
