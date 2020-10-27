###  安装 ntpdate ntp
```shell
yum install -y ntpdate ntp
```
###　时间同步，使用阿里云时间同步服务器
```shell
ntpdate -u ntp.aliyun.com
```