# B-Raft
在fabric v1.4.3基础上进行修改
common、msp和orderer文件夹，直接替换fabric原目录下的这三个文件夹
raft文件夹替换fabric/vendor/go.etcd.io/etcd目录下的原raft文件夹
bin文件夹下的二进制文件是编译出来，可以直接运行的指令文件，拷贝至ubuntu系统的/usr/local/bin文件夹下
orderer.yaml文件为修改后的orderer配置文件范例
