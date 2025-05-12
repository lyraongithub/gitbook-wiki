# Camera Rig Guide

_By_ [_Lyra_](../../../members/members/lyra.md)

## Introduction 
The rigs were originally designed and built by honorary society member [Cooper](https://bsky.app/profile/ministraitor.bsky.social), who maintains documentation on the [parts](https://administraitor.video/rig.html) and [operation](https://administraitor.video/rig_operation.html) of a filming rig. Cooper also maintains a page on the [assembly of a rig](https://administraitor.video/organizers/assembly.html), containing videos on some stages of the process.  This guide is designed to supplement his work, based on the specific rig used by Hacksoc.

### Cables
The filming rigs use Serial Digital Interface (SDI) cables, a standard designed for transmitting uncompressed video/audio, due to the increased reliability compared to High-Definition Multimedia Interface (HDMI) over long distances.

While SDI cables are bi-directional, the power cables attached makes them effectively mono-directional and getting them the wrong way round will result in you having to unplug everything and start again.

The male end of the SDI cable goes at the PC end.
Figure x - Male end of SDI cable.
<img src="../.gitbook/assets/sdi-male.jpg" width="500"  alt="SDICableMaleEnd"/>

The female end of the SDI cable goes to the camera/podium end.
Figure x - Female end of SDI cable.
<img src="../.gitbook/assets/sdi-female.jpg" width="500"  alt="SDICableFemaleEnd"/>

Figure x - Power box connector.
<img src="../.gitbook/assets/power-box.jpg" width="500"  alt="PowerBox"/>

## Camera Connections
Figure x - Camera HDMI output.
<img src="../.gitbook/assets/camera-1.jpg" width="500"  alt="CameraHDMI"/>

Figure x - Camera power supply.
<img src="../.gitbook/assets/camera-2.jpg" width="500"  alt="CameraPower"/>

Take one of the coloured power boxes, and connect it to the power cable tied to to SDI cable.
Figure x - Camera power box.
<img src="../.gitbook/assets/camera-4.jpg" width="500"  alt="CameraPower"/>

The HDMI cable from the camera should be to the HDMI-SDI converter. Pay particular attention to use the unit with `INPUT` above the HDMI port. The SDI cable and power supply should be connected to the other side.
```
Commmon mistake: Using the HDMI-SDI covnerter with `OUTPUT` above the HDMI port.
```

Figure x - HDMI to SDI conversion.
<img src="../.gitbook/assets/camera-3.jpg" width="500"  alt="CameraPower"/>

## Podium Connections
Figure x - HDMI to SDI conversion.
<img src="../.gitbook/assets/podium-1.jpg" width="500"  alt="PodiumHDMICables"/>

Figure x - HDMI to SDI conversion.
<img src="../.gitbook/assets/podium-2.jpg" width="500"  alt="PosiumSDICables"/>

## PC Connections
Moving to the PC, SDI cable running from the camera should be connected to the top/right (depending on PC orientation)  input.
Figure x - Connection of camera cables.
<img src="../.gitbook/assets/camera-pc-connection.jpg" width="500"  alt="PCCameraConnections"/>

The SDI cable from the podium should be connected to the bottom/left input. The orientation of the two power cables does not matter.
Figure x - All SDI & power cables connected.
<img src="../.gitbook/assets/speaker-pc-connection.jpg" width="500"  alt="PCSpeakerConnections"/>

## Audio
Figure x - Front of audio interface.
<img src="../.gitbook/assets/audio-1.jpg" width="500" alt="BagSecondLayer"/>

Figure x - Read of audio interface.
<img src="../.gitbook/assets/audio-2.jpg" width="500" alt="BagSecondLayer"/>

## Troubleshooting

## Packing Everything Away
Before anything is unplugged, the system should be powered off with a command such as `shutdown`

### Toilet Bag
The order parts are placed into the toilet bag is personal preference, however this guide describes the way I prefer to pack it.

The bag is essentially packed largest to smallest, with the first parts being the Roland DUO-CAPTURE EX and HDMI-SDI splitter. Places side-by-side, they fit nicely.
Figure x - First layer of the "toilet bag".
<img src="../.gitbook/assets/bag-1.JPG" width="500" alt="BagFirstLayer"/>

The ROLAND unit is quite tall, so the two HDMI-SDI converters sit rather well next to it, on top of the HDMI-SDI splitter.
Figure x - Second layer of the "toilet bag".
<img src="../.gitbook/assets/bag-2.JPG" width="500" alt="BagSecondLayer"/>

