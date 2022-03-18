
```
_______  _______  _______  ______  _______  _______  
|   __ \|    |  ||     __||  ___ /|    |  ||     __|  
|   __< |   \   ||__     || |___  |       ||__     |  
|______/|__|____||_______||______\|__|____||_______|  
```
A DNS blocklist to block malware, junk software, trackers, backdoors in China  
一个 DNS 屏蔽清单，能屏蔽流氓软件、跟踪器、后门域名

---
Supports ``hosts``, ``AdGuard Home``, ``dnsmasq``, ``Clash`` syntax. [Compatibility List](/pages/compatibility.md)  
支持 ``hosts``、``AdGuard Home``、``dnsmasq``、``Clash`` 语法。[兼容性列表](/pages/compatibility.md)

## 使用教程 / How to use
#### Adguard Home  
[见该教程](/pages/adgh.md)  
#### Clash  
将[该文件](/rules/clash)添加至配置文件的``rule``部分  
#### hosts  
Linux: 将[该文件](/rules/hosts)添加至``/etc/hosts``  
macOS: 同上  
Windows: 将[该文件](/rules/hosts)添加至``%windir%\System32\driver\etc\hosts``  
Android: 将[该文件](/rules/hosts)添加至``/system/etc/hosts``并重启  
#### 配置 DNS
[MBRjun Public DNS](/pages/dns.md)  
