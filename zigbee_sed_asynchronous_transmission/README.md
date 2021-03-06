# Companion example for KBA - A reliable way for SED to receive asynchronous transmissions from other devices without frequent polling

## Summary ##

This example is a demo project for Knowledge Base Article [A reliable way for SED to receive asynchronous transmissions from other devices without frequent polling](https://www.silabs.com/community/wireless/zigbee-and-thread/knowledge-base.entry.html/2018/11/29/a_reliable_way_fors-OTah). It implements a reliable way for a sleepy end device to receive asynchronous transmissions from other devices without frequent polling.

## Gecko SDK version ##

v2.4.1

## Hardware Required ##

Three BRD4162A EFR32MG12 radio boards.

## Setup ##

One BRD4162A loaded with Z3Switch_SED project to be the receiver sleepy end deivce.

One BRD4162A loaded with Z3Light_Router project to be the parent of the Z3Switch_SED.

One BRD4162A loaded with Z3Light_EndDevice project to control the polling of Z3Switch_SED remotely.

## How It Works ##

Please refer to the Knowledge Base Article [A reliable way for SED to receive asynchronous transmissions from other devices without frequent polling](https://www.silabs.com/community/wireless/zigbee-and-thread/knowledge-base.entry.html/2018/11/29/a_reliable_way_fors-OTah).

## .sls Projects Used ##

z3light_enddevice_mg12.sls

z3light_router_mg12.sls

z3switch_sed_mg12.sls

## How to Port to Another Part ##

Please refer to [Migrating Projects from Application Framework V2 to the Zigbee Application Framework in Simplicity Studio’s AppBuilder](https://www.silabs.com/community/wireless/zigbee-and-thread/knowledge-base.entry.html/2019/05/30/migrating_projectsf-AsOr).