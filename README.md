# Dashboard-Builder



![Dashboard-Builder Clip](https://drive.google.com/uc?export=view&id=1dk_7bPZNT78RXJwPt_FjkPvyX9BjkoF8)

[Dashboard-Builder here](https://drive.google.com/file/d/1dk_7bPZNT78RXJwPt_FjkPvyX9BjkoF8/view?usp=sharing) if the video doesn't load.

The vast majority of data sources used in urban planning are, in one way or another, georeferenced.
Many open GIS (geographic information system) standards, crucial for working and processing this data, are defined by the Open Geospatial Consortium (OGC).
As the Hamburgs [Urban Data Platform](http://www.urbandataplatform.hamburg/) (UDP) also relies on these standards, we developed the Dashboard-Builder prototype by trying to havest the full potential of Web Feature Service (WFS) and Web Processing Service (WPS). The amount of open source web GIS clients that rely on OGC standards is growing quickly. We see a lack of comprehensive open source software that provides analytical capabalities for these standardised data sources.

This feasibility study examines the extent to which a dashboard builder can be created on the basis of the existing backend components of the UDP Hamburg and the coordinated front-end software packages ([Masterportal](https://bitbucket.org/geowerkstatt-hamburg/masterportal), [Masterportal Admin Tool](https://bitbucket.org/geowerkstatt-hamburg/mp-admintool/src) and [Dashboard-Framework](https://github.com/citysciencelab/udh-dashboard-framework) / [UDP cockpit](https://geoportal-hamburg.de/udp-cockpit/)), or which components are missing for this purpose. Dashboards and the associated visualizations are intended to bring complex data closer to the viewer in an understandable way. If the various users of the UDP can be enabled to explore the data of the platform and create their own visualizations in an explorative way, independently and without existing programming knowledge, this has the potential to greatly increase the user value of the same. In order to avoid the use of proprietary software and to be able to optimally link the designated application with the existing software projects of the UDP, the following study investigates the possibilities of an in-house development. For this purpose, the existing components are first analyzed, user stories are designed, requirements are defined, and an architecture sketch is developed. This draft of an architecture is compared afterwards with the actual state of the UDP. This comparison then results in the prototypical designs. Finally, the effort of a practical implementation of the same is estimated, potential bottlenecks are defined and upcoming tasks are determined.

You can find all corresponding repositories and the code here:
https://bitbucket.org/till-hcu/workspace/projects/DBP

The subsequent figure is a sketch of the designed architecture:
<img width="525" alt="architektur" src="https://user-images.githubusercontent.com/36763878/126600933-81b19c8c-2a86-4eed-a985-9a469cd32e7d.png">

The complete study in German can be downloded here:
[Machbarkeitsstudie_Dashboard-Builder_Final.pdf](https://github.com/citysciencelab/dashboard-builder/files/6860429/Machbarkeitsstudie_Dashboard-Builder_Final.pdf)


