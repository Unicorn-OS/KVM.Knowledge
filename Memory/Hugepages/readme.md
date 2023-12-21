# Guide:
- https://access.redhat.com/solutions/36741

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
