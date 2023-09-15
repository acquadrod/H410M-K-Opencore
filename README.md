# ASUS H410M-K Opencore

- CPU : Intel® Core™ i5-10400f Comet Lake
- Storage : Samsung 870 EVO 500GB SATA  
- Rx 570 8gb
- Mainboard : ASUS PRIME H410M-K
- SMBIOS :  iMac20,1
- AppleALC Layout : 11 (Realtek ALC897)
- BIOS Version : 1630
- Fixing CFG Lock : setup_var_cv CpuSetup 0x3E 0x01 0x00

BIOS Setup :

DISABLE 
- Fast Boot
- Secure Boot
- CSM
- Intel SGX
- Intel Platform Trust (not Found)

ENABLE
- Hyper-Threading
- EHCI/XHCI Hand-off
- SATA Mode: AHCI (not found on my BIOS version)

Succeded with Big Sur on AFPS disk.
