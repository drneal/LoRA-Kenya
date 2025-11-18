# LoRA-Kenya
Materials list for LoRa projects across Kenya:

1) Heltec V3 Development board MUST be 868MHz.
2) 1100 to 3000mAh Lithium-Ion battery.
3) Antenna – I have tested Gizont Antennas from AliExpress at 868Mhz and get an SWR of 1.1 to 1.2.
4) Case – the case in the images directories iare good for a devices you carry around with you – there is a blue/white one that fits in a pocket and connects to your phone via to USB cable but it cannot house a battery in the case and cannot connect to your phone by BLE as it is unpowered. For a repeater and case with more room in it is needed to house a battery (unless you don't care about it not working if there's no 5V power from mains via a wall wart). Case end is USB-C; phone end is whatever your phone is so you need ...
5) the appropriate USB cable.

If you have your own an IP-68 case you don't need to buy another case for your repeater units.

Get a better antenna especially if you are intending to set up a device as a repeater. (Remember that under the Meshcore protocol companion nodes do not repeat). Make sure your antenna is an 868MHz antenna. Most are 868 though many are sold out of China as being for 915MHz. The only way to tell for your is with an SWR meter.

A good introductory video that can cement these ideas into your mind is this one by Andy Kirby ... https://youtu.be/t1qne8uJBAc
A video that dives into the differences between Meshtastic, Meshcore and Reticulum - https://youtu.be/KHqCQCfvoMo
Why should we do this? - https://youtu.be/1n6xBJea3gs
