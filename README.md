# fabric-network

build blockchain with fabric

## 1\. 下载fabric相关镜像与二进制文件

```
./bootstrap1.1.sh # 版本v1.1.0
```

## 2\. 将fabric相关的二进制文件路径加入环境变量

```
export PATH=$PWD/bin:$PATH
```

## 3\. 生成MSP证书和创世块等文件

```
./fabric-scripts/hlfv1/composer/generateMaterial.sh
```
