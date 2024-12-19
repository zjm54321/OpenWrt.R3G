# 🗂️OpenWrt.R3G
| OpenWrt | 23.05.5 |
| :------ |:-------:|
Architecture|MIPS
Targets|ramips
Vendor|Mediatek
Bootloader|Breed
System-On-Chip|MT7621 Family
CPU/Speed|mipsel_24kc @ 880MHz 2 core
Flash|128MB SLC Nand Flash
RAM|RAM 256MB DDR3-1200
Wireless|2.4G MT7603EN WiFi 2X2 802.11N<br>5G MT7612EN WiFi 2X2 802.11AC
Ethernet|3x1000Mbit/s VLAN Support
USB|1x3.0 DC Output:5V/1A

```
[Latest Stable Release](https://downloads.openwrt.org/)
```

## 📔必装插件:
> 仅收录WebUI,对应核心·依赖·翻译包自动补齐
### 通过官方渠道✨

* luci-i18n-base-zh-cn 0️⃣
* luci-app-ksmbd 1️⃣
* luci-app-upnp 3️⃣
* block-mount 4️⃣

### 通过三方渠道🪄
* luci-app-mihomo 2️⃣
* luci-theme-design 5️⃣

$$Custom \quad Settings$$
```html
<style>
.navbar {
  display: none;
}
</style>

<div class="navbar">
  <a href="/cgi-bin/luci/admin/status/overview"><img src="<%=media%>/images/home.png" /></a>
  <a href="/cgi-bin/luci/admin/services/openclash"><img src="<%=media%>/images/openclash.png" /></a>
  <a href="/cgi-bin/luci/admin/network/network"><img src="<%=media%>/images/link.png" /></a>
  <a href="/cgi-bin/luci/admin/status/realtime"><img src="<%=media%>/images/rank.png" /></a>
  <a href="/cgi-bin/luci/admin/system/admin"><img src="<%=media%>/images/user.png" /></a>
</div>
```

`⬇️Download:`
[OpenWrt-mihomo](https://github.com/morytyann/OpenWrt-mihomo)
[mihomo](https://github.com/MetaCubeX/mihomo)
[dl.openwrt.ai](https://dl.openwrt.ai/packages-24.10/mipsel_24kc/kiddin9/)
[OpenWrt固件插件](https://dllkids.xyz/packages/mipsel_24kc/)

## 🔮选装插件:

- [ ] luci-mod-dashboard
- [ ] luci-app-diskman
- [ ] luci-app-aria2
- [ ] luci-app-mwan3
- [ ] luci-app-openclash
- [ ] luci-app-clash v1.8.0-2
- [ ] luci-app-frpc
- [ ] tailscale
- [ ] luci-app-zerotier
- [ ] adguardhome
- [ ] luci-app-samba4
- [ ] luci-app-smartdns
- [ ] luci-app-wol

0️⃣1️⃣2️⃣3️⃣4️⃣5️⃣6️⃣7️⃣8️⃣9️⃣🔟

✨🪄🔎📔🗂️🔥⭐💖⚡🔦🔮🧸

```
luci-theme-design备份来源 @fichenx(https://github.com/fichenx/packages)
同步"上上上上上上上"游更新 (https://github.com/kenzok8/small-package)
GithubPage (https://kenzok8.github.io/openwrt-packages/)
```
