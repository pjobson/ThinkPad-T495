# pactl Info

pactl can be used to issue control commands to the PulseAudio sound server.

`pactl list`

	Module #0
		Name: module-device-restore
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Automatically restore the volume/mute state of devices"
			module.version = "15.99.1"
	
	Module #1
		Name: module-stream-restore
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Automatically restore the volume/mute/device state of streams"
			module.version = "15.99.1"
	
	Module #2
		Name: module-card-restore
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Automatically restore profile of cards"
			module.version = "15.99.1"
	
	Module #3
		Name: module-augment-properties
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Augment the property sets of streams with additional static information"
			module.version = "15.99.1"
	
	Module #4
		Name: module-switch-on-port-available
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "David Henningsson"
			module.description = "Switches ports and profiles when devices are plugged/unplugged"
			module.version = "15.99.1"
	
	Module #5
		Name: module-switch-on-connect
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Michael Terry"
			module.description = "When a sink/source is added, switch to it or conditionally switch to it"
			module.version = "15.99.1"
	
	Module #6
		Name: module-udev-detect
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Detect available audio hardware and load matching drivers"
			module.version = "15.99.1"
	
	Module #7
		Name: module-alsa-card
		Argument: device_id="0" name="pci-0000_06_00.1" card_name="alsa_card.pci-0000_06_00.1" namereg_fail=false tsched=yes fixed_latency_range=no ignore_dB=no deferred_volume=yes use_ucm=yes avoid_resampling=no card_properties="module-udev-detect.discovered=1"
		Usage counter: 0
		Properties:
			module.author = "Lennart Poettering"
			module.description = "ALSA Card"
			module.version = "15.99.1"
	
	Module #8
		Name: module-alsa-card
		Argument: device_id="1" name="pci-0000_06_00.6" card_name="alsa_card.pci-0000_06_00.6" namereg_fail=false tsched=yes fixed_latency_range=no ignore_dB=no deferred_volume=yes use_ucm=yes avoid_resampling=no card_properties="module-udev-detect.discovered=1"
		Usage counter: 2
		Properties:
			module.author = "Lennart Poettering"
			module.description = "ALSA Card"
			module.version = "15.99.1"
	
	Module #9
		Name: module-bluetooth-policy
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Frédéric Dalleau, Pali Rohár"
			module.description = "Policy module to make using bluetooth devices out-of-the-box easier"
			module.version = "15.99.1"
	
	Module #10
		Name: module-bluetooth-discover
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "João Paulo Rechi Vita"
			module.description = "Detect available Bluetooth daemon and load the corresponding discovery module"
			module.version = "15.99.1"
	
	Module #11
		Name: module-bluez5-discover
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "João Paulo Rechi Vita"
			module.description = "Detect available BlueZ 5 Bluetooth audio devices and load BlueZ 5 Bluetooth audio drivers"
			module.version = "15.99.1"
	
	Module #12
		Name: module-native-protocol-unix
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Native protocol (UNIX sockets)"
			module.version = "15.99.1"
	
	Module #13
		Name: module-default-device-restore
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Automatically restore the default sink and source"
			module.version = "15.99.1"
	
	Module #14
		Name: module-always-sink
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Colin Guthrie"
			module.description = "Always keeps at least one sink loaded even if it's a null one"
			module.version = "15.99.1"
	
	Module #15
		Name: module-intended-roles
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Automatically set device of streams based on intended roles of devices"
			module.version = "15.99.1"
	
	Module #16
		Name: module-suspend-on-idle
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "When a sink/source is idle for too long, suspend it"
			module.version = "15.99.1"
	
	Module #17
		Name: module-systemd-login
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Create a client for each login session of this user"
			module.version = "15.99.1"
	
	Module #18
		Name: module-position-event-sounds
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Position event sounds between L and R depending on the position on screen of the widget triggering them."
			module.version = "15.99.1"
	
	Module #19
		Name: module-role-cork
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Mute & cork streams with certain roles while others exist"
			module.version = "15.99.1"
	
	Module #20
		Name: module-snap-policy
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Canonical Ltd"
			module.description = "Ubuntu Snap policy management"
			module.version = "15.99.1"
	
	Module #21
		Name: module-filter-heuristics
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Colin Guthrie"
			module.description = "Detect when various filters are desirable"
			module.version = "15.99.1"
	
	Module #22
		Name: module-filter-apply
		Argument: 
		Usage counter: n/a
		Properties:
			module.author = "Colin Guthrie"
			module.description = "Load filter sinks automatically when needed"
			module.version = "15.99.1"
	
	Module #23
		Name: module-x11-publish
		Argument: display=:0 xauthority=/home/pjobson/.Xauthority
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "X11 credential publisher"
			module.version = "15.99.1"
	
	Module #24
		Name: module-x11-cork-request
		Argument: display=:0 xauthority=/home/pjobson/.Xauthority
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "Synthesize X11 media key events when cork/uncork is requested"
			module.version = "15.99.1"
	
	Module #25
		Name: module-x11-xsmp
		Argument: display=:0 xauthority=/home/pjobson/.Xauthority session_manager=local/tpad:@/tmp/.ICE-unix/3071,unix/tpad:/tmp/.ICE-unix/3071
		Usage counter: n/a
		Properties:
			module.author = "Lennart Poettering"
			module.description = "X11 session management"
			module.version = "15.99.1"
	
	Sink #0
		State: RUNNING
		Name: alsa_output.pci-0000_06_00.6.analog-stereo
		Description: Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo
		Driver: module-alsa-card.c
		Sample Specification: s16le 2ch 48000Hz
		Channel Map: front-left,front-right
		Owner Module: 8
		Mute: no
		Volume: front-left: 65536 / 100% / 0.00 dB,   front-right: 65536 / 100% / 0.00 dB
		        balance 0.00
		Base Volume: 65536 / 100% / 0.00 dB
		Monitor Source: alsa_output.pci-0000_06_00.6.analog-stereo.monitor
		Latency: 36612 usec, configured 36000 usec
		Flags: HARDWARE HW_MUTE_CTRL HW_VOLUME_CTRL DECIBEL_VOLUME LATENCY 
		Properties:
			alsa.resolution_bits = "16"
			device.api = "alsa"
			device.class = "sound"
			alsa.class = "generic"
			alsa.subclass = "generic-mix"
			alsa.name = "ALC257 Analog"
			alsa.id = "ALC257 Analog"
			alsa.subdevice = "0"
			alsa.subdevice_name = "subdevice #0"
			alsa.device = "0"
			alsa.card = "1"
			alsa.card_name = "HD-Audio Generic"
			alsa.long_card_name = "HD-Audio Generic at 0xd05c0000 irq 90"
			alsa.driver_name = "snd_hda_intel"
			device.bus_path = "pci-0000:06:00.6"
			sysfs.path = "/devices/pci0000:00/0000:00:08.1/0000:06:00.6/sound/card1"
			device.bus = "pci"
			device.vendor.id = "1022"
			device.vendor.name = "Advanced Micro Devices, Inc. [AMD]"
			device.product.id = "15e3"
			device.product.name = "Family 17h (Models 10h-1fh) HD Audio Controller"
			device.string = "front:1"
			device.buffering.buffer_size = "352768"
			device.buffering.fragment_size = "176384"
			device.access_mode = "mmap+timer"
			device.profile.name = "analog-stereo"
			device.profile.description = "Analog Stereo"
			device.description = "Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo"
			module-udev-detect.discovered = "1"
			device.icon_name = "audio-card-pci"
		Ports:
			analog-output-speaker: Speakers (type: Speaker, priority: 10000, availability unknown)
			analog-output-headphones: Headphones (type: Headphones, priority: 9900, not available)
		Active Port: analog-output-speaker
		Formats:
			pcm
	
	Source #0
		State: IDLE
		Name: alsa_output.pci-0000_06_00.6.analog-stereo.monitor
		Description: Monitor of Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo
		Driver: module-alsa-card.c
		Sample Specification: s16le 2ch 48000Hz
		Channel Map: front-left,front-right
		Owner Module: 8
		Mute: no
		Volume: front-left: 65536 / 100% / 0.00 dB,   front-right: 65536 / 100% / 0.00 dB
		        balance 0.00
		Base Volume: 65536 / 100% / 0.00 dB
		Monitor of Sink: alsa_output.pci-0000_06_00.6.analog-stereo
		Latency: 0 usec, configured 1837333 usec
		Flags: DECIBEL_VOLUME LATENCY 
		Properties:
			device.description = "Monitor of Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo"
			device.class = "monitor"
			alsa.card = "1"
			alsa.card_name = "HD-Audio Generic"
			alsa.long_card_name = "HD-Audio Generic at 0xd05c0000 irq 90"
			alsa.driver_name = "snd_hda_intel"
			device.bus_path = "pci-0000:06:00.6"
			sysfs.path = "/devices/pci0000:00/0000:00:08.1/0000:06:00.6/sound/card1"
			device.bus = "pci"
			device.vendor.id = "1022"
			device.vendor.name = "Advanced Micro Devices, Inc. [AMD]"
			device.product.id = "15e3"
			device.product.name = "Family 17h (Models 10h-1fh) HD Audio Controller"
			device.string = "1"
			module-udev-detect.discovered = "1"
			device.icon_name = "audio-card-pci"
		Formats:
			pcm
	
	Source #1
		State: SUSPENDED
		Name: alsa_input.pci-0000_06_00.6.analog-stereo
		Description: Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo
		Driver: module-alsa-card.c
		Sample Specification: s16le 2ch 44100Hz
		Channel Map: front-left,front-right
		Owner Module: 8
		Mute: no
		Volume: front-left: 10387 /  16% / -48.00 dB,   front-right: 10387 /  16% / -48.00 dB
		        balance 0.00
		Base Volume: 6554 /  10% / -60.00 dB
		Monitor of Sink: n/a
		Latency: 0 usec, configured 0 usec
		Flags: HARDWARE HW_MUTE_CTRL HW_VOLUME_CTRL DECIBEL_VOLUME LATENCY 
		Properties:
			alsa.resolution_bits = "16"
			device.api = "alsa"
			device.class = "sound"
			alsa.class = "generic"
			alsa.subclass = "generic-mix"
			alsa.name = "ALC257 Analog"
			alsa.id = "ALC257 Analog"
			alsa.subdevice = "0"
			alsa.subdevice_name = "subdevice #0"
			alsa.device = "0"
			alsa.card = "1"
			alsa.card_name = "HD-Audio Generic"
			alsa.long_card_name = "HD-Audio Generic at 0xd05c0000 irq 90"
			alsa.driver_name = "snd_hda_intel"
			device.bus_path = "pci-0000:06:00.6"
			sysfs.path = "/devices/pci0000:00/0000:00:08.1/0000:06:00.6/sound/card1"
			device.bus = "pci"
			device.vendor.id = "1022"
			device.vendor.name = "Advanced Micro Devices, Inc. [AMD]"
			device.product.id = "15e3"
			device.product.name = "Family 17h (Models 10h-1fh) HD Audio Controller"
			device.string = "front:1"
			device.buffering.buffer_size = "352768"
			device.buffering.fragment_size = "176384"
			device.access_mode = "mmap+timer"
			device.profile.name = "analog-stereo"
			device.profile.description = "Analog Stereo"
			device.description = "Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo"
			module-udev-detect.discovered = "1"
			device.icon_name = "audio-card-pci"
		Ports:
			analog-input-internal-mic: Internal Microphone (type: Mic, priority: 8900, availability unknown)
			analog-input-mic: Microphone (type: Mic, priority: 8700, not available)
		Active Port: analog-input-internal-mic
		Formats:
			pcm
	
	Sink Input #54
		Driver: protocol-native.c
		Owner Module: 12
		Client: 9
		Sink: 0
		Sample Specification: float32le 2ch 48000Hz
		Channel Map: front-left,front-right
		Format: pcm, format.sample_format = "\"float32le\""  format.rate = "48000"  format.channels = "2"  format.channel_map = "\"front-left,front-right\""
		Corked: no
		Mute: no
		Volume: front-left: 65536 / 100% / 0.00 dB,   front-right: 65536 / 100% / 0.00 dB
		        balance 0.00
		Buffer Latency: 42187 usec
		Sink Latency: 36150 usec
		Resample method: copy
		Properties:
			media.name = "AudioCallbackDriver"
			application.name = "Firefox"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.process.id = "4592"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "firefox-bin"
			application.language = "en_US.UTF-8"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			application.process.session_id = "c2"
			module-stream-restore.id = "sink-input-by-application-name:Firefox"
	
	Sink Input #663
		Driver: protocol-native.c
		Owner Module: 12
		Client: 20
		Sink: 0
		Sample Specification: s16le 1ch 44100Hz
		Channel Map: mono
		Format: pcm, format.sample_format = "\"s16le\""  format.rate = "44100"  format.channels = "1"  format.channel_map = "\"mono\""
		Corked: no
		Mute: no
		Volume: mono: 65536 / 100% / 0.00 dB
		        balance 0.00
		Buffer Latency: 0 usec
		Sink Latency: 36046 usec
		Resample method: speex-float-1
		Properties:
			media.name = "playback"
			application.name = "speech-dispatcher-dummy"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.process.id = "2114951"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "sd_dummy"
			application.language = "C"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			module-stream-restore.id = "sink-input-by-application-name:speech-dispatcher-dummy"
	
	Client #0
		Driver: module-systemd-login.c
		Owner Module: 17
		Properties:
			application.name = "Login Session c2"
			systemd-login.session = "c2"
	
	Client #4
		Driver: module-x11-xsmp.c
		Owner Module: 25
		Properties:
			application.name = "XSMP Session on cinnamon-session as 10ed97ee0a13fc22c6169050762146502000000030710047"
			xsmp.vendor = "cinnamon-session"
			xsmp.client.id = "10ed97ee0a13fc22c6169050762146502000000030710047"
	
	Client #5
		Driver: protocol-native.c
		Owner Module: 12
		Properties:
			application.name = "Cinnamon Volume Control Media Keys"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.id = "org.gnome.VolumeControl"
			application.icon_name = "multimedia-volume-control"
			application.version = "5.8.0"
			application.process.id = "3391"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "csd-media-keys"
			application.language = "en_US.UTF-8"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			application.process.session_id = "c2"
	
	Client #6
		Driver: protocol-native.c
		Owner Module: 12
		Properties:
			application.name = "Cinnamon Volume Control"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.id = "org.gnome.VolumeControl"
			application.icon_name = "multimedia-volume-control"
			application.version = "5.8.0"
			application.process.id = "3561"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "cinnamon"
			application.language = "en_US.UTF-8"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			application.process.session_id = "c2"
	
	Client #7
		Driver: protocol-native.c
		Owner Module: 12
		Properties:
			application.name = "Muffin"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.process.id = "3561"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "cinnamon"
			application.language = "en_US.UTF-8"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			application.process.session_id = "c2"
	
	Client #9
		Driver: protocol-native.c
		Owner Module: 12
		Properties:
			application.name = "Firefox"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.process.id = "4592"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "firefox-bin"
			application.language = "en_US.UTF-8"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			application.process.session_id = "c2"
	
	Client #16
		Driver: module-systemd-login.c
		Owner Module: 17
		Properties:
			application.name = "Login Session 72"
			systemd-login.session = "72"
	
	Client #20
		Driver: protocol-native.c
		Owner Module: 12
		Properties:
			application.name = "speech-dispatcher-dummy"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.process.id = "2114951"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "sd_dummy"
			application.language = "C"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
	
	Client #25
		Driver: protocol-native.c
		Owner Module: 12
		Properties:
			application.name = "WEBRTC VoiceEngine"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.process.id = "3069137"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "Discord"
			application.language = "en_US.UTF-8"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			application.process.session_id = "c2"
	
	Client #26
		Driver: protocol-native.c
		Owner Module: 12
		Properties:
			application.name = "Chromium input"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.process.id = "3070102"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "Discord"
			application.language = "en_US.UTF-8"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			application.process.session_id = "c2"
	
	Client #57
		Driver: protocol-native.c
		Owner Module: 12
		Properties:
			application.name = "pactl"
			native-protocol.peer = "UNIX socket client"
			native-protocol.version = "35"
			application.process.id = "237853"
			application.process.user = "pjobson"
			application.process.host = "tpad"
			application.process.binary = "pactl"
			application.language = "en_US.UTF-8"
			window.x11.display = ":0"
			application.process.machine_id = "e7d0df732b0649e49e97a4d764308014"
			application.process.session_id = "c2"
	
	Card #0
		Name: alsa_card.pci-0000_06_00.1
		Driver: module-alsa-card.c
		Owner Module: 7
		Properties:
			alsa.card = "0"
			alsa.card_name = "HD-Audio Generic"
			alsa.long_card_name = "HD-Audio Generic at 0xd05c8000 irq 89"
			alsa.driver_name = "snd_hda_intel"
			device.bus_path = "pci-0000:06:00.1"
			sysfs.path = "/devices/pci0000:00/0000:00:08.1/0000:06:00.1/sound/card0"
			device.bus = "pci"
			device.vendor.id = "1002"
			device.vendor.name = "Advanced Micro Devices, Inc. [AMD/ATI]"
			device.product.id = "15de"
			device.product.name = "Raven/Raven2/Fenghuang HDMI/DP Audio Controller"
			device.string = "0"
			device.description = "Raven/Raven2/Fenghuang HDMI/DP Audio Controller"
			module-udev-detect.discovered = "1"
			device.icon_name = "audio-card-pci"
		Profiles:
			output:hdmi-stereo: Digital Stereo (HDMI) Output (sinks: 1, sources: 0, priority: 5900, available: no)
			output:hdmi-surround: Digital Surround 5.1 (HDMI) Output (sinks: 1, sources: 0, priority: 800, available: no)
			output:hdmi-surround71: Digital Surround 7.1 (HDMI) Output (sinks: 1, sources: 0, priority: 800, available: no)
			output:hdmi-stereo-extra1: Digital Stereo (HDMI 2) Output (sinks: 1, sources: 0, priority: 5700, available: no)
			output:hdmi-surround-extra1: Digital Surround 5.1 (HDMI 2) Output (sinks: 1, sources: 0, priority: 600, available: no)
			output:hdmi-surround71-extra1: Digital Surround 7.1 (HDMI 2) Output (sinks: 1, sources: 0, priority: 600, available: no)
			output:hdmi-stereo-extra2: Digital Stereo (HDMI 3) Output (sinks: 1, sources: 0, priority: 5700, available: no)
			output:hdmi-surround-extra2: Digital Surround 5.1 (HDMI 3) Output (sinks: 1, sources: 0, priority: 600, available: no)
			output:hdmi-surround71-extra2: Digital Surround 7.1 (HDMI 3) Output (sinks: 1, sources: 0, priority: 600, available: no)
			off: Off (sinks: 0, sources: 0, priority: 0, available: yes)
		Active Profile: off
		Ports:
			hdmi-output-0: HDMI / DisplayPort (type: HDMI, priority: 5900, latency offset: 0 usec, not available)
				Properties:
					device.icon_name = "video-display"
				Part of profile(s): output:hdmi-stereo, output:hdmi-surround, output:hdmi-surround71
			hdmi-output-1: HDMI / DisplayPort 2 (type: HDMI, priority: 5800, latency offset: 0 usec, not available)
				Properties:
					device.icon_name = "video-display"
				Part of profile(s): output:hdmi-stereo-extra1, output:hdmi-surround-extra1, output:hdmi-surround71-extra1
			hdmi-output-2: HDMI / DisplayPort 3 (type: HDMI, priority: 5700, latency offset: 0 usec, not available)
				Properties:
					device.icon_name = "video-display"
				Part of profile(s): output:hdmi-stereo-extra2, output:hdmi-surround-extra2, output:hdmi-surround71-extra2
	
	Card #1
		Name: alsa_card.pci-0000_06_00.6
		Driver: module-alsa-card.c
		Owner Module: 8
		Properties:
			alsa.card = "1"
			alsa.card_name = "HD-Audio Generic"
			alsa.long_card_name = "HD-Audio Generic at 0xd05c0000 irq 90"
			alsa.driver_name = "snd_hda_intel"
			device.bus_path = "pci-0000:06:00.6"
			sysfs.path = "/devices/pci0000:00/0000:00:08.1/0000:06:00.6/sound/card1"
			device.bus = "pci"
			device.vendor.id = "1022"
			device.vendor.name = "Advanced Micro Devices, Inc. [AMD]"
			device.product.id = "15e3"
			device.product.name = "Family 17h (Models 10h-1fh) HD Audio Controller"
			device.string = "1"
			device.description = "Family 17h (Models 10h-1fh) HD Audio Controller"
			module-udev-detect.discovered = "1"
			device.icon_name = "audio-card-pci"
		Profiles:
			input:analog-stereo: Analog Stereo Input (sinks: 0, sources: 1, priority: 32833, available: yes)
			output:analog-stereo: Analog Stereo Output (sinks: 1, sources: 0, priority: 39268, available: yes)
			output:analog-stereo+input:analog-stereo: Analog Stereo Duplex (sinks: 1, sources: 1, priority: 39333, available: yes)
			off: Off (sinks: 0, sources: 0, priority: 0, available: yes)
		Active Profile: output:analog-stereo+input:analog-stereo
		Ports:
			analog-input-internal-mic: Internal Microphone (type: Mic, priority: 8900, latency offset: 0 usec, availability unknown)
				Properties:
					device.icon_name = "audio-input-microphone"
				Part of profile(s): input:analog-stereo, output:analog-stereo+input:analog-stereo
			analog-input-mic: Microphone (type: Mic, priority: 8700, latency offset: 0 usec, not available)
				Properties:
					device.icon_name = "audio-input-microphone"
				Part of profile(s): input:analog-stereo, output:analog-stereo+input:analog-stereo
			analog-output-speaker: Speakers (type: Speaker, priority: 10000, latency offset: 0 usec, availability unknown)
				Properties:
					device.icon_name = "audio-speakers"
				Part of profile(s): output:analog-stereo, output:analog-stereo+input:analog-stereo
			analog-output-headphones: Headphones (type: Headphones, priority: 9900, latency offset: 0 usec, not available)
				Properties:
					device.icon_name = "audio-headphones"
				Part of profile(s): output:analog-stereo, output:analog-stereo+input:analog-stereo
