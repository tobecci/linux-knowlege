[up](./README.md)

## How to fix qemu not starting(showing an error about the default network)

to check the state of the network  `sudo virsh net-list --all`  
to enable the network `sudo virsh net-start default`  
to enable autostart `sudo virsh net-autostart default`  