# snowball-on-linux


@rosebook:$ pacmd list-cards
3 card(s) available.
index: 0
name: <alsa_card.pci-0000_05_00.1>
driver: <module-alsa-card.c>
owner module: 7
properties:
alsa.card = "0"
alsa.card_name = "HD-Audio Generic"
alsa.long_card_name = "HD-Audio Generic at 0xe06c8000 irq 87"
alsa.driver_name = "snd_hda_intel"
device.bus_path = "pci-0000:05:00.1"
sysfs.path = "/devices/pci0000:00/0000:00:08.1/0000:05:00.1/sound/card0"
device.bus = "pci"
device.vendor.id = "1002"
device.vendor.name = "Advanced Micro Devices, Inc. [AMD/ATI]"
device.product.id = "1637"
device.product.name = "Renoir Radeon High Definition Audio Controller"
device.string = "0"
device.description = "Renoir Radeon High Definition Audio Controller"
module-udev-detect.discovered = "1"
device.icon_name = "audio-card-pci"
profiles:
output:hdmi-stereo: Digital Stereo (HDMI) Output (priority 5900, available: no)
output:hdmi-surround: Digital Surround 5.1 (HDMI) Output (priority 800, available: no)
output:hdmi-surround71: Digital Surround 7.1 (HDMI) Output (priority 800, available: no)
output:hdmi-stereo-extra1: Digital Stereo (HDMI 2) Output (priority 5700, available: no)
output:hdmi-surround-extra1: Digital Surround 5.1 (HDMI 2) Output (priority 600, available: no)
output:hdmi-surround71-extra1: Digital Surround 7.1 (HDMI 2) Output (priority 600, available: no)
output:hdmi-stereo-extra2: Digital Stereo (HDMI 3) Output (priority 5700, available: no)
output:hdmi-surround-extra2: Digital Surround 5.1 (HDMI 3) Output (priority 600, available: no)
output:hdmi-surround71-extra2: Digital Surround 7.1 (HDMI 3) Output (priority 600, available: no)
output:hdmi-stereo-extra3: Digital Stereo (HDMI 4) Output (priority 5700, available: no)
output:hdmi-surround-extra3: Digital Surround 5.1 (HDMI 4) Output (priority 600, available: no)
output:hdmi-surround71-extra3: Digital Surround 7.1 (HDMI 4) Output (priority 600, available: no)
off: Off (priority 0, available: unknown)
active profile: <off>
ports:
hdmi-output-0: HDMI / DisplayPort (priority 5900, latency offset 0 usec, available: no)
properties:
device.icon_name = "video-display"
hdmi-output-1: HDMI / DisplayPort 2 (priority 5800, latency offset 0 usec, available: no)
properties:
device.icon_name = "video-display"
hdmi-output-2: HDMI / DisplayPort 3 (priority 5700, latency offset 0 usec, available: no)
properties:
device.icon_name = "video-display"
hdmi-output-3: HDMI / DisplayPort 4 (priority 5600, latency offset 0 usec, available: no)
properties:
device.icon_name = "video-display"
index: 1
name: <alsa_card.pci-0000_05_00.6>
driver: <module-alsa-card.c>
owner module: 8
properties:
alsa.card = "1"
alsa.card_name = "HD-Audio Generic"
alsa.long_card_name = "HD-Audio Generic at 0xe06c0000 irq 88"
alsa.driver_name = "snd_hda_intel"
device.bus_path = "pci-0000:05:00.6"
sysfs.path = "/devices/pci0000:00/0000:00:08.1/0000:05:00.6/sound/card1"
device.bus = "pci"
device.vendor.id = "1022"
device.vendor.name = "Advanced Micro Devices, Inc. [AMD]"
device.product.id = "15e3"
device.product.name = "Family 17h (Models 10h-1fh) HD Audio Controller"
device.string = "1"
device.description = "Family 17h (Models 10h-1fh) HD Audio Controller"
module-udev-detect.discovered = "1"
device.icon_name = "audio-card-pci"
profiles:
input:analog-stereo: Analog Stereo Input (priority 32833, available: unknown)
output:analog-stereo: Analog Stereo Output (priority 39268, available: unknown)
output:analog-stereo+input:analog-stereo: Analog Stereo Duplex (priority 39333, available: unknown)
off: Off (priority 0, available: unknown)
active profile: output:analog-stereo+input:analog-stereo
sinks:
alsa_output.pci-0000_05_00.6.analog-stereo/#0: Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo
sources:
alsa_output.pci-0000_05_00.6.analog-stereo.monitor/#0: Monitor of Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo
alsa_input.pci-0000_05_00.6.analog-stereo/#1: Family 17h (Models 10h-1fh) HD Audio Controller Analog Stereo
ports:
analog-input-internal-mic: Internal Microphone (priority 8900, latency offset 0 usec, available: unknown)
properties:
device.icon_name = "audio-input-microphone"
analog-input-mic: Microphone (priority 8700, latency offset 0 usec, available: no)
properties:
device.icon_name = "audio-input-microphone"
analog-output-speaker: Speakers (priority 10000, latency offset 0 usec, available: unknown)
properties:
device.icon_name = "audio-speakers"
analog-output-headphones: Headphones (priority 9900, latency offset 0 usec, available: no)
properties:
device.icon_name = "audio-headphones"
index: 3
name: <alsa_card.usb-BLUE_MICROPHONE_Blue_Snowball_797_2020_05_17_75878-00>
driver: <module-alsa-card.c>
owner module: 28
properties:
alsa.card = "2"
alsa.card_name = "Blue Snowball"
alsa.long_card_name = "BLUE MICROPHONE Blue Snowball at usb-0000:05:00.3-2, full speed"
alsa.driver_name = "snd_usb_audio"
device.bus_path = "pci-0000:05:00.3-usb-0:2:1.0"
sysfs.path = "/devices/pci0000:00/0000:00:08.1/0000:05:00.3/usb1/1-2/1-2:1.0/sound/card2"
udev.id = "usb-BLUE_MICROPHONE_Blue_Snowball_797_2020_05_17_75878-00"
device.bus = "usb"
device.vendor.id = "0d8c"
device.vendor.name = "C-Media Electronics, Inc."
device.product.id = "0005"
device.product.name = "Blue Snowball"
device.serial = "BLUE_MICROPHONE_Blue_Snowball_797_2020_05_17_75878"
device.string = "2"
device.description = "Blue Snowball"
module-udev-detect.discovered = "1"
device.icon_name = "audio-card-usb"
profiles:
input:mono-fallback: Mono Input (priority 1, available: unknown)
off: Off (priority 0, available: unknown)
active profile: input:mono-fallback
sources:
alsa_input.usb-BLUE_MICROPHONE_Blue_Snowball_797_2020_05_17_75878-00.mono-fallback/#3: Blue Snowball Mono
ports:
analog-input-mic: Microphone (priority 8700, latency offset 0 usec, available: unknown)
properties:
device.icon_name = "audio-input-microphone"
rose@rosebook:
$

how to set blue snowball as default

To set the Blue Snowball microphone as the default input device, you can use the pacmd command-line tool. Here's how you can do it:

    Identify the sink index of the Blue Snowball microphone. In this case, the Blue Snowball has a card name of "Blue Snowball" and its sink index is 2.

    Set the Blue Snowball microphone as the default input device using the following command:

bash

pacmd set-default-source alsa_input.usb-BLUE_MICROPHONE_Blue_Snowball_797_2020_05_17_75878-00.mono-fallback

This command will set the Blue Snowball microphone as the default input source on your system. You should now be able to use it as the primary microphone for input.

If you encounter any issues or need further assistance, feel free to ask for help.

omg yay :D
