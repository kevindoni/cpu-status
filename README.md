# luci-app-cpu-status
CPU utilization info for the LuCI status page (OpenWrt webUI).

OpenWrt >= 19.07.

**Installation notes:**

    wget --no-check-certificate -O /tmp/luci-app-cpu-status_0.2-4_all.ipk https://raw.githubusercontent.com/kevindoni/cpu-status/main/packages/19.07/luci-app-cpu-status_0.2-4_all.ipk
    opkg --force-overwrite install /tmp/luci-app-cpu-status_0.2-4_all.ipk
    rm /tmp/luci-app-cpu-status_0.2-4_all.ipk
    /etc/init.d/rpcd restart

**i18n-ru:**

    wget --no-check-certificate -O /tmp/luci-i18n-cpu-status-ru_0.2-4_all.ipk https://raw.githubusercontent.com/kevindoni/cpu-status/main/packages/19.07/luci-i18n-cpu-status-ru_0.2-4_all.ipk
    opkg --force-overwrite install /tmp/luci-i18n-cpu-status-ru_0.2-4_all.ipk
    rm /tmp/luci-i18n-cpu-status-ru_0.2-4_all.ipk
    
    
 **i18n-ru:**

    wget --no-check-certificate -O /tmp/luci-i18n-cpu-status-ru_0.2-4_all.ipk https://raw.githubusercontent.com/kevindoni/cpu-status/main/packages/19.07/luci-i18n-cpu-status-zh-cn_0.2-4_all.ipk
    opkg --force-overwrite install /tmp/luci-i18n-cpu-status-zh-cn_0.2-4_all.ipk
    rm /tmp/luci-i18n-cpu-status-zh-cn_0.2-4_all.ipk

**Screenshots:**

![](https://github.com/kevindoni/cpu-status/blob/main/screenshots/cpu.png)
