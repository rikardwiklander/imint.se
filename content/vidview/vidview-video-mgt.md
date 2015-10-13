---
date: 2015-09-24
title: "Vidview Video Mgt"
menu:
  main:
    name:
    parent:
    weight: 30
---


A Vidview™ video viewer is primarily an enabling platform for the [Vidhance](http://vidhance.com "Vidhance") technology, but is also provides a number of useful video management and video viewing functionality. This allows high level of customization for integration, as well as it saves valuable development time for standard functionality in any video viewing application.

# User Interaction

Vidview comes with functionality to interact with the video viewer, whether or not the video is playing or paused, such as:

- Panning
- Zooming
- Rotation
- Taking snapshots (save original and enhanced snapshots, including time stamps)

This can all be achieved seamlessly and convenient through, for example, mouse button interaction.

# Video Presentation

The way the video is presented in the Vidview viewer can be defined through functions like:

- Cropping of borders (size of crop can be set individually for each border)
- Setting of aspect ratio
- De-interlacing of video

# Video Capture and Input

Vidview allows for viewing and recording live video as well as video from file.

### *Live Analog Capture*

A number of analog capture devices are supported, such as Hauppage USB-LIVE-2, AVerMedia DVD EZMaker 7, and Sensoray 2253. Additional capture devices are also supported, and new devices can be supported upon request.

### *Live Digital Capture*

Vidivew supports receiving digital video in the following formats:

- MJPEG encoded video streamed over HTTP (record)
- MJPEG encoded video streamed over RTSP (record)

Vidview can also support receiving digital video in the following formats (additional codecs might be required):

- MPEG-2 encoded video in a MPEG-2 transport stream over UDP (record, timeshift)
- H.264 encoded video in a MPEG-2 transport stream over UDP (record, timeshift)
- MPEG-4 Visual encoded video in a MPEG-2 transport stream over RTSP
- H.264 encoded in MPEG-2 transport stream over RTSP (record, timeshift)

### *Pre-recorded Video*

Vidview can read stored video in the following formats:

AVI-container with an .avi file extension:

- MJPEG
- WMV1
- WMV2
- MS MPEG4 v1
- DV
- MPEG-2 (additional codecs may be required)
- H.264 (additional codecs may be required)

ASF-container with the following formats:

- MJPEG (with .asf file extension)
- WMV1 (with .wmv file extension)
- WMV2 (with .wmv file extension)

MPEG-2 or H.264 in a MPEG-2 program or transport stream with the following extensions (additional codecs may be required):

- .vob (MPEG-2 program stream)
- .mpeg (MPEG-2 program stream)
- .mpg (MPEG-2 program stream)
- .m2t (MPEG-2 transport stream)
- .m2ts (MPEG-2 transport stream)
- .mpeg ((MPEG-2 transport stream)
- .mpg (MPEG-2 transport stream)
- .mts (MPEG-2 transport stream)


# Video Overlays

Vidview is using advanced adaptive vector overlays, open and sensitive to user interaction. This is a summary of main features:

- Text overlays
- Vector and raster symbols
- Easy transforms available
- 18 anchoring points available
- Anchoring points can be set relative to video frame or viewing window.
- Pointer interaction
- Programmatic creation of symbols
