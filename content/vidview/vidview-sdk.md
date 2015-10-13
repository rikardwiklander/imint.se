---
date: 2015-09-24
title: "Vidview SDK"
menu:
  main:
    name: 
    parent:
    weight: 20
---


Vidview™ is designed to be an ideal software integration product. It brings in both the advanced real-time video enhancement and analytics functions of Vidhance®, as well as nifty video player and video management functionality, into a host application. Vidview SDK (Software Development Kit) is the development tool provided to enable smooth integration into a host application. Different levels of integration is possible, from tight integration through development in a .NET environment, to providing Active X COM-interfaces, or simply by remote control of a Vidview application through TCP/IP. Different licensing models are also available.
[Vidview intregrated into a submarine pilot console using Vidview SDK] Vidview intregrated into a submarine pilot console using Vidview SDK

{{<img src="img/vidview/uw-blandat_282_0.jpg" class="small-image floatright">}}
## Software Integration Using Vidview SDK

For those who want to achieve a tighter integration, the Vidview SDK is needed. For integration partners, Imint is enabling a true open collaborative development methodology, freely sharing a wealth of useful utilities and optimized functions to support successful development.

Currently, the Vidview SDK is tailored for .NET development environments, and the primary programming language used is C#. However, there are a number of ways to bring Vidview into a host application that is not .NET centric. For instance, a Vidview application can be brought into another application by COM interfaces or docking windows. Vidview can also be controlled over TCP/IP, so that a host application can treat the Vidview video viewer as a remote slave, but achieving the full sense of integration from a user perspective.

{{<img src="img/vidview/vw-sdk-screenshot-web.png" class="small-image floatright">}}

The Vidview SDK is a comprehensive set of software (both source and binary code), examples, utilities and documentation. As an example, a simple video viewer example project is included, which allow a software developer to swiftly experiment with functions like:

- Load a video file from disk or from a live stream.
- Play, pause, zoom, pan, crop, rotate, etc.
- Enable different modes of video stabilization.
- Enable different modes of local contrast optimization, and experiment with settings.
- Enable different modes of object tracking; click on object of interest and evaluate the performance
- Add overlays and symbols, either fixed to video frame or to viewing frame.


## Modular and Configurable

On the light weight integration side, Vidview can be provided as a ready made video handling application. Vidview is  customizable, as it is made highly modular. Configuration options are separated into XML-files, which are easy to edit or remove. XML files are provided to handle all aspects of the GUI (what user interaction buttons to show, and where), custom video overlays, video capture, video recording, etc. In addition, the different Vidhance components is also accessible through XML files. Within a very short time period, an integrator are able to create its own flavor of a Vidview application, to fit specific requirements.

## Why Integrating a Video Viewer?

Given the powerful Vidhance algorithm package, a software engineer would conclude that the most efficient way to deliver these benefits would be through a graphics library. Although this is doable, Imint have reached the conclusion that a good delivery platform which aims at reducing development efforts and providing fullest functionality, is best solved through integration of complete video viewing and management. Providing only graphics libraries has a few pitfalls, such as:

- Video management is a hassle. Video shall be captured from an analog input, or retrieved from an IP stream or disk. There is no shortage on video formats or transport containers, making it a daunting and time consuming task.What is perceived as "simple" functionality such as panning and zooming in the video, recording or playback, is in fact time consuming engineering tasks, and the end result does not provide any competitive edge to the system.
- Problems to utilize hardware. Different processor platforms behaves differently, and maximum performance is achieved in non-intuitive ways. Making clever decision algorithms on graphics hardware utilization part and parcel of the enhancement algorithms itself, performance will benefit.
- Viewing limitations. The video will be presented in a window on a computer display. For functions such as stabilization and local mosaic, the practical viewing limitations has significant impact on how the algorithms should behave. If the software keep foreground object stable in a situation with a moving camera, and the video frames comes close to the display window borders, how should the situation be handled? The Vidhance algorithms is not only a core library of video analysis, but it also utilizes knowledge about the practical constraints for video viewing.


## Contact us

Vidview SDK is made available in different licensing packages, to fit team size, project scope, and end systems. [Sign up for evaluation](/imint.se/form/evaluation-request "Evaluation Request"), or [contact us](/imint.se/about/contact/ "Contact") for a Vidview SDK quotation.
