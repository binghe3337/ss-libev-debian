# ss-libev-debian

本脚本适用环境：

系统支持：Debian/Ubuntu

内存要求：≥128M

使用方法：
使用root用户登录，运行以下命令：

wget --no-check-certificate -O shadowsocks-libev-debian.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-libev-debian.sh
chmod +x shadowsocks-libev-debian.sh
./shadowsocks-libev-debian.sh 2>&1 | tee shadowsocks-libev-debian.log

卸载方法：
使用 root 用户登录，运行以下命令：

./shadowsocks-libev-debian.sh uninstall
