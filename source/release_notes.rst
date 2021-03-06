.. _release_notes:

Release Notes
#############

.. contents:: :local:



--------

ww201826
========

================================  =====
Build ID                          celadon-userdebug 8.1.0 OPM4.171019.021.E1 eng.build.20180629.162304 test-keys
Software Version                  Android version 8.1.0
Mesa                              18.2.0-devel
Kernel Flinger                    5.09
Kernel Version                    4.14.50
Download Link                     https://github.com/projectceladon/celadon-binary/tree/master/ww201826
================================  =====

Integrated Features
-------------------
In the WW24 release we have IVI also enabled , IVI is for Enabling CAR UI

* MESA graphics - OpenGL ES 3.0 & Vulkan 1.0 support
* Graphics Memory Allocator (Gralloc) 1.0
* HDMI display support
* HWC 2.0 support for Display
* USB digital audio playback support
* USB Type C support
* Analog Audio (MP3/AAC) playback on stereo wired Headset
* BT A2DP Audio support
* Audio parameter framework for audio routing policy
* H263/ H264/ HEVC/VP9/MPEG4 Video Playback using google video software codecs
* Wi-Fi 802.11 a/b/g/n
* Wired Ethernet support
* Open CI infrastructure for automatic build to verify and upstream patches
* Android Grub boot support
* Android Kernel Flinger boot support

Important Notes and Remarks
---------------------------

This |C| build has been validated on |NUC| Kit `NUC7i5BNH <https://www.intel.com/content/www/us/en/products/boards-kits/nuc/kits/nuc7i5bnh.html>`_ in the following function domains:

=============================  =======  ========
Component                      Results  Comments
=============================  =======  ========
Wi-Fi                          OK       WiFi Direct, WiFi streaming
BT                             OK       File Transfer Protocol
Audio over USB and BT headset  OK       MP3/AAC/MIDI/FLAC/WAV Audio playback, BT A2DP Audio Playback
Audio over 3.5mm jack          OK       MP3/AAC/MIDI/FLAC/WAV Audio playback
Video                          OK       H263/ H264/ HEVC/VP9/MPEG4 Video Playback using google video software codecs
Adb connect                    OK
Display /Touch and Gesture     OK
Storage/SD Card                OK
Security                       OK
Boot/Kernel                    OK
USB devices over OTG           OK
Fastboot                                Not available
GRUB Boot                      OK
Web browsing                   OK
Clone Mode                     OK
Image Display                  OK       SW JPEG Decode
USB/ADB                        OK       Working through Type-A USB & Ethernet
SD card                        OK
=============================  =======  ========

Known Issues
------------

* Screen overlap observed while playing local H263 video format

--------


ww201824
========

================================  =====
Build ID                          celadon-userdebug 8.1.0 O.CEL.T.WW24 eng.build.20180618.145425 test-keys
Software Version                  Android version 8.1.0
Mesa                              18.2.0-devel
Kernel Flinger                    5.09
Kernel Version / Android Version  4.14.35-project-celedon_64-g0a945a1
Download Link                     https://github.com/projectceladon/celadon-binary/tree/master/ww201824
================================  =====

Integrated Features
-------------------
In the WW24 release we have IVI also enabled , IVI is for Enabling CAR UI

* MESA graphics - OpenGL ES 3.0 & Vulkan 1.0 support
* Graphics Memory Allocator (Gralloc) 1.0
* HDMI display support
* HWC 2.0 support for Display
* USB digital audio playback support
* USB Type C support
* Analog Audio (MP3/AAC) playback on stereo wired Headset
* BT A2DP Audio support
* Audio parameter framework for audio routing policy
* H263/ H264/ HEVC/VP9/MPEG4 Video Playback using google video software codecs
* Wi-Fi 802.11 a/b/g/n
* Wired Ethernet support
* Open CI infrastructure for automatic build to verify and upstream patches
* Android Grub boot support
* Android Kernel Flinger boot support

Important Notes and Remarks
---------------------------

This |C| build has been validated on |NUC| Kit `NUC7i5BNH <https://www.intel.com/content/www/us/en/products/boards-kits/nuc/kits/nuc7i5bnh.html>`_ in the following function domains:

=============================  =======  ========
Component                      Results  Comments
=============================  =======  ========
Wi-Fi                          OK       WiFi Direct, WiFi streaming
BT                             OK       File Transfer Protocol
Audio over USB and BT headset  OK       MP3/AAC/MIDI/FLAC/WAV Audio playback, BT A2DP Audio Playback
Audio over 3.5mm jack          OK       MP3/AAC/MIDI/FLAC/WAV Audio playback
Video                          OK       H263/ H264/ HEVC/VP9/MPEG4 Video Playback using google video software codecs
Adb connect                    OK
Display /Touch and Gesture     OK
Storage/SD Card                OK
Security                       OK
Boot/Kernel                    OK
USB devices over OTG           OK
Fastboot                                Not available
GRUB Boot                      OK
Web browsing                   OK
Clone Mode                     OK
Image Display                  OK       SW JPEG Decode
USB/ADB                        OK       Working through Type-A USB & Ethernet
SD card                        OK
=============================  =======  ========

Known Issues
------------

* Disturbances and green screen observed during local video play

--------

ww201818
========

================================  =====
Build ID                          celadon-userdebug 8.1.0 OPM3.171019.013 eng.build.20180502.092142 test-keys
Software Version                  Android version 8.1.0
Mesa                              18.2.0-devel
Kernel Flinger                    5.09
Kernel Version / Android Version  4.14.35-project-celedon_64-g0a945a1
Download Link                     https://github.com/projectceladon/celadon-binary/tree/master/ww201818
================================  =====

Integrated Features
-------------------

* MESA graphics - OpenGL ES 3.0 & Vulkan 1.0 support
* Graphics Memory Allocator (Gralloc) 1.0
* HDMI display support
* HWC 2.0 support for Display
* USB digital audio playback support
* USB Type C support
* Analog Audio (MP3/AAC) playback on stereo wired Headset
* BT A2DP Audio support
* Audio parameter framework for audio routing policy
* H263/ H264/ HEVC/VP9/MPEG4 Video Playback using google video software codecs
* Wi-Fi 802.11 a/b/g/n
* Wired Ethernet support
* Open CI infrastructure for automatic build to verify and upstream patches
* Android Grub boot support
* Android Kernel Flinger boot support

Important Notes and Remarks
---------------------------

This |C| build has been validated on |NUC| Kit `NUC7i5BNH <https://www.intel.com/content/www/us/en/products/boards-kits/nuc/kits/nuc7i5bnh.html>`_ in the following function domains:

=============================  =======  ========
Component                      Results  Comments
=============================  =======  ========
Wi-Fi                          OK       WiFi Direct, WiFi streaming
BT                             OK       File Transfer Protocol
Audio over USB and BT headset  OK       MP3/AAC/MIDI/FLAC/WAV Audio playback, BT A2DP Audio Playback
Audio over 3.5mm jack          OK       MP3/AAC/MIDI/FLAC/WAV Audio playback
Video                          OK       H263/ H264/ HEVC/VP9/MPEG4 Video Playback using google video software codecs
Adb connect                    OK
Display /Touch and Gesture     OK
Storage/SD Card                OK
Security                       OK
Boot/Kernel                    OK
USB devices over OTG           OK
Fastboot                                Not available
GRUB Boot                      OK
Web browsing                   OK
Clone Mode                     OK
Image Display                  OK       SW JPEG Decode
USB/ADB                        OK       Working through Type-A USB & Ethernet
SD card                        OK
=============================  =======  ========

Known Issues
------------

* Disturbances observed during local video play
