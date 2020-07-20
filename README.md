# mingyue-openwrt-ssr

本项目只提供shadowsocksr和shadowsocks以及redsocks的ipk，以供在明月永在固件上安装使用。请不要在其它固件上安装这些ipk，因为有修改，和固件中其它的文件相互调用，所以不保证在其它固件里安装能正常使用。

配合明月永在v1.4版本使用，含有订阅功能

安装步骤：

使用ssh登录路由器

然后执行一下命令：

cd /tmp/

wget https://github.com/liliuwei/mingyue-openwrt-ssr/releases/download/v1.4/ssr.zip

opkg install luci-app-chinadns_1.3.1-1_all.ipk

opkg install luci-app-pdnsd_git-18.282.55666-c04c81f-1_all.ipk

opkg install luci-i18n-pdnsd-zh-cn_git-18.282.55666-c04c81f-1_all.ipk

opkg install Shadowsocks-libev-spec_3.1.2-2_mips_24kc.ipk

opkg install luci-app-shadowsocks-spec_1.3.1-1_all.ipk

opkg install libudns_0.4-1_mips_24kc.ipk

opkg install luci-app-shadowsocksR-GFW_1.2.5_all.ipk

opkg install shadowsocks-vpn_20150909_mips_24kc.ipk
