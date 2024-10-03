**New: [wireguard-install](https://github.com/Nyr/wireguard-install) is also available.**

## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS and Fedora.

This script will let you set up your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

### Installation
Run the script and follow the assistant:

Nyr:

`wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh`

My:

`wget https://raw.githubusercontent.com/zjt000/openvpn-install/master/openvpn-install.sh -O openvpn-install.sh && bash openvpn-install.sh`

1. 创建脚本(将checkpwd.sh里面的内容复制进去)

`vim /etc/openvpn/checkpwd.sh`

2. 添加权限

`chmod 755 /etc/openvpn/checkpwd.sh`

3. 重启服务

`systemctl restart openvpn-server@server`
