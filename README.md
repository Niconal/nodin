nodin
=====

NodeJS SNMP Monitoring

###Current features:
- Monitor different devices/ports of devices via SNMP (hugin)
- Discover device states automatically/periodically (munin)
- Write SNMP Values to a Influx Database
- Configuration and states are stored in REDIS

###What should be possible in the future (aka ToDO): 
- Web-Interface for Values and configuration (module will be caled nodin)

## How to start nodin?
1. Get the databases to store your data
  * REDIS (stores all properties of your devices) -> http://redis.io/ 
  * INFLUXDB (stores all values of your devices) -> http://influxdb.com/
2. Install the databases
3. Get and install the current version of nodeJS (including npm) -> http://nodejs.org/
4. Clone this repo
5. Enter the cloned directory and type in "npm install"
6. Start nodin by typing ./bin/www (please make sure the file is executeable)

* (Optional) To view your data you might also get grafana -> http://grafana.org/

###Where does the name come from?
Odin should be know, by the most people - otherwise: http://en.wikipedia.org/wiki/Odin 

Odins two birds were called hugin and munin they provided him information about the things going on around him - both names were already taken by other projects so I decided to use the a mixture of the programming language and the "master" of hugin and munin -> NodeJS + Odin = nodin
