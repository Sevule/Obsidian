# 联网(一个操作都不能少)
输入iwctl进入交互式网络配置shell
## 列出设备
```
device list
```
## 启用设备
```
device device-name set-property Powered on
adapter adapter-name set-property Powered on
```
## 扫描附近WiFi
```
station device-name scan 
#此命令不会输出任何内容
```
## 列出可用WiFi
```
station device-name get-networks
```
## 连接网络
```
station device-name connect SSID
```
