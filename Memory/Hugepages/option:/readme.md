# Guide:
## [Understanding vm.nr_hugepages, vm.hugetlb_shm_group, kernel.shmall, kernel.shmmax, kernel.shmmni](https://harvarinder.blogspot.com/2019/12/understanding-vmnrhugepages.html)

### Calculator: 
>Getting Current values for all the variables
>`cat /etc/sysctl.conf | egrep '(shm|huge)' | sort`
>
>Hugepage size used on the machine
>`grep -i "Hugepagesize" /proc/meminfo`
