# pve-zfs-clone
Proxmox script for cloning LXC and KVM

Wladimir-N/pve-zfs-clone made an interactive script to create a clone that does not take up space at the start and is created very quickly. You can then delete the clone and the snapshot on which it was created directly from the Proxmox web interface.
https://t.me/ticketssettinru/187

# Installation via git:

1) Clone the repository

```bash
git clone https://github.com/Wladimir-N/pve-zfs-clone.git
```

2) Create a link to the executable file in the bin directory

```bash
chmod +x pve-zfs-clone/pve-zfs-clone
ln -s $(pwd)/pve-zfs-clone/pve-zfs-clone /usr/local/bin/pve-zfs-clone
```

To call the utility, you can run `pve-zfs-clone` from any folder.

