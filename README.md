# Curriculum Vitae
 - Mario Fatiga - Croatia
 - born on January 30, 1988

# TLDR
 - software system architect, language-agnostic developer, team lead
 - love to find solutions for all kinds of problems in anything tech related
 - started coding in 1996 with QBasic and Basic on ZX Spectrum
 - very good knowledge of a wide array of programming languages
 - high interest in anything software and hardware related
 - high interest in all facets of technology and science
 - very good knowledge and understanding of electronics and embedded communication protocols

# Work experience
## [March 1, 2016 - now] Software Engineer/Architect - SIL d.o.o Croatia
 - Linux based IOT system solution designer based on Linux, largely developed in Python
 - Android developer and solution designer on multiple different libraries and frameworks used internally in most apps
 - system architect on multiple projects including firmware and mobile app architecture


### Projects [sorted from most to least recent]

Python - ZeroMQ based Entity-Resource management and control system:
 - software solution designer, lead developer (Python, ZeroMQ, ...)
 - Python Linux services
 - generic solution for controlling and consuming any kind of software or hardware resource using a simple and powerful API
 - integrated generic RPC solution for UNARY and STREAM calls with easily developed resource wrappers
 - easily extendable support for multiple protocols (ZeroMQ, Websockets, ...)
 - distributed resource management and control
 - auto-generated API and documentation


Smart Linux locker system:
 - software solution designer, lead developer (Python, Redis, ...)
 - Python Linux systemd services controlling different kinds of external/internal hardware/software
 - used mostly for controlling externally connected electronic lock controllers
 - services communication and shared storage implemented using Redis
 - consisted of over 20 internally developed libraries, including:
   - Python OpenAPI client generator - generate a python client module based on OpenAPI.json rest service description
   - PyRedisMQ - generic python redis-list based message queues with support for RPC (unary and generator-based streams)
   - PyRedisLock - shared resource locking using Redis key auto-expiry


Smart Android locker system:
 - software solution designer, lead developer (Kotlin)
 - BLE based and locally USB-connected electronic lock control and business logic


Multiple parcel locker / Single parcel locker / SeeUS - embedded firmware solutions:
 - software solution designer, hardware high-level architect, lead firmware developer (C++)
 - using Mbed OS as the high level RTOS and HAL wrapper
 - using STM (control) and Nordic (BLE) developed microcontrollers
 - multiple hardware revisions, up to 4 concurrently running microcontrollers with different responsibilities
 - ultra-low power consumption hardware and ultra-low power optimized firmware
 - UART power optimized communication using lazy request-based UART initialization
 - highly size-optimized small object list storage solution for EEPROMs (4 kilobyte)
 - custom memory allocation algorithm for auto-chunked memory allocation in highly fragmented RAM
 - ePaper image diff, merge, write using SPI
 - idea and partial solution for DMA audio playback from flash based memory with MP3 stream decoding


Smart Letterbox Android application:
 - solution designer and lead developer (Kotlin)
 - BLE (bluetooth low energy) scanning and communication with BLE devices


Civitavecchia Android application - [link](https://play.google.com/store/apps/details?id=hr.sil.civitavecchia):
 - architect and developer (Kotlin)
 - tourist point-of-interest guide app with scavenger hunts
 - POI beacons detection using BLE scanning


Paketbox Android application - [link](https://play.google.com/store/apps/details?id=hr.sil.android.paketbox.user):
 - lead developer (Kotlin)
 - smart letter and parcel box lock control and key sharing app
 - BLE


Beacon Configurator / SilwareBullet Android apps:
 - solution designer and lead developer (Kotlin)
 - internal app used for configuring, analyzing, and debugging BLE based embedded products
 - lots of different functionalities including generic BLE communication testing, GPS tracking, live parameter charting, dynamic UI building based on BLE device advertisement information, etc.


ESP8266 Arduino based WiFi to UART proxy:
 - solution designer and developer (C++)
 - IOT WiFi to UART proxy
 - Arduino framework, custom protocol on top of TCP

