## How to Install luci-app-tinyfm
### Open your terminal, then you enter the commands below one by one
    opkg upgrade
    wget --no-check-certificate -O /root/luci-app-tinyfm_1.6_all.ipk https://github.com/Jbt88/package-ipk/raw/main/luci-app-tinyfm/luci-app-tinyfm_1.6_all.ipk
    opkg install /root/luci-app-tinyfm_1.6_all.ipk
    rm /root/luci-app-tinyfm_1.6_all.ipk
    /etc/init.d/uhttpd restart
    
## Enjoy 🙂
