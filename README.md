# Proxmox
I used my old PC to install Proxmox VE.

Proxmox VE 8.0 ISO Installer:
[Download the Proxmox VE 8.0 ISO Installer here.](https://www.proxmox.com/en/downloads/proxmox-virtual-environment/iso)

Download via the link and boot up like a regular ISO file.

You can watch Craft Computing's video to help you install Proxmox VE:
[Craft Computing Proxmox Installation Guide](https://youtu.be/sZcOlW-DwrU?si=QqOY40KrekdRCa8h)

Remember the IP address.

## Manage
Enter `https://[The IP]:8006` to manage your server.

Example: `https://192.168.0.15:8006`

Use Proxmox default user `[root]` and enter the password you set before.

Also, you can use SSH to manage your server.

Open the terminal and enter `ssh [Username]@[The IP]`.

Example:`ssh root@192.168.9.15`

Enter the password you set before and type `Y` to confirm.

# Setup Your Proxmox
I have four Harddisk each one are 500Gb and one for install Proxmox one for saveing Backups other two for VMs

