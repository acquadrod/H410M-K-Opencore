# ASUS H410M-K Opencore

- CPU : Intel® Core™ i5-10400 Comet Lake
- Storage : Samsung 870 EVO 500GB SATA  |  WD Blue SSD SATA 250GB
- Integrated Graphics UHD 630
- Mainboard : ASUS PRIME H410M-K
- SMBIOS : Macmini8,1  |  iMac20,1
- AppleALC Layout : 11 (Realtek ALC897)
- BIOS Version : 1620
- Fixing CFG Lock : setup_var_cv CpuSetup 0x3E 0x01 0x00

BIOS Setup :

DISABLE 
- Fast Boot
- Secure Boot
- CSM
- Intel SGX
- Intel Platform Trust

ENABLE
- Hyper-Threading
- EHCI/XHCI Hand-off
- DVMT Pre-Allocated(iGPU Memory): 64MB (Recommend)
- SATA Mode: AHCI
