Auto Install ocserv Server for CentOS&RedHat 7
=======================================
这是 ocserv 在 CentOS 7 和 RHEL 7 的一键安装脚本，使用 epel 的二进制源，可以在最小化安装环境的 CentOS 7 和 RHEL 7 下一键部署 ocserv。

该项目参考自 [ocserv-auto](https://github.com/travislee8964/ocserv-auto)，移除交互式获取变量（端口、用户名、密码），使其能够在VM初始化时自动安装

默认参数：

* 用户名：`vpn`
* 密码：`vpnvpnvpn`
* 端口：443

本仓库的CA证书为自用，如需在其它地方使用需要更换为自己申请的证书。

