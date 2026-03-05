

##  环境
1. 宿主机是aarch64的平台
2. docker使用ubuntu24.04
  
## 安装包

###安装基本的包
```
pip install infinity-sdk==0.7.0.dev1
```


###安装magic_enum

```
git clone https://github.com/Neargye/magic_enum.git

cd magic_enum
mkdir -p build && cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr/local ..
cmake --build . --target install
```


###安装oatpp

```
git clone https://github.com/oatpp/oatpp.git

cd oatpp
mkdir -p build && cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr/local ..
cmake --build . --target install
```


