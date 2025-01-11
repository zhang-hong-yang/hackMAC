# hackMAC
MSI B450M  + 3700X + WX4100


# 问题

## 黑苹果无法登录APPLE ID和ICLOUD的解决方法
解决方法如下：
1，下载必要的驱动：NullEthernet.kext,链接: https://pan.baidu.com/s/1sV89MNJBuMlpOzcs7X4HDA?pwd=h5zv 提取码: h5zv

2,把NullEthernet.kext拷贝到OC/Kexts/下，SSDT-RMNE.aml拷贝到OC/ACPI/下

3，在config.plist的APCI和Kernel下添加这两项

4，重启即可