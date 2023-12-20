# Solution: Use OVMF_CODE_4M.fd firmware!
If you use the default instead, gpu will fail to passthrough. You will get error "Code 43"

# Test: Passed
Host: Ubuntu
- version: 22.04.6
- kernel: 6.2.0-39-generic

Hardware:
- gpu: |
  03:00.0 VGA compatible controller [0300]: Advanced Micro Devices, Inc. [AMD/ATI] Navi 23 [Radeon RX 6600/6600 XT/6600M] [1002:73ff] (rev c1)
	Subsystem: Micro-Star International Co., Ltd. [MSI] Navi 23 [Radeon RX 6600/6600 XT/6600M] [1462:5021] 

Hypervisor Details
- Emulator: /usr/bin/qemu-system-x86_64
- Chipset: Q35
- Firmware: UEFI x86_64: /usr/share/OVMF/OVMF_CODE_4M.fd

Guest: Windows 11
- image: Win11_23H2_English_x64.iso
- amddriver: whql-amd-software-adrenalin-edition-23.12.1-win10-win11-dec5-rdna.exe
