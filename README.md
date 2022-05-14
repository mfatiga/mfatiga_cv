# Curriculum Vitae
 - Mario Fatiga - Croatia
 - born on January 30, 1988


# Links
[GitHub](https://github.com/mfatiga/)
[LinkedIn](https://www.linkedin.com/in/mario-fatiga-9198b435/)
[exercism](https://exercism.org/profiles/mfatiga)
[500px](https://500px.com/p/mfatiga)


# Introduction
 - software system architect, language-agnostic developer, team lead
 - love to find solutions for all kinds of problems in anything tech related
 - started coding in 1996 with QBasic and Basic on ZX Spectrum
 - very good knowledge of a wide array of programming languages
 - high interest in anything software and hardware related
 - high interest in all facets of technology and science
 - very good knowledge and understanding of electronics and embedded communication protocols
 - Linux user - using NeoVIM for most development, or Android Studio with VIM keybindings for Android
 - hobbies include: music synthesizers, SIM racing, FPV drone flying, Smart Home systems, photography, etc.


# Work experience

## [March 2016 - now] Software Engineer/Architect - SIL d.o.o, Varazdin, Croatia
 - Linux based IOT system solution designer, largely developed in Python
 - developer and solution designer on numerous software libraries, frameworks, and applications
 - system architect on multiple projects including backend, firmware, and mobile app architecture

### ZeroMQ based Entity-Resource management and control system:
 - software solution designer, lead developer (Python, ZeroMQ, ...)
 - Python Linux services
 - generic solution for controlling and consuming any kind of software or hardware resource using a simple and powerful API
 - integrated generic RPC solution for UNARY and STREAM calls with easily developed resource wrappers
 - easily extendable support for multiple protocols (ZeroMQ, Websockets, ...)
 - distributed resource management and control
 - auto-generated API and documentation

### Smart Linux locker system:
 - software solution designer, lead developer (Python, Redis, ...)
 - Python Linux systemd services controlling different kinds of external/internal hardware/software
 - used mostly for controlling externally connected electronic lock controllers
 - services communication and shared storage implemented using Redis
 - consisted of over 20 internally developed libraries, including:
   - Python OpenAPI client generator - generate a python client module based on OpenAPI.json rest service description
   - PyRedisMQ - generic python redis-list based message queues with support for RPC (unary and generator-based streams)
   - PyRedisLock - shared resource locking using Redis key auto-expiry

### Smart Android locker system:
 - software solution designer, lead developer (Kotlin)
 - BLE based and locally USB-connected electronic lock control and business logic

### Multiple parcel locker / Single parcel locker / SeeUS - embedded firmware solutions:
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

### Smart Letterbox Android application:
 - solution designer and lead developer (Kotlin)
 - BLE (bluetooth low energy) scanning and communication with BLE devices

### Civitavecchia Android application:
 - [link](https://play.google.com/store/apps/details?id=hr.sil.civitavecchia)
 - architect and developer (Kotlin)
 - tourist point-of-interest guide app with scavenger hunts
 - POI beacons detection using BLE scanning

### Paketbox Android application:
 - [link](https://play.google.com/store/apps/details?id=hr.sil.android.paketbox.user)
 - lead developer (Kotlin)
 - smart letter and parcel box lock control and key sharing app
 - BLE

### Beacon Configurator / SilwareBullet Android apps:
 - solution designer and lead developer (Kotlin)
 - internal app used for configuring, analyzing, and debugging BLE based embedded products
 - lots of different functionalities including generic BLE communication testing, GPS tracking, live parameter charting, dynamic UI building based on BLE device advertisement information, etc.

### ESP8266 Arduino based WiFi to UART proxy:
 - solution designer and developer (C++)
 - IOT WiFi to UART proxy
 - Arduino framework, custom protocol on top of TCP


## [March 2014 - March 2016] Software Engineer/Architect - Koncar INEM d.d., Zagreb, Croatia

### MARS2:
 - developer, front end solution designer
 - energy consumption/production measurement aggregation and reporting
 - technologies: WebApi2 rest services, React.js web front end with a large number of components, other Javascript utility libraries, ModBus and MBus windows C# drivers for direct reading of measurement values from electric energy meters

### MARS:
 - developer
 - deployment and end user education and training at "HEP Proizvodnja d.o.o." in Varazdin
 - technologies: server: windows service for energy source consumption aggregation and organization (some pub-sub components and different energy source aggregator drivers...); client: silverlight web app

### EIS (Energy Information System - city of Zagreb):
 - developer
 - aggregation of measured energy source consumption, billing, consumption prediction algorithms, energy classes, lots of algorithms and data stored in a temporal database;
 - technologies: ASP.NET MVC 5 (web app, Razor views using Kendo components...), jQuery, D3js used for data visualization; smaller parts done using WebApi 2 and an AngularJS frontend using NVD3 charts in Angular directives (D3 reusable charts)

### WorkOrders:
 - solution designer and developer
 - simple application for work order tracking developed using WebApi 2 web service with a flux (Reflux.js) + React.js frontend


## [September 2013 - March 2014] Software Engineer - Multicom d.o.o., Zagreb, Croatia

### OSF (One Service Frontend)
 - developer
 - a project for HT - Hrvatski Telekom - a Java EE 6 application connecting to different web services, collecting, organizing and displaying the information
 - creating custom JSF components (i.e. custom tree node) with renderers, component and tag handlers
 - JSF - PrimeFaces, JSTL, jQuery, Oracle DBMS

### TRT (Tariff Simulator Tool)
 - developer
 - a project for HT - Hrvatski Telekom - a web application for simulating various changes in tariffs and options for a mobile subscription plan - Ember.JS, jQuery, Java rest web services - JSON used for data exchange
 - writing different kinds of PL/SQL scripts for Oracle databases


## [September 2011 - July 2013] Software Engineer - WORX d.o.o., Zagreb, Croatia
 - development and maintenance of a PLM application written in Java (swing, ejb, hibernate, JBoss...), including deployment and configuration of this application on remote networks used by customers (mix of Linux and Windows machines)
 - solution design and development of lots of new functionality in that PLM system (for example, workflow processing engine running using manually drawn process flow diagrams, lots of work with tree structures including tree comparisson...)
 - 1 month of work experience in Canada (ATS - Automation Tooling Systems, Cambridge, Ontario) - working with them on PLMWorx to design and properly implement some of their business requirements
 - solution design and development of PDM support plug-ins, add-ins and external applications for SolidWorks (C# client with Java webservices, hibernate, ejb, JBoss), AutoCAD (C#, MSSQL), Inventor (C# client with Java webservices, hibernate, ejb, JBoss) and also some small work with Catia (VBA scripts)
 - partial solution design and development of a grid process server system(using Condor HTC as a resource management system) including support applications and Windows services used by that system
 - development of a web PLM application (SmartClient 6.5 - 8.2, ejb, hibernate, JBoss...).
 - working with different kinds of DBMS-es, migration of MS-SQL database data and procedures to MySQL
 - working in a team designing and developing applications and also with people from different parts of the world (Croatia, Canada, Germany)


## [2008 - 2010] Student jobs
### [February 2011 - July 2011] Computer programmer - Financijska agencija (FINA), Zagreb, Croatia
Developement of desktop and server (windows service) applications in C#; using and creating databases in MS SQL Server 2005.

### [Summer job 2008 - 2010] Traffic lights maintenance - Selekta Prima d.o.o., Zagreb, Croatia
Traffic lights maintenance (checking for errors and repair) in the areas of Varaždin, Koprivnica, Križevci, Čakovec, Ludbreg, Zlatar Bistrica, Ivanec. The job included communication with the police and companies that ensure proper traffic functioning. I had access to the company car and a cellphone, and I was doing the job alone, only calling the more experienced people when I couldn't fix a malfunction by myself. The job consisted of a daily check for errors in traffic light functioning and going on interventions upon receiving a call.


# Education
## [September 2006 - June 2011] Master of Engineering in Computing
Faculty of Electrical Engineering and Computing, Zagreb, Croatia

## [September 2002 - June 2006] Computing technician
Elektrostrojarska škola, Varazdin, Croatia

## [2005] Cisco CCNA Course
Varazdin, Croatia


# Languages
 - proficient user of English
 - Croatian - mother tongue
