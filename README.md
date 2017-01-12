# OSPi-SNMP
A plugin for Dan-in-CA/SIP to add SNMP polling and control based on returned OID values

These files started from the Proto examples at https://github.com/Dan-in-CA/sip_plugins/tree/master/proto

The purpose of this project is to contain my code for a plugin to allow an opensprinkler Pi to poll SNMP device for temperature and humidity, and use that to control sprinklers (in addition to watering schedules). It is intended to run one or more lines of misters, or other similar devices, to maintain temperature and humidity with acceptable parameters within a greenhouse environment. Ideally, it will also activate the OSPi onboard relay to control fans or heater(s) (although of course you can use any OSPi output to drive an external relay to trigger various devices). 

A "lockout" period should be allowed that will prevent the misters being used "too late" in the day (to control nocturnal wetness and its related diseases). 

The target SNMP device is a Jacarta InterSeptor (http://www.jacarta.com/interseptor/), but any SNMP OID should be usable. 

https://orchids-on-a-balcony.blogspot.com
