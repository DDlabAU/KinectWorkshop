# Microsoft Kinect i Processing på OS X og Windows
##Formål med workshoppen: At blive bekendt med, hvordan man bruger Microsofts Kinect 1 eller 2 via Open Kinect i Processing 3.

###Ressourcer

**KinectPV2**
- [KinectPV2 til Windows](https://github.com/ThomasLengeling/KinectPV2) (inkl. installationsinstruktioner)
- [KinectPV2-udviklerens hjemmeside](http://codigogenerativo.com/code/kinectpv2-k4w2-processing-library/)

Herunder er links til de forskellige versioner af Windows SDKet. Der er et link, hvor SDKet bliver beskrevet og man kan se hvordan man skal installere og et link til selve downloaden. Det er muligt at I skal installere mere end selve SDK-downloaden for at få det til at køre.

- Kinect SDK 1.8 inkl. getting started. Til Kinect for Windows (IKKE Kinect for Xbox 360): https://msdn.microsoft.com/en-us/library/hh855347.aspx
- Kinect SDK 1.8 download: https://www.microsoft.com/en-us/download/details.aspx?id=40278
- Kinect SDK 2.0 inkl. getting started. Til Kinect v2: https://msdn.microsoft.com/en-us/library/dn799271.aspx
- SDK 2.0 download: http://www.microsoft.com/en-us/download/details.aspx?id=44561

**OpenNI** <br />
I vil måske støde på noget der hedder OpenNI (Open Natural Interface) rundt omkring. Det er blevet købt af Apple og er derfor nu svært at regne med. Der er et firma der kører det videre: Occipital, Inc, der kører Structure.io hvor de laver en tracker til iOS bl.a.

- [OpenNI2 SDK](http://structure.io/openni) (har ikke noget med Processing at gøre)
- [Structure sensor fra structure.io](https://store.structure.io/store)

Man kan køre OpenNI med Processing via SimpleOpenNI-biblioteket (OBS. Hent og brug Processing 2.2.1 til dette)
     - Vil det ikke launche? #33 på denne tråd hjalp mig https://code.google.com/p/simple-openni/issues/detail?id=75
     - Installér via disse instruktioner: https://code.google.com/p/simple-openni/wiki/Installation

**Installation af Open Kinect for Processing i Processing 3 på OS X og med Kinect for Xbox 360**

- Download den seneste Processing fra https://processing.org/download/ og installér det.
- Tilføj biblioteket via: "Sketch -> Import Library… -> Add Library…” og søg efter ‘open’.
