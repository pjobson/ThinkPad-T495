# Lenovo ThinkPad T495

## Specifications

* **CPU:** [AMD Ryzen 5 PRO 3500U](https://www.cpubenchmark.net/cpu.php?cpu=AMD+Ryzen+5+3500U&id=3421)
* **Graphics:** [AMD Radeon Vega 8 Mobile Gfx](https://www.videocardbenchmark.net/gpu.php?gpu=Radeon+Vega+8+Mobile&id=3845)
* **Monitor Support:** Supports up to 4 independent displays via native display and 3 external monitors; supports external monitors via HDMI? (up to 4096x2160@60Hz) or USB-C (up to 4096x2304@60Hz)
* **Memory:** One memory soldered to systemboard, one DDR4 SO-DIMM slot, dual-channel capable. 8GB soldered, up to 40GB 8GB + 32GB module.
    * Known good memory: Samsung p/n M471A4G43MB1-CTD
* **Storage Support:** M.2 2280 NVME
* **Card Reader:** MicroSD
* **Audio:** Realtek ALC257
* **Ethernet:** Realtek RTL8111EPV
* **Wireless:** Intel Wireless-AC 9260, 802.11ac Dual Band 2x2 Wi-Fi + Bluetooth 5.1, M.2 card
* **WWAN/Mobile:** M.2 B+M-Key
    * Can be replaced with a B+M Key SSD, such as: Western Digital p/n SDAPTUW-128G

## Hardware Info

* **[aplay](data/aplay.md)** - ALSA List of Devices & PCMs
* **[dmidecode](data/dmidecode.md)** - Decoded SMBIOS Hardware Table Info
* **[inxi](data/inxi.md)** - Technical Hardware Data
* **[lscpu](data/lscpu.md)** - Information about CPU Architecture
* **[lshw](data/lshw.md)** - Lists hardware information
* **[lspci](data/lspci.md)** - Lists PCI devices
* **[lsusb](data/lsusb.md)** - Lists USB devices
* **[pactl](data/pactl.md)** - Information on Pulse Audio Devices

## Docking Stations


| Station                                | USB 3.1       | USB 2.0 | USB-C    | Gigabit Ethernet | DP 1.4 | HDMI 2.0 | VGA | Stereo/Mic Audio | Lock Slot |
| -------------------------------------- |:-------------:|:-------:|:--------:|:----------------:|:------:|:--------:|:---:|:----------------:|:---------:|
| [Basic](https://1tn.org/lenovobasic)   | 2 gen1 5Gbps  | 2       | 0        | 1                | 1      | 0        | 1   | 1                | 1         |
| [Pro](https://1tn.org/lenovopro)       | 3 gen1 5Gbps  | 2       | 2 5Gbps  | 1                | 2      | 0        | 0   | 1                | 1         |
| [Ultra](https://1tn.org/lenovoultra)   | 4 gen2 10Gbps | 0       | 2 10Gbps | 1                | 2      | 1        | 1   | 1                | 1         |


## Manuals

* [User's Guide v2 (PDF)](pdf/T495.UsersGuide_v2.en.pdf)
* [Product Specification Reference (PDF)](pdf/T495.ProductSpecificationReference.en.pdf)
* [Hardware Maintenance Manual (PDF)](pdf/T495.HardwareMaintenanceManual.en.pdf)
* [Datasheet](pdf/T495.Datasheet.2.en.pdf)
* [Partner Datasheet](pdf/T495.Datasheet.1.en.pdf)
* [Datasheet Submodel 20NJ0000US](pdf/T495.Datasheet.20NJ0000US.en.pdf)
* [EU Declaratoin of Conformity](pdf/T495.EU_Declaration_of_Conformity.en.pdf)

## Articles

* [Enable Fingerprint Reader Ubuntu Variants](https://gist.github.com/pjobson/705d3c24a7712dede6860337791068dd)
* [Dual Boot ThinkPad T495 w/ rEFInd](https://gist.github.com/pjobson/33c4eb250c2542c84dbfde79d6a8b31c)
* [AMDGPU Firmware Linux](https://gist.github.com/pjobson/90380853d37fb28345d38592c1f7a5eb)

## 1.32 BIOS Updates

Note: The Debian/RHEL/SUSE/Ubuntu one would not run properly under Mint 21.2 x64.

* BIOS Update Utility (Windows 10/11 64 bit) - [r12uj62w.exe](BIOS/r12uj62w.exe)
* ReadMe for BIOS Update Utility (Windows 10/11 64 bit) - [r12uj62w.txt](BIOS/r12uj62w.txt)
* BIOS Update (Bootable CD) - [r12uj62wd.iso](BIOS/r12uj62wd.iso)
* ReadMe for BIOS Update (Bootable CD) - [r12uj62wd.txt](BIOS/r12uj62wd.txt)
* BIOS Update Utility (Debian/RHEL/SUSE/Ubuntu) - [r12ul62w.zip](BIOS/r12ul62w.zip)
* README (Debian/RHEL/SUSE/Ubuntu) - [r12ul62w.txt](BIOS/r12ul62w.txt)

## Images

* [Motherboard Bottom](img/motherboard.bottom.jpg)
* [Motherboard Top](img/motherboard.top.jpg)
* [Samsung 32GB DDR4 PC4-21300, 2666MHZ, M471A4G43MB1-CTD](img/recommended.ram.jpg)
* [Western Digital WD 128GB SSD  SDAPTUW-128G B+M Key](img/wd.bmkey.ssd.jpg)
* [Intel Wireless-AC 9260](img/intel.ac9260.jpg)

## References

* [Lenovo T495](https://www.lenovo.com/us/en/p/laptops/thinkpad/thinkpadt/t495/22tp2ttt495)
* [Lenovo Support](https://pcsupport.lenovo.com/us/en/products/laptops-and-netbooks/thinkpad-t-series-laptops/thinkpad-t495-type-20nj-20nk)
* [iFixit T495](https://www.ifixit.com/Parts/Lenovo_ThinkPad_T495)
* [BIOS & Drivers](https://pcsupport.lenovo.com/us/en/products/laptops-and-netbooks/thinkpad-t-series-laptops/thinkpad-t495-type-20nj-20nk/downloads/ds539877-bios-update-utility-bootable-cd-for-windows-10-64-bit-thinkpad-t495)
