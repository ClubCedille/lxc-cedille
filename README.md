# lxc-cedille


This script permit CEDILLE members to create easily lxc machine base on debian.  :+1:


### Basic useful feature list:

 * Leave only custom config for specific lxc folder
 * Unify common lxc config for cedille on this file : cedille.common.conf

### Prerequisite:
 * LXC tools
 * debian lxc config 
 

### To install:

```bash
cp cedille.common.conf /usr/share/lxc/config/.
cp lxc-cedille /usr/share/lxc/templates/.
```

### NOTE: 
 * File named lxc-cedille's based on lxc-debian. So, to maintain this file for new debian release, we must rebase lxc-cedille on new lxc-debian template.
