# inxi info

Command line system information script for console and IRC

`inxi`

	CPU: quad core AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx (-MT MCP-)
	speed/min/max: 1877/1400/2100 MHz Kernel: 5.15.0-82-generic x86_64 Up: 4h 29m
	Mem: 12953.4/38008.8 MiB (34.1%) Storage: 465.04 GiB (4.8% used) Procs: 475
	Shell: Bash inxi: 3.3.13


`inxi --full`

	System:
	  Host: tpad Kernel: 5.15.0-82-generic x86_64 bits: 64
	    Desktop: Cinnamon 5.8.4 Distro: Linux Mint 21.2 Victoria
	Machine:
	  Type: Laptop System: LENOVO product: 20NKS0WA03 v: ThinkPad T495
	    serial: PF14FXAB
	  Mobo: LENOVO model: 20NKS0WA03 v: SDK0J40697 WIN serial: L1HF993044V
	    UEFI: LENOVO v: R12ET62W(1.32 ) date: 01/11/2023
	Battery:
	  ID-1: BAT0 charge: 46.7 Wh (100.0%) condition: 46.7/50.5 Wh (92.5%)
	CPU:
	  Info: quad core model: AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx
	    bits: 64 type: MT MCP cache: L2: 2 MiB
	  Speed (MHz): avg: 1575 min/max: 1400/2100 cores: 1: 2100 2: 1400 3: 1400
	    4: 1400 5: 1400 6: 2100 7: 1400 8: 1400
	Graphics:
	  Device-1: AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Mobile Series]
	    driver: amdgpu v: kernel
	  Device-2: Chicony Integrated Camera (1280x720@30) type: USB
	    driver: uvcvideo
	  Display: server: X.Org v: 1.21.1.4 driver: X: loaded: amdgpu,ati
	    unloaded: fbdev,modesetting,vesa gpu: amdgpu resolution: 1920x1080~60Hz
	  OpenGL: renderer: AMD Radeon Vega 8 Graphics (raven LLVM 15.0.7 DRM 3.42
	  5.15.0-82-generic)
	    v: 4.6 Mesa 23.0.4-0ubuntu1~22.04.1
	Audio:
	  Device-1: AMD Raven/Raven2/Fenghuang HDMI/DP Audio driver: snd_hda_intel
	  Device-2: AMD Raven/Raven2/FireFlight/Renoir Audio Processor
	    driver: snd_pci_acp3x
	  Device-3: AMD Family 17h HD Audio driver: snd_hda_intel
	  Sound Server-1: ALSA v: k5.15.0-82-generic running: yes
	  Sound Server-2: PulseAudio v: 15.99.1 running: yes
	  Sound Server-3: PipeWire v: 0.3.48 running: yes
	Network:
	  Device-1: Intel Wireless-AC 9260 driver: iwlwifi
	  IF: wlp1s0 state: up mac: 40:74:e0:58:98:b9
	  Device-2: Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet
	    driver: r8169
	  IF: enp3s0f0 state: down mac: 98:fa:9b:b8:b8:c6
	  Device-3: Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet
	    driver: r8169
	  IF: enp4s0 state: down mac: 98:fa:9b:b8:b8:c5
	Bluetooth:
	  Device-1: Intel Wireless-AC 9260 Bluetooth Adapter type: USB driver: btusb
	  Report: hciconfig ID: hci0 state: up address: 40:74:E0:58:98:BD bt-v: 3.0
	RAID:
	  Device-1: bpool type: zfs status: ONLINE level: linear raw: size: 1.88 GiB
	    free: 1.46 GiB zfs-fs: size: 1.75 GiB free: 1.33 GiB
	  Components: Online: N/A
	  Device-2: rpool type: zfs status: ONLINE level: linear raw: size: 232 GiB
	    free: 210 GiB zfs-fs: size: 224.81 GiB free: 202.74 GiB
	  Components: Online: N/A
	Drives:
	  Local Storage: total: raw: 238.47 GiB usable: 465.04 GiB
	    used: 22.43 GiB (4.8%)
	  ID-1: /dev/nvme0n1 vendor: Intel model: SSDPEKKF256G8L size: 238.47 GiB
	Partition:
	  ID-1: / size: 210.38 GiB used: 7.64 GiB (3.6%) fs: zfs
	    logical: rpool/ROOT/ubuntu_3z5a91
	  ID-2: /boot size: 1.75 GiB used: 426.8 MiB (23.8%) fs: zfs
	    logical: bpool/BOOT/ubuntu_3z5a91
	  ID-3: /boot/efi size: 511 MiB used: 14.3 MiB (2.8%) fs: vfat
	    dev: /dev/nvme0n1p1
	  ID-4: /var/log size: 202.75 GiB used: 8 MiB (0.0%) fs: zfs
	    logical: rpool/ROOT/ubuntu_3z5a91/var/log
	Swap:
	  ID-1: swap-1 type: partition size: 2 GiB used: 0 KiB (0.0%)
	    dev: /dev/nvme0n1p2
	Sensors:
	  System Temperatures: cpu: 53.0 C mobo: N/A gpu: amdgpu temp: 52.0 C
	  Fan Speeds (RPM): fan-1: 2700
	Info:
	  Processes: 475 Uptime: 4h 31m Memory: 37.12 GiB used: 12.66 GiB (34.1%)
	  Shell: Sudo inxi: 3.3.13

