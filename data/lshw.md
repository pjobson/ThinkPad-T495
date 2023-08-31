# lshw info

lshw is a small tool to extract detailed information on the hardware configuration of the machine. It can  report exact  memory  configuration,  firmware version, mainboard configuration, CPU version and speed, cache configuration, bus speed, etc. on DMI-capable x86 or IA-64 systems and on some PowerPC machines (PowerMac G4 is  known  to work).

`lshw`

	tpad
	    description: Notebook
	    product: 20NKS0WA03 (LENOVO_MT_20NK_BU_Think_FM_ThinkPad T495)
	    vendor: LENOVO
	    version: ThinkPad T495
	    serial: PF14FXAB
	    width: 64 bits
	    capabilities: smbios-3.1.1 dmi-3.1.1 smp vsyscall32
	    configuration: administrator_password=disabled chassis=notebook family=ThinkPad T495 power-on_password=disabled sku=LENOVO_MT_20NK_BU_Think_FM_ThinkPad T495 uuid=5463df4c-24c6-11b2-a85c-b2785cba164f
	  *-core
	       description: Motherboard
	       product: 20NKS0WA03
	       vendor: LENOVO
	       physical id: 0
	       version: SDK0J40697 WIN
	       serial: L1HF993044V
	       slot: Not Available
	     *-memory
	          description: System Memory
	          physical id: 1
	          slot: System board or motherboard
	          size: 16GiB
	        *-bank:0
	             description: SODIMM DDR4 Synchronous Unbuffered (Unregistered) 2400 MHz (0.4 ns)
	             product: M471A1G44AB0-CTD
	             vendor: Samsung
	             physical id: 0
	             serial: 00000000
	             slot: DIMM 0
	             size: 8GiB
	             width: 64 bits
	             clock: 2400MHz (0.4ns)
	        *-bank:1
	             description: SODIMM DDR4 Synchronous Unbuffered (Unregistered) 2400 MHz (0.4 ns)
	             product: M471A1K43DB1-CTD
	             vendor: Samsung
	             physical id: 1
	             serial: 13C0B388
	             slot: DIMM 0
	             size: 8GiB
	             width: 64 bits
	             clock: 2400MHz (0.4ns)
	     *-cache:0
	          description: L1 cache
	          physical id: 3
	          slot: L1 - Cache
	          size: 384KiB
	          capacity: 384KiB
	          clock: 1GHz (1.0ns)
	          capabilities: pipeline-burst internal write-back unified
	          configuration: level=1
	     *-cache:1
	          description: L2 cache
	          physical id: 4
	          slot: L2 - Cache
	          size: 2MiB
	          capacity: 2MiB
	          clock: 1GHz (1.0ns)
	          capabilities: pipeline-burst internal write-back unified
	          configuration: level=2
	     *-cache:2
	          description: L3 cache
	          physical id: 5
	          slot: L3 - Cache
	          size: 4MiB
	          capacity: 4MiB
	          clock: 1GHz (1.0ns)
	          capabilities: pipeline-burst internal write-back unified
	          configuration: level=3
	     *-cpu
	          description: CPU
	          product: AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx
	          vendor: Advanced Micro Devices [AMD]
	          physical id: 6
	          bus info: cpu@0
	          version: 23.24.1
	          serial: None
	          slot: FP5
	          size: 1734MHz
	          capacity: 3700MHz
	          width: 64 bits
	          clock: 100MHz
	          capabilities: lm fpu fpu_exception wp vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp x86-64 constant_tsc rep_good nopl nonstop_tsc cpuid extd_apicid aperfmperf rapl pni pclmulqdq monitor ssse3 fma cx16 sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand lahf_lm cmp_legacy svm extapic cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw skinit wdt tce topoext perfctr_core perfctr_nb bpext perfctr_llc mwaitx cpb hw_pstate ssbd ibpb vmmcall fsgsbase bmi1 avx2 smep bmi2 rdseed adx smap clflushopt sha_ni xsaveopt xsavec xgetbv1 xsaves clzero irperf xsaveerptr arat npt lbrv svm_lock nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold avic v_vmsave_vmload vgif overflow_recov succor smca sme sev sev_es cpufreq
	          configuration: cores=4 enabledcores=4 microcode=135299337 threads=8
	     *-firmware
	          description: BIOS
	          vendor: LENOVO
	          physical id: e
	          version: R12ET62W(1.32 )
	          date: 01/11/2023
	          size: 128KiB
	          capacity: 16MiB
	          capabilities: pci pnp upgrade shadowing cdboot bootselect edd int13floppy720 int5printscreen int9keyboard int14serial int17printer int10video acpi usb biosbootspecification uefi
	     *-pci:0
	          description: Host bridge
	          product: Raven/Raven2 Root Complex
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 100
	          bus info: pci@0000:00:00.0
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	        *-generic UNCLAIMED
	             description: IOMMU
	             product: Raven/Raven2 IOMMU
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 0.2
	             bus info: pci@0000:00:00.2
	             version: 00
	             width: 32 bits
	             clock: 33MHz
	             capabilities: msi ht cap_list
	             configuration: latency=0
	        *-pci:0
	             description: PCI bridge
	             product: Raven/Raven2 PCIe GPP Bridge [6:0]
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 1.2
	             bus info: pci@0000:00:01.2
	             version: 00
	             width: 32 bits
	             clock: 33MHz
	             capabilities: pci pm pciexpress msi ht normal_decode bus_master cap_list
	             configuration: driver=pcieport
	             resources: irq:26 ioport:4000(size=4096) memory:d0a00000-d0afffff ioport:d0b00000(size=2097152)
	           *-network
	                description: Wireless interface
	                product: Wireless-AC 9260
	                vendor: Intel Corporation
	                physical id: 0
	                bus info: pci@0000:01:00.0
	                logical name: wlp1s0
	                version: 29
	                serial: 40:74:e0:58:98:b9
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm msi pciexpress msix bus_master cap_list ethernet physical wireless
	                configuration: broadcast=yes driver=iwlwifi driverversion=5.15.0-78-generic firmware=46.fae53a8b.0 9260-th-b0-jf-b0- ip=10.10.10.115 latency=0 link=yes multicast=yes wireless=IEEE 802.11
	                resources: irq:80 memory:d0a00000-d0a03fff
	        *-pci:1
	             description: PCI bridge
	             product: Raven/Raven2 PCIe GPP Bridge [6:0]
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 1.3
	             bus info: pci@0000:00:01.3
	             version: 00
	             width: 32 bits
	             clock: 33MHz
	             capabilities: pci pm pciexpress msi ht normal_decode bus_master cap_list
	             configuration: driver=pcieport
	             resources: irq:27 ioport:5000(size=4096) memory:d0900000-d09fffff ioport:d0d00000(size=2097152)
	           *-nvme
	                description: NVMe device
	                product: INTEL SSDPEKKF256G8L
	                vendor: Intel Corporation
	                physical id: 0
	                bus info: pci@0000:02:00.0
	                logical name: /dev/nvme0
	                version: L15P
	                serial: PHHP93600D8W256B
	                width: 64 bits
	                clock: 33MHz
	                capabilities: nvme pm msi pciexpress msix nvm_express bus_master cap_list
	                configuration: driver=nvme latency=0 nqn=nqn.2014.08.org.nvmexpress:80868086PHHP93600D8W256B    INTEL SSDPEKKF256G8L state=live
	                resources: irq:48 memory:d0900000-d0903fff
	              *-namespace:0
	                   description: NVMe disk
	                   physical id: 0
	                   logical name: hwmon2
	              *-namespace:1
	                   description: NVMe disk
	                   physical id: 2
	                   logical name: /dev/ng0n1
	              *-namespace:2
	                   description: NVMe disk
	                   physical id: 1
	                   bus info: nvme@0:1
	                   logical name: /dev/nvme0n1
	                   size: 238GiB (256GB)
	                   capabilities: gpt-1.00 partitioned partitioned:gpt
	                   configuration: guid=7391280a-e75d-4cf7-857f-c2520e65b24b logicalsectorsize=512 sectorsize=512 wwid=eui.5cd2e4299140df43
	                 *-volume:0
	                      description: Windows FAT volume
	                      vendor: mkfs.fat
	                      physical id: 1
	                      bus info: nvme@0:1,1
	                      logical name: /dev/nvme0n1p1
	                      logical name: /boot/efi
	                      logical name: /boot/grub
	                      version: FAT32
	                      serial: 934b-67bb
	                      size: 510MiB
	                      capacity: 511MiB
	                      capabilities: boot fat initialized
	                      configuration: FATs=2 filesystem=fat mount.fstype=vfat mount.options=rw,relatime,fmask=0022,dmask=0022,codepage=437,iocharset=iso8859-1,shortname=mixed,errors=remount-ro name=EFI System Partition state=mounted
	                 *-volume:1
	                      description: Linux swap volume
	                      vendor: Linux
	                      physical id: 2
	                      bus info: nvme@0:1,2
	                      logical name: /dev/nvme0n1p2
	                      version: 1
	                      serial: 5ef17d43-ba9a-4bd4-915e-2236baeae457
	                      size: 2047MiB
	                      capacity: 2047MiB
	                      capabilities: nofs swap initialized
	                      configuration: filesystem=swap pagesize=4095
	                 *-volume:2
	                      description: boot partition
	                      vendor: Solaris
	                      physical id: 3
	                      bus info: nvme@0:1,3
	                      logical name: /dev/nvme0n1p3
	                      serial: 63a5b449-096a-9b45-99e7-f345c18cac67
	                      capacity: 2047MiB
	                      capabilities: boot
	                 *-volume:3
	                      description: root partition
	                      vendor: Solaris
	                      physical id: 4
	                      bus info: nvme@0:1,4
	                      logical name: /dev/nvme0n1p4
	                      serial: ee2a9422-0b2d-ac47-81c8-0d129f8ce37a
	                      capacity: 233GiB
	        *-pci:2
	             description: PCI bridge
	             product: Raven/Raven2 PCIe GPP Bridge [6:0]
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 1.4
	             bus info: pci@0000:00:01.4
	             version: 00
	             width: 32 bits
	             clock: 33MHz
	             capabilities: pci pm pciexpress msi ht normal_decode bus_master cap_list
	             configuration: driver=pcieport
	             resources: irq:28 ioport:3000(size=4096) memory:d0800000-d08fffff ioport:d0f00000(size=2097152)
	           *-network
	                description: Ethernet interface
	                product: RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller
	                vendor: Realtek Semiconductor Co., Ltd.
	                physical id: 0
	                bus info: pci@0000:03:00.0
	                logical name: enp3s0f0
	                version: 0e
	                serial: 98:fa:9b:b8:b8:c6
	                capacity: 1Gbit/s
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm msi pciexpress msix vpd bus_master cap_list ethernet physical tp mii 10bt 10bt-fd 100bt 100bt-fd 1000bt-fd autonegotiation
	                configuration: autonegotiation=on broadcast=yes driver=r8169 driverversion=5.15.0-78-generic latency=0 link=no multicast=yes port=twisted pair
	                resources: irq:47 ioport:3400(size=256) memory:d0814000-d0814fff memory:d0800000-d0803fff
	           *-communication:0
	                description: Serial controller
	                product: RTL8111xP UART #1
	                vendor: Realtek Semiconductor Co., Ltd.
	                physical id: 0.1
	                bus info: pci@0000:03:00.1
	                version: 0e
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm msi pciexpress msix vpd 16550 cap_list
	                configuration: driver=serial latency=0
	                resources: irq:32 ioport:3200(size=256) memory:d0815000-d0815fff memory:d0804000-d0807fff
	           *-communication:1
	                description: Serial controller
	                product: RTL8111xP UART #2
	                vendor: Realtek Semiconductor Co., Ltd.
	                physical id: 0.2
	                bus info: pci@0000:03:00.2
	                version: 0e
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm msi pciexpress msix vpd 16550 cap_list
	                configuration: driver=serial latency=0
	                resources: irq:33 ioport:3100(size=256) memory:d0816000-d0816fff memory:d0808000-d080bfff
	           *-serial UNCLAIMED
	                description: IPMI Interface
	                product: RTL8111xP IPMI interface
	                vendor: Realtek Semiconductor Co., Ltd.
	                physical id: 0.3
	                bus info: pci@0000:03:00.3
	                version: 0e
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm msi pciexpress msix vpd kcs cap_list
	                configuration: latency=0
	                resources: ioport:3000(size=256) memory:d0817000-d0817fff memory:d080c000-d080ffff
	           *-usb
	                description: USB controller
	                product: RTL811x EHCI host controller
	                vendor: Realtek Semiconductor Co., Ltd.
	                physical id: 0.4
	                bus info: pci@0000:03:00.4
	                version: 0e
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm msi pciexpress msix vpd ehci bus_master cap_list
	                configuration: driver=ehci-pci latency=0
	                resources: irq:35 memory:d0818000-d0818fff memory:d0810000-d0813fff
	              *-usbhost
	                   product: EHCI Host Controller
	                   vendor: Linux 5.15.0-78-generic ehci_hcd
	                   physical id: 1
	                   bus info: usb@1
	                   logical name: usb1
	                   version: 5.15
	                   capabilities: usb-2.00
	                   configuration: driver=hub slots=1 speed=480Mbit/s
	        *-pci:3
	             description: PCI bridge
	             product: Raven/Raven2 PCIe GPP Bridge [6:0]
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 1.6
	             bus info: pci@0000:00:01.6
	             version: 00
	             width: 32 bits
	             clock: 33MHz
	             capabilities: pci pm pciexpress msi ht normal_decode bus_master cap_list
	             configuration: driver=pcieport
	             resources: irq:29 ioport:2000(size=4096) memory:d0700000-d07fffff ioport:d1100000(size=2097152)
	           *-network
	                description: Ethernet interface
	                product: RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller
	                vendor: Realtek Semiconductor Co., Ltd.
	                physical id: 0
	                bus info: pci@0000:04:00.0
	                logical name: enp4s0
	                version: 10
	                serial: 98:fa:9b:b8:b8:c5
	                capacity: 1Gbit/s
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm msi pciexpress msix vpd bus_master cap_list ethernet physical tp mii 10bt 10bt-fd 100bt 100bt-fd 1000bt-fd autonegotiation
	                configuration: autonegotiation=on broadcast=yes driver=r8169 driverversion=5.15.0-78-generic firmware=rtl8168g-3_0.0.1 04/23/13 latency=0 link=no multicast=yes port=twisted pair
	                resources: irq:75 ioport:2000(size=256) memory:d0704000-d0704fff memory:d0700000-d0703fff
	        *-pci:4
	             description: PCI bridge
	             product: Raven/Raven2 PCIe GPP Bridge [6:0]
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 1.7
	             bus info: pci@0000:00:01.7
	             version: 00
	             width: 32 bits
	             clock: 33MHz
	             capabilities: pci pm pciexpress msi ht normal_decode bus_master cap_list
	             configuration: driver=pcieport
	             resources: irq:30 ioport:6000(size=4096) memory:d0600000-d06fffff ioport:d1300000(size=2097152)
	           *-generic
	                description: MMC Host
	                product: RTS522A PCI Express Card Reader
	                vendor: Realtek Semiconductor Co., Ltd.
	                physical id: 0
	                bus info: pci@0000:05:00.0
	                logical name: mmc0
	                version: 01
	                width: 32 bits
	                clock: 33MHz
	                capabilities: pm msi pciexpress bus_master cap_list
	                configuration: driver=rtsx_pci latency=0
	                resources: irq:37 memory:d0600000-d0600fff
	              *-device
	                   description: SD Card
	                   product: SA08G
	                   vendor: Kingston
	                   physical id: 1234
	                   logical name: /dev/mmcblk0
	                   version: 1.4
	                   date: 03/2015
	                   serial: 348749148
	                   size: 7388MiB (7746MB)
	                   capabilities: sd gpt-1.00 partitioned partitioned:gpt
	                   configuration: guid=77beb716-772e-4fb3-b471-f14699532ab9 logicalsectorsize=512 sectorsize=512
	                 *-volume
	                      description: EXT4 volume
	                      vendor: Linux
	                      physical id: 1
	                      logical name: /dev/mmcblk0p1
	                      logical name: /media/pjobson/721a316b-afc9-4e9b-b5c0-fd5ac05760c1
	                      version: 1.0
	                      serial: 721a316b-afc9-4e9b-b5c0-fd5ac05760c1
	                      size: 7386MiB
	                      capabilities: journaled extended_attributes large_files huge_files dir_nlink recover extents ext4 ext2 initialized
	                      configuration: created=2023-07-25 23:44:57 filesystem=ext4 modified=2023-07-27 21:27:02 mount.fstype=ext4 mount.options=rw,nosuid,nodev,relatime,errors=remount-ro mounted=2023-07-27 21:27:02 state=mounted
	        *-pci:5
	             description: PCI bridge
	             product: Raven/Raven2 Internal PCIe GPP Bridge 0 to Bus A
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 8.1
	             bus info: pci@0000:00:08.1
	             version: 00
	             width: 32 bits
	             clock: 33MHz
	             capabilities: pci pm pciexpress msi normal_decode bus_master cap_list
	             configuration: driver=pcieport
	             resources: irq:31 ioport:1000(size=4096) memory:d0200000-d05fffff ioport:c0000000(size=270532608)
	           *-display
	                description: VGA compatible controller
	                product: Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]
	                vendor: Advanced Micro Devices, Inc. [AMD/ATI]
	                physical id: 0
	                bus info: pci@0000:06:00.0
	                logical name: /dev/fb0
	                version: d2
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm pciexpress msi msix vga_controller bus_master cap_list fb
	                configuration: depth=32 driver=amdgpu latency=0 resolution=1920,1080
	                resources: irq:50 memory:c0000000-cfffffff memory:d0000000-d01fffff ioport:1000(size=256) memory:d0500000-d057ffff
	           *-multimedia:0
	                description: Audio device
	                product: Raven/Raven2/Fenghuang HDMI/DP Audio Controller
	                vendor: Advanced Micro Devices, Inc. [AMD/ATI]
	                physical id: 0.1
	                bus info: pci@0000:06:00.1
	                logical name: card0
	                logical name: /dev/snd/controlC0
	                logical name: /dev/snd/hwC0D0
	                logical name: /dev/snd/pcmC0D3p
	                logical name: /dev/snd/pcmC0D7p
	                logical name: /dev/snd/pcmC0D8p
	                version: 00
	                width: 32 bits
	                clock: 33MHz
	                capabilities: pm pciexpress msi bus_master cap_list
	                configuration: driver=snd_hda_intel latency=0
	                resources: irq:90 memory:d05c8000-d05cbfff
	              *-input:0
	                   product: HD-Audio Generic HDMI/DP,pcm=3
	                   physical id: 0
	                   logical name: input10
	                   logical name: /dev/input/event9
	              *-input:1
	                   product: HD-Audio Generic HDMI/DP,pcm=7
	                   physical id: 1
	                   logical name: input11
	                   logical name: /dev/input/event10
	              *-input:2
	                   product: HD-Audio Generic HDMI/DP,pcm=8
	                   physical id: 2
	                   logical name: input12
	                   logical name: /dev/input/event11
	           *-generic
	                description: Encryption controller
	                product: Family 17h (Models 10h-1fh) Platform Security Processor
	                vendor: Advanced Micro Devices, Inc. [AMD]
	                physical id: 0.2
	                bus info: pci@0000:06:00.2
	                version: 00
	                width: 32 bits
	                clock: 33MHz
	                capabilities: pm pciexpress msi msix bus_master cap_list
	                configuration: driver=ccp latency=0
	                resources: irq:78 memory:d0400000-d04fffff memory:d05cc000-d05cdfff
	           *-usb:0
	                description: USB controller
	                product: Raven USB 3.1
	                vendor: Advanced Micro Devices, Inc. [AMD]
	                physical id: 0.3
	                bus info: pci@0000:06:00.3
	                version: 00
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm pciexpress msi msix xhci bus_master cap_list
	                configuration: driver=xhci_hcd latency=0
	                resources: irq:38 memory:d0200000-d02fffff
	              *-usbhost:0
	                   product: xHCI Host Controller
	                   vendor: Linux 5.15.0-78-generic xhci-hcd
	                   physical id: 0
	                   bus info: usb@2
	                   logical name: usb2
	                   version: 5.15
	                   capabilities: usb-2.00
	                   configuration: driver=hub slots=4 speed=480Mbit/s
	                 *-usb
	                      description: Mouse
	                      product: Kensington USB/PS2 Wheel Mouse
	                      vendor: Kensington
	                      physical id: 3
	                      bus info: usb@2:3
	                      logical name: input18
	                      logical name: /dev/input/event15
	                      logical name: /dev/input/mouse2
	                      version: 4.00
	                      capabilities: usb-1.10 usb
	                      configuration: driver=usbhid maxpower=100mA speed=2Mbit/s
	              *-usbhost:1
	                   product: xHCI Host Controller
	                   vendor: Linux 5.15.0-78-generic xhci-hcd
	                   physical id: 1
	                   bus info: usb@3
	                   logical name: usb3
	                   version: 5.15
	                   capabilities: usb-3.10
	                   configuration: driver=hub slots=4 speed=10000Mbit/s
	           *-usb:1
	                description: USB controller
	                product: Raven USB 3.1
	                vendor: Advanced Micro Devices, Inc. [AMD]
	                physical id: 0.4
	                bus info: pci@0000:06:00.4
	                version: 00
	                width: 64 bits
	                clock: 33MHz
	                capabilities: pm pciexpress msi msix xhci bus_master cap_list
	                configuration: driver=xhci_hcd latency=0
	                resources: irq:50 memory:d0300000-d03fffff
	              *-usbhost:0
	                   product: xHCI Host Controller
	                   vendor: Linux 5.15.0-78-generic xhci-hcd
	                   physical id: 0
	                   bus info: usb@4
	                   logical name: usb4
	                   version: 5.15
	                   capabilities: usb-2.00
	                   configuration: driver=hub slots=2 speed=480Mbit/s
	                 *-usb:0
	                      description: Bluetooth wireless interface
	                      product: Wireless-AC 9260 Bluetooth Adapter
	                      vendor: Intel Corp.
	                      physical id: 1
	                      bus info: usb@4:1
	                      version: 0.02
	                      capabilities: bluetooth usb-2.00
	                      configuration: driver=btusb maxpower=100mA speed=12Mbit/s
	                 *-usb:1
	                      description: USB hub
	                      product: USB2.0 Hub
	                      vendor: Genesys Logic, Inc.
	                      physical id: 2
	                      bus info: usb@4:2
	                      version: 60.52
	                      capabilities: usb-2.00
	                      configuration: driver=hub maxpower=100mA slots=4 speed=480Mbit/s
	                    *-usb:0
	                         description: Video
	                         product: Integrated Camera: Integrated C
	                         vendor: Chicony Electronics Co.,Ltd.
	                         physical id: 1
	                         bus info: usb@4:2.1
	                         logical name: input13
	                         logical name: /dev/input/event12
	                         version: 0.27
	                         serial: 0001
	                         capabilities: usb-2.01 usb
	                         configuration: driver=uvcvideo maxpower=500mA speed=480Mbit/s
	                    *-usb:1 UNCLAIMED
	                         description: Generic USB device
	                         product: Prometheus MIS Touch Fingerprint Reader
	                         vendor: Synaptics, Inc.
	                         physical id: 4
	                         bus info: usb@4:2.4
	                         version: 0.00
	                         serial: 6952b6e21325
	                         capabilities: usb-2.00
	                         configuration: maxpower=100mA speed=12Mbit/s
	              *-usbhost:1
	                   product: xHCI Host Controller
	                   vendor: Linux 5.15.0-78-generic xhci-hcd
	                   physical id: 1
	                   bus info: usb@5
	                   logical name: usb5
	                   version: 5.15
	                   capabilities: usb-3.10
	                   configuration: driver=hub slots=1 speed=10000Mbit/s
	           *-multimedia:1
	                description: Multimedia controller
	                product: Raven/Raven2/FireFlight/Renoir Audio Processor
	                vendor: Advanced Micro Devices, Inc. [AMD]
	                physical id: 0.5
	                bus info: pci@0000:06:00.5
	                version: 00
	                width: 32 bits
	                clock: 33MHz
	                capabilities: pm pciexpress msi bus_master cap_list
	                configuration: driver=snd_pci_acp3x latency=0
	                resources: irq:88 memory:d0580000-d05bffff
	           *-multimedia:2
	                description: Audio device
	                product: Family 17h (Models 10h-1fh) HD Audio Controller
	                vendor: Advanced Micro Devices, Inc. [AMD]
	                physical id: 0.6
	                bus info: pci@0000:06:00.6
	                logical name: card1
	                logical name: /dev/snd/controlC1
	                logical name: /dev/snd/hwC1D0
	                logical name: /dev/snd/pcmC1D0c
	                logical name: /dev/snd/pcmC1D0p
	                version: 00
	                width: 32 bits
	                clock: 33MHz
	                capabilities: pm pciexpress msi bus_master cap_list
	                configuration: driver=snd_hda_intel latency=0
	                resources: irq:49 memory:d05c0000-d05c7fff
	              *-input:0
	                   product: HD-Audio Generic Mic
	                   physical id: 0
	                   logical name: input14
	                   logical name: /dev/input/event13
	              *-input:1
	                   product: HD-Audio Generic Headphone
	                   physical id: 1
	                   logical name: input15
	                   logical name: /dev/input/event14
	        *-serial
	             description: SMBus
	             product: FCH SMBus Controller
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 14
	             bus info: pci@0000:00:14.0
	             version: 61
	             width: 32 bits
	             clock: 66MHz
	             configuration: driver=piix4_smbus latency=0
	             resources: irq:0
	        *-isa
	             description: ISA bridge
	             product: FCH LPC Bridge
	             vendor: Advanced Micro Devices, Inc. [AMD]
	             physical id: 14.3
	             bus info: pci@0000:00:14.3
	             version: 51
	             width: 32 bits
	             clock: 66MHz
	             capabilities: isa bus_master
	             configuration: latency=0
	           *-pnp00:00
	                product: PnP device PNP0c02
	                physical id: 0
	                capabilities: pnp
	                configuration: driver=system
	           *-pnp00:01
	                product: PnP device PNP0b00
	                physical id: 1
	                capabilities: pnp
	                configuration: driver=rtc_cmos
	           *-pnp00:02
	                product: PnP device PNP0c02
	                physical id: 2
	                capabilities: pnp
	                configuration: driver=system
	           *-pnp00:03
	                product: PnP device PNP0c01
	                physical id: 3
	                capabilities: pnp
	                configuration: driver=system
	           *-pnp00:04
	                product: PnP device LEN0071
	                vendor: Lenovo Group Limited
	                physical id: 4
	                capabilities: pnp
	                configuration: driver=i8042 kbd
	           *-pnp00:05
	                product: PnP device LEN2062
	                vendor: Lenovo Group Limited
	                physical id: 5
	                capabilities: pnp
	                configuration: driver=i8042 aux
	     *-pci:1
	          description: Host bridge
	          product: Family 17h (Models 00h-1fh) PCIe Dummy Host Bridge
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 101
	          bus info: pci@0000:00:01.0
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	     *-pci:2
	          description: Host bridge
	          product: Family 17h (Models 00h-1fh) PCIe Dummy Host Bridge
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 102
	          bus info: pci@0000:00:08.0
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	     *-pci:3
	          description: Host bridge
	          product: Raven/Raven2 Device 24: Function 0
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 103
	          bus info: pci@0000:00:18.0
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	     *-pci:4
	          description: Host bridge
	          product: Raven/Raven2 Device 24: Function 1
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 104
	          bus info: pci@0000:00:18.1
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	     *-pci:5
	          description: Host bridge
	          product: Raven/Raven2 Device 24: Function 2
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 105
	          bus info: pci@0000:00:18.2
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	     *-pci:6
	          description: Host bridge
	          product: Raven/Raven2 Device 24: Function 3
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 106
	          bus info: pci@0000:00:18.3
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	          configuration: driver=k10temp
	          resources: irq:0
	     *-pci:7
	          description: Host bridge
	          product: Raven/Raven2 Device 24: Function 4
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 107
	          bus info: pci@0000:00:18.4
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	     *-pci:8
	          description: Host bridge
	          product: Raven/Raven2 Device 24: Function 5
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 108
	          bus info: pci@0000:00:18.5
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	     *-pci:9
	          description: Host bridge
	          product: Raven/Raven2 Device 24: Function 6
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 109
	          bus info: pci@0000:00:18.6
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	     *-pci:10
	          description: Host bridge
	          product: Raven/Raven2 Device 24: Function 7
	          vendor: Advanced Micro Devices, Inc. [AMD]
	          physical id: 10a
	          bus info: pci@0000:00:18.7
	          version: 00
	          width: 32 bits
	          clock: 33MHz
	  *-battery
	       product: 02DL008
	       vendor: SMP
	       physical id: 1
	       slot: Front
	       capacity: 50450mWh
	       configuration: voltage=11.5V
	  *-input:0
	       product: Power Button
	       physical id: 2
	       logical name: input0
	       logical name: /dev/input/event0
	       capabilities: platform
	  *-input:1
	       product: Lid Switch
	       physical id: 3
	       logical name: input1
	       logical name: /dev/input/event1
	       capabilities: platform
	  *-input:2
	       product: Sleep Button
	       physical id: 4
	       logical name: input2
	       logical name: /dev/input/event2
	       capabilities: platform
	  *-input:3
	       product: Power Button
	       physical id: 5
	       logical name: input3
	       logical name: /dev/input/event3
	       capabilities: platform
	  *-input:4
	       product: AT Translated Set 2 keyboard
	       physical id: 6
	       logical name: input4
	       logical name: /dev/input/event4
	       logical name: input4::capslock
	       logical name: input4::numlock
	       logical name: input4::scrolllock
	       capabilities: i8042
	  *-input:5
	       product: Video Bus
	       physical id: 7
	       logical name: input6
	       logical name: /dev/input/event5
	       capabilities: platform
	  *-input:6
	       product: SynPS/2 Synaptics TouchPad
	       physical id: 8
	       logical name: input7
	       logical name: /dev/input/event6
	       logical name: /dev/input/mouse0
	       capabilities: i8042
	  *-input:7
	       product: TPPS/2 Elan TrackPoint
	       physical id: 9
	       logical name: input8
	       logical name: /dev/input/event7
	       logical name: /dev/input/mouse1
	       capabilities: i8042
	  *-input:8
	       product: ThinkPad Extra Buttons
	       physical id: a
	       logical name: input9
	       logical name: /dev/input/event8
	       capabilities: platform
