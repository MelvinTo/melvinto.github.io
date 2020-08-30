## Home Lab
### Virtualization
* [PVE](https://pve.proxmox.com/wiki/Main_Page)
  * Remove License warning
    ```
    sed -i.bak "s/data.status !== 'Active'/false/g" /usr/share/javascript/proxmox-widget-toolkit/proxmoxlib.js && systemctl restart pveproxy.service`
    ```
  * [Dark Theme](https://github.com/Weilbyte/PVEDiscordDark)

### NAS
* Software - [FreeNAS](https://www.freenas.org)
* Hardware - HP Gen8


### System Monitoring
* [Prometheus](https://prometheus.io/)


### Router & Security
* [Firewalla](https://firewalla.com)

 
