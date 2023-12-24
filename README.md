# acgnfun

# NOTICE!!!

**之前的证书由于意外私钥丢失，现已更换新证书，请重新下载安装**

## 关于数字签名

我的每个项目的发行版都会用数字证书进行签名（当然是自己做的证书，权威CA的证书买不起）

如果您相信我，您可以在[这里](https://github.com/acgnfun/acgnfun/releases/download/v0.1.0/CA_Certification.crt)找到我颁发的根证书，将该证书安装到您的计算机上来确认您获取到的软件是否为本人构建

**本人声称，您安装在计算机上的证书只会用于检测软件来源，不会被用于一些恶意行为**

如果您不信任我，您也可以随发行版找到一张MD5或SHA256哈希表，您也可以自行测试哈希文件

## 关于CA证书

如果**您信任我**，您可以[在此](https://github.com/acgnfun/acgnfun/releases/download/v0.1.0/CertificationInstaller.exe)安装由本人签发的根证书

您同时也可以在发行版中找到程序`CertificationInstaller.exe`，运行该程序，该程序会向您请求管理员权限来安装CA证书

## 关于数字证书

对于本人签发的根证书，其机构名应为`ACGNFUN CA`

对于软件的数字签名，其机构名应为`ACGNFUN`（在UAC中显示为**已验证的发布者**）
