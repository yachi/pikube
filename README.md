```
add

cgroup_enable=memory cgroup_memory=1

to

/boot/firmware/cmdline.txt
```

```
microk8s.enable dns
microk8s.enable helm3
microk8s.enable metallb:10.0.11.10-10.0.11.110
cd pihole && ./install
```
