# aplay info

arecord  is a command-line soundfile recorder for the ALSA soundcard driver. It supports several file formats and
multiple soundcards with multiple devices. If recording with interleaved mode samples the file  is  automatically
split before the 2GB filesize.

`aplay --list-devices`

	**** List of PLAYBACK Hardware Devices ****
	card 0: Generic [HD-Audio Generic], device 3: HDMI 0 [HDMI 0]
	  Subdevices: 1/1
	  Subdevice #0: subdevice #0
	card 0: Generic [HD-Audio Generic], device 7: HDMI 1 [HDMI 1]
	  Subdevices: 1/1
	  Subdevice #0: subdevice #0
	card 0: Generic [HD-Audio Generic], device 8: HDMI 2 [HDMI 2]
	  Subdevices: 1/1
	  Subdevice #0: subdevice #0
	card 1: Generic_1 [HD-Audio Generic], device 0: ALC257 Analog [ALC257 Analog]
	  Subdevices: 0/1
	  Subdevice #0: subdevice #0


