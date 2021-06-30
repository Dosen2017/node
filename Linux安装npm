# npm的安装
### 下载二进制压缩包
    下载地址：https://nodejs.org/en/download/  【官网】
             http://nodejs.cn/download/       【中文官网】
             
    下   载：wget  https://nodejs.org/dist/v14.17.1/node-v14.17.1-linux-x64.tar.xz
             wget https://npm.taobao.org/mirrors/node/v16.4.0/node-v16.4.0-linux-x64.tar.xz
           
### 解压
    tar -xvf node-v14.17.1-linux-x64.tar.xz
    
### 检查安装是否成功
    解压目录的bin中：./node -v
    
### 配置软链接
    #/usr/local/node/bin/node 这个路径是node.js解压包的路径，重新起了个名字
    mv node-v14.17.1-linux-x64 node  // 修改解压包名称

    ln -s /usr/local/node/bin/node /usr/bin/node  --将node源文件映射到usr/bin下的node文件
    ln -s /usr/local/node/bin/npm /usr/bin/npm
    
### 安装CNPM【可选】
    npm install cnpm -g --registry=https://registry.npm.taobao.org
