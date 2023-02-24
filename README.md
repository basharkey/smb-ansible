# smb-ansible
Deploy simple samba server

[Mount host path inside LXC container](https://pve.proxmox.com/wiki/Linux_Container#_bind_mount_points)

## Create Samba user
```
useradd <user>
smbpasswd -a <user>
```
