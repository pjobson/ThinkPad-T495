# lspci info

lspci is a utility for displaying information about PCI buses in the system and devices connected to them.

`lspci -v`

	00:00.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Root Complex
		Subsystem: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Root Complex
		Flags: fast devsel
	
	00:00.2 IOMMU: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 IOMMU
		Subsystem: Lenovo Raven/Raven2 IOMMU
		Flags: bus master, fast devsel, latency 0, IRQ 25
		Capabilities: <access denied>
	
	00:01.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Family 17h (Models 00h-1fh) PCIe Dummy Host Bridge
		Flags: fast devsel, IOMMU group 0
	
	00:01.2 PCI bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 PCIe GPP Bridge [6:0] (prog-if 00 [Normal decode])
		Flags: bus master, fast devsel, latency 0, IRQ 26, IOMMU group 1
		Bus: primary=00, secondary=01, subordinate=01, sec-latency=0
		I/O behind bridge: 00004000-00004fff [size=4K]
		Memory behind bridge: d0a00000-d0afffff [size=1M]
		Prefetchable memory behind bridge: 00000000d0b00000-00000000d0cfffff [size=2M]
		Capabilities: <access denied>
		Kernel driver in use: pcieport
	
	00:01.3 PCI bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 PCIe GPP Bridge [6:0] (prog-if 00 [Normal decode])
		Flags: bus master, fast devsel, latency 0, IRQ 27, IOMMU group 2
		Bus: primary=00, secondary=02, subordinate=02, sec-latency=0
		I/O behind bridge: [disabled]
		Memory behind bridge: d0900000-d09fffff [size=1M]
		Prefetchable memory behind bridge: [disabled]
		Capabilities: <access denied>
		Kernel driver in use: pcieport
	
	00:01.4 PCI bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 PCIe GPP Bridge [6:0] (prog-if 00 [Normal decode])
		Flags: bus master, fast devsel, latency 0, IRQ 28, IOMMU group 3
		Bus: primary=00, secondary=03, subordinate=03, sec-latency=0
		I/O behind bridge: 00003000-00003fff [size=4K]
		Memory behind bridge: d0800000-d08fffff [size=1M]
		Prefetchable memory behind bridge: [disabled]
		Capabilities: <access denied>
		Kernel driver in use: pcieport
	
	00:01.6 PCI bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 PCIe GPP Bridge [6:0] (prog-if 00 [Normal decode])
		Flags: bus master, fast devsel, latency 0, IRQ 29, IOMMU group 4
		Bus: primary=00, secondary=04, subordinate=04, sec-latency=0
		I/O behind bridge: 00002000-00002fff [size=4K]
		Memory behind bridge: d0700000-d07fffff [size=1M]
		Prefetchable memory behind bridge: [disabled]
		Capabilities: <access denied>
		Kernel driver in use: pcieport
	
	00:01.7 PCI bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 PCIe GPP Bridge [6:0] (prog-if 00 [Normal decode])
		Flags: bus master, fast devsel, latency 0, IRQ 30, IOMMU group 5
		Bus: primary=00, secondary=05, subordinate=05, sec-latency=0
		I/O behind bridge: [disabled]
		Memory behind bridge: d0600000-d06fffff [size=1M]
		Prefetchable memory behind bridge: [disabled]
		Capabilities: <access denied>
		Kernel driver in use: pcieport
	
	00:08.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Family 17h (Models 00h-1fh) PCIe Dummy Host Bridge
		Flags: fast devsel, IOMMU group 6
	
	00:08.1 PCI bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Internal PCIe GPP Bridge 0 to Bus A (prog-if 00 [Normal decode])
		Flags: bus master, fast devsel, latency 0, IRQ 31, IOMMU group 7
		Bus: primary=00, secondary=06, subordinate=06, sec-latency=0
		I/O behind bridge: 00001000-00001fff [size=4K]
		Memory behind bridge: d0200000-d05fffff [size=4M]
		Prefetchable memory behind bridge: 00000000c0000000-00000000d01fffff [size=258M]
		Capabilities: <access denied>
		Kernel driver in use: pcieport
	
	00:14.0 SMBus: Advanced Micro Devices, Inc. [AMD] FCH SMBus Controller (rev 61)
		Subsystem: Lenovo FCH SMBus Controller
		Flags: 66MHz, medium devsel, IOMMU group 8
		Kernel driver in use: piix4_smbus
		Kernel modules: i2c_piix4, sp5100_tco
	
	00:14.3 ISA bridge: Advanced Micro Devices, Inc. [AMD] FCH LPC Bridge (rev 51)
		Subsystem: Lenovo FCH LPC Bridge
		Flags: bus master, 66MHz, medium devsel, latency 0, IOMMU group 8
	
	00:18.0 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Device 24: Function 0
		Flags: fast devsel, IOMMU group 9
	
	00:18.1 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Device 24: Function 1
		Flags: fast devsel, IOMMU group 9
	
	00:18.2 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Device 24: Function 2
		Flags: fast devsel, IOMMU group 9
	
	00:18.3 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Device 24: Function 3
		Flags: fast devsel, IOMMU group 9
		Kernel driver in use: k10temp
		Kernel modules: k10temp
	
	00:18.4 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Device 24: Function 4
		Flags: fast devsel, IOMMU group 9
	
	00:18.5 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Device 24: Function 5
		Flags: fast devsel, IOMMU group 9
	
	00:18.6 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Device 24: Function 6
		Flags: fast devsel, IOMMU group 9
	
	00:18.7 Host bridge: Advanced Micro Devices, Inc. [AMD] Raven/Raven2 Device 24: Function 7
		Flags: fast devsel, IOMMU group 9
	
	01:00.0 Network controller: Intel Corporation Wireless-AC 9260 (rev 29)
		Subsystem: Intel Corporation Wireless-AC 9260
		Physical Slot: 0
		Flags: bus master, fast devsel, latency 0, IRQ 81, IOMMU group 10
		Memory at d0a00000 (64-bit, non-prefetchable) [size=16K]
		Capabilities: <access denied>
		Kernel driver in use: iwlwifi
		Kernel modules: iwlwifi
	
	02:00.0 Non-Volatile memory controller: Intel Corporation SSD Pro 7600p/760p/E 6100p Series (rev 03) (prog-if 02 [NVM Express])
		Subsystem: Intel Corporation SSD Pro 7600p/760p/E 6100p Series [NVM Express]
		Flags: bus master, fast devsel, latency 0, IRQ 48, NUMA node 0, IOMMU group 11
		Memory at d0900000 (64-bit, non-prefetchable) [size=16K]
		Capabilities: <access denied>
		Kernel driver in use: nvme
		Kernel modules: nvme
	
	03:00.0 Ethernet controller: Realtek Semiconductor Co., Ltd. RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller (rev 0e)
		Subsystem: Lenovo RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller
		Flags: bus master, fast devsel, latency 0, IRQ 38, IOMMU group 12
		I/O ports at 3400 [size=256]
		Memory at d0814000 (64-bit, non-prefetchable) [size=4K]
		Memory at d0800000 (64-bit, non-prefetchable) [size=16K]
		Capabilities: <access denied>
		Kernel driver in use: r8169
		Kernel modules: r8169
	
	03:00.1 Serial controller: Realtek Semiconductor Co., Ltd. RTL8111xP UART #1 (rev 0e) (prog-if 02 [16550])
		Subsystem: Lenovo RTL8111xP UART
		Flags: fast devsel, IRQ 32, IOMMU group 12
		I/O ports at 3200 [size=256]
		Memory at d0815000 (64-bit, non-prefetchable) [size=4K]
		Memory at d0804000 (64-bit, non-prefetchable) [size=16K]
		Capabilities: <access denied>
		Kernel driver in use: serial
	
	03:00.2 Serial controller: Realtek Semiconductor Co., Ltd. RTL8111xP UART #2 (rev 0e) (prog-if 02 [16550])
		Subsystem: Lenovo RTL8111xP UART
		Flags: fast devsel, IRQ 33, IOMMU group 12
		I/O ports at 3100 [size=256]
		Memory at d0816000 (64-bit, non-prefetchable) [size=4K]
		Memory at d0808000 (64-bit, non-prefetchable) [size=16K]
		Capabilities: <access denied>
		Kernel driver in use: serial
	
	03:00.3 IPMI Interface: Realtek Semiconductor Co., Ltd. RTL8111xP IPMI interface (rev 0e) (prog-if 01 [KCS])
		Subsystem: Lenovo RTL8111xP IPMI interface
		Flags: fast devsel, IRQ 255, IOMMU group 12
		I/O ports at 3000 [disabled] [size=256]
		Memory at d0817000 (64-bit, non-prefetchable) [disabled] [size=4K]
		Memory at d080c000 (64-bit, non-prefetchable) [disabled] [size=16K]
		Capabilities: <access denied>
		Kernel modules: ipmi_si
	
	03:00.4 USB controller: Realtek Semiconductor Co., Ltd. RTL811x EHCI host controller (rev 0e) (prog-if 20 [EHCI])
		Subsystem: Lenovo RTL811x EHCI host controller
		Flags: bus master, fast devsel, latency 0, IRQ 35, IOMMU group 12
		Memory at d0818000 (32-bit, non-prefetchable) [size=4K]
		Memory at d0810000 (64-bit, non-prefetchable) [size=16K]
		Capabilities: <access denied>
		Kernel driver in use: ehci-pci
	
	04:00.0 Ethernet controller: Realtek Semiconductor Co., Ltd. RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller (rev 10)
		Subsystem: Lenovo RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller
		Flags: bus master, fast devsel, latency 0, IRQ 75, IOMMU group 13
		I/O ports at 2000 [size=256]
		Memory at d0704000 (64-bit, non-prefetchable) [size=4K]
		Memory at d0700000 (64-bit, non-prefetchable) [size=16K]
		Capabilities: <access denied>
		Kernel driver in use: r8169
		Kernel modules: r8169
	
	05:00.0 Unassigned class [ff00]: Realtek Semiconductor Co., Ltd. RTS522A PCI Express Card Reader (rev 01)
		Subsystem: Lenovo RTS522A PCI Express Card Reader
		Flags: bus master, fast devsel, latency 0, IRQ 37, IOMMU group 14
		Memory at d0600000 (32-bit, non-prefetchable) [size=4K]
		Capabilities: <access denied>
		Kernel driver in use: rtsx_pci
		Kernel modules: rtsx_pci
	
	06:00.0 VGA compatible controller: Advanced Micro Devices, Inc. [AMD/ATI] Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] (rev d2) (prog-if 00 [VGA controller])
		Subsystem: Lenovo Picasso
		Flags: bus master, fast devsel, latency 0, IRQ 65, IOMMU group 15
		Memory at c0000000 (64-bit, prefetchable) [size=256M]
		Memory at d0000000 (64-bit, prefetchable) [size=2M]
		I/O ports at 1000 [size=256]
		Memory at d0500000 (32-bit, non-prefetchable) [size=512K]
		Capabilities: <access denied>
		Kernel driver in use: amdgpu
		Kernel modules: amdgpu
	
	06:00.1 Audio device: Advanced Micro Devices, Inc. [AMD/ATI] Raven/Raven2/Fenghuang HDMI/DP Audio Controller
		Subsystem: Lenovo Raven/Raven2/Fenghuang HDMI/DP Audio Controller
		Flags: bus master, fast devsel, latency 0, IRQ 89, IOMMU group 16
		Memory at d05c8000 (32-bit, non-prefetchable) [size=16K]
		Capabilities: <access denied>
		Kernel driver in use: snd_hda_intel
		Kernel modules: snd_hda_intel
	
	06:00.2 Encryption controller: Advanced Micro Devices, Inc. [AMD] Family 17h (Models 10h-1fh) Platform Security Processor
		Subsystem: Lenovo Family 17h (Models 10h-1fh) Platform Security Processor
		Flags: bus master, fast devsel, latency 0, IRQ 78, IOMMU group 16
		Memory at d0400000 (32-bit, non-prefetchable) [size=1M]
		Memory at d05cc000 (32-bit, non-prefetchable) [size=8K]
		Capabilities: <access denied>
		Kernel driver in use: ccp
		Kernel modules: ccp
	
	06:00.3 USB controller: Advanced Micro Devices, Inc. [AMD] Raven USB 3.1 (prog-if 30 [XHCI])
		Subsystem: Lenovo Raven USB 3.1
		Flags: bus master, fast devsel, latency 0, IRQ 39, IOMMU group 16
		Memory at d0200000 (64-bit, non-prefetchable) [size=1M]
		Capabilities: <access denied>
		Kernel driver in use: xhci_hcd
		Kernel modules: xhci_pci
	
	06:00.4 USB controller: Advanced Micro Devices, Inc. [AMD] Raven USB 3.1 (prog-if 30 [XHCI])
		Subsystem: Lenovo Raven USB 3.1
		Flags: bus master, fast devsel, latency 0, IRQ 65, IOMMU group 16
		Memory at d0300000 (64-bit, non-prefetchable) [size=1M]
		Capabilities: <access denied>
		Kernel driver in use: xhci_hcd
		Kernel modules: xhci_pci
	
	06:00.5 Multimedia controller: Advanced Micro Devices, Inc. [AMD] Raven/Raven2/FireFlight/Renoir Audio Processor
		Subsystem: Lenovo Raven/Raven2/FireFlight/Renoir Audio Processor
		Flags: bus master, fast devsel, latency 0, IRQ 88, IOMMU group 16
		Memory at d0580000 (32-bit, non-prefetchable) [size=256K]
		Capabilities: <access denied>
		Kernel driver in use: snd_pci_acp3x
		Kernel modules: snd_pci_acp3x, snd_rn_pci_acp3x, snd_pci_acp5x, snd_pci_acp6x
	
	06:00.6 Audio device: Advanced Micro Devices, Inc. [AMD] Family 17h (Models 10h-1fh) HD Audio Controller
		Subsystem: Lenovo Family 17h (Models 10h-1fh) HD Audio Controller
		Flags: bus master, fast devsel, latency 0, IRQ 90, IOMMU group 16
		Memory at d05c0000 (32-bit, non-prefetchable) [size=32K]
		Capabilities: <access denied>
		Kernel driver in use: snd_hda_intel
		Kernel modules: snd_hda_intel



