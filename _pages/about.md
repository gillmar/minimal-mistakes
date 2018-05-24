---
permalink: /about/
layout: single
author_profile: true
---

# Eurex Clearing’s C7

Delivering innovation on a broad scale, Eurex Clearing’s C7 is designed to leave no footprint on the participant side allowing you to choose the technology that’s right for your business. C7 is designed to ensure more flexibility for the introduction of new products & services and keeps you well prepared for evolving regulatory changes.

As a result of many years of continuous investment, market consultation and regular upgrades, our superior technology ensures that we remain in the best position to serve our customers.
So as conditions continue to change, we always keep our Members clear to trade.

# C7 Core Backend
This is the project for the C7 Core Backend - see also http://www.eurexclearing.com/clearing-en/technology/c7.
![Landscape Overview](documentation/installation-guide/images/overview.png)

## Documentation Resources
A good starting point is the [Eurexwiki](http://prosv8.rdev.deutsche-boerse.de/eurexwiki/index.php/Main_Page).

  * [JIRA](https://jiradbg.deutsche-boerse.de/browse/C7)
  * [C7 Project SIRs](https://sire.deutsche-boerse.de/cgiplus-bin/sire/sire.com/query_results.slk?PR=NCA&DN=Container&DN=DCCR&DN=Issue&DN=Project+SIR&SI=&EI=&CM=1&AT=S&AU=&CT=S&SU=&SDDY=&SDMN=&SDYR=&EDDY=&EDMN=&EDYR=&H0=1&N0=&H1=1&N1=&H2=1&N2=&H3=1&N3=&DH0=1&DS0DY=&DS0MN=&DS0YR=&DE0DY=&DE0MN=&DE0YR=&UH0=1&UN0=&US0DY=&US0MN=&US0YR=&UE0DY=&UE0MN=&UE0YR=&UH1=1&UN1=&US1DY=&US1MN=&US1YR=&UE1DY=&UE1MN=&UE1YR=&IH0=1&IN0=&IV0=&IH1=1&IN1=&IV1=&FA=1&F=&RT=D&X=Product&X=Type&X=Current+state&X=Submitter&X=Current+owner&G=Short+description&ACTION=VIEW&ENTITY=QUERY&FC=4&FC1=1&FC2=2&FC3=2&ROLE=Superset%3B&VER=1)

## Other C7 components
  * [C7 GUI](https://github.deutsche-boerse.de/dev/ec-gui-c7)
  * [C7 Entitlement](https://github.deutsche-boerse.de/dev/C7-Entitlement-Core)
  * [C7 RDS](https://github.deutsche-boerse.de/dev/C7-RDS)
  * [C7 Controller](https://github.deutsche-boerse.de/dev/C7-Controller)
  * [C7 Collateral Management Service](https://github.deutsche-boerse.de/dev/C7-Collateral-Core)
  * [C7 Payment Service](https://github.deutsche-boerse.de/dev/eurex-ccs-parent)
  * [C7 Advanced Risk Protection](https://github.deutsche-boerse.de/dev/C7-ARP-Core)

## Continuous Integration
Our Jenkins Pipeline can be found here: [Jenkins](https://scmci1.deutsche-boerse.de/job/Clear/view/Backend%20CI%20Pipeline/)

## CIL Layouts
Our CIL Layout files can be found here: [C7 Proto Files](https://github.deutsche-boerse.de/dev/gts.cilmsg.c7/)
#### Generation of language bindings from proto files
To generate java and python bindings from protofiles, use the following command :  
`mvn -P generate-cil clean process-sources`

