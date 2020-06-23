# etcd-cluster
<!-- TOC -->
## cfssl-etcd-cluster
<!-- /TOC -->
### author: yinshixiong
### 用于安装Etcd服务
### 安装前需要将数组脚本内ip进行替换，如果多节点适当修改配置信息
### 只需要修改globalClusterInfo.sh
- [server_arrays数组](用于录入IP地址)
  - [etcd1 etcd2 etcd3 etcd4 etcd5]
  - [etcd1 etcd2 etcd3]
  - [etcd1]
## 主要组件版本
| 组件 | 版本 |
| --- | --- | 
| etcd| 3.3.13|
| etcdctl| 3.3.13|


- [树]
  - [cleanRootCA.sh](用于清理所有证书)
  
