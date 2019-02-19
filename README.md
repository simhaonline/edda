# edda

## Requirements

python3-lxc, version 2.0.7+

You can find it at [https://github.com/lxc/python3-lxc].

However LXD should also have its own commands, and its own python bindings?

## Give user storage capacity

> edda grant-storage dave 20GB

This will allocate storage from /data and mount it in the container as
/mnt/data.
