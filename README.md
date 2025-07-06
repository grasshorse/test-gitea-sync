# test-gitea-sync
just a test to sync gitea and github

zt6nti2mwx

```
# This is the network config for mg
network:
  ethernets:
    eth0:
      dhcp4: false
    zt6nti2mwx:
      dhcp4: false
  version: 2

  bridges:
    br0:
      dhcp4: true
      interfaces:
        - eth0
        - zt6nti2mwx
      dhcp4: yes
```

- tbd
