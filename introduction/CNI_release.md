# CNI插件版本更新

## 20.07.1

### 变更记录

* Pod网络设置后，增加发送一个GARP包。

## 20.05.1

### 变更记录

* 修改UNI和EIP名称长度上限为64字节。
* cni增强自动识别节点主网卡，无需配置文件里配置。
* 识别UPHost物理机节点不运行UNI设备插件。

### 要求

* Kubernetes版本：全部
* 地域：全部

## 20.04.3

### 变更记录

* 功能更新：实现Pod绑定EIP的功能。

### 要求

* Kubernetes版本：全部
* 地域：全部

## 20.03.2

### 变更记录

* 功能更新：修复重复的API调用导致删除IP失败的更新。

### 要求

* Kubernetes版本：全部
* 地域：全部

## 20.03.1

### 变更记录

* 功能更新：升级CNI配置文件。

### 要求

* Kubernetes版本：全部
* 地域：全部

## 19.12.1

### 变更记录

* 功能更新：能够与Calico Felix和Typha结合，用来支持Kubernetes的网络策略，实现网络隔离功能。

### 要求

* Kubernetes版本：全部
* 地域：全部