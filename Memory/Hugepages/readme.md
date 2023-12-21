# Wiki:
- https://wiki.debian.org/Hugepages
- https://wiki.archlinux.org/title/KVM#Enabling_huge_pages

# Guide:
- https://access.redhat.com/solutions/36741
- https://oracle-base.com/articles/linux/configuring-huge-pages-for-oracle-on-linux-64
- https://help.ubuntu.com/community/KVM%20-%20Using%20Hugepages

https://mathiashueber.com/pci-passthrough-ubuntu-2004-virtual-machine/

>Hugepages for better RAM performance
>This step is optionaland requires previous setup: See the Hugepages post for details.
>
>find the line which ends with </currentMemory> and add the following block behind it:
>```
>  <memoryBacking>   
>    <hugepages/> 
>  </memoryBacking>
>```

sch: https://www.google.com/search?q=kvm+hugepages

# options:
Guide:
- https://harvarinder.blogspot.com/2019/12/understanding-vmnrhugepages.html

## Transparent Huge Pages (THP)
https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/virtualization_tuning_and_optimization_guide/sect-virtualization_tuning_optimization_guide-memory-huge_pages
