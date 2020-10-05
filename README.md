# Tasmota Plus
UBWH has developed an enhanced version of [Tasmota](https://tasmota.github.io/docs/ "Tasmota") with additional features making it better suited for use by IT professionals.

## Why Tasmota
[Internet of Things](https://en.wikipedia.org/wiki/Internet_of_things "IoT") (IoT) devices are Internet-connected smart appliances. 

Unfortunately, many IoT devices are controlled via a cloud server; commonly in China. Also, there is generally no way to control these devices using remote commands from (e.g.) a PHP script running on a separate computer.

Tasmota devices work differently; they are controlled via
1. the built-in Web server [GUI](https://en.wikipedia.org/wiki/Graphical_user_interface)
1. http commands: e.g. http://<ip>/cm?cmnd=Power%20On
1. [MQTT]()
1. [openHAB]()
1. [Many others...](https://tasmota.github.io/docs/Integrations/)
  
## Enhancements
**Tasmota Plus** has these enhancements over Tasmota.
| Feature                        | Comment       
| :------------------------------|:-------------| 
| WAN security                   | Prevent commands being executed unless coming from a nominated IP address
| Timer configuration page       | Allowing timer controls such a 'Turn ON at Sunset plus 15 mins'
| Clock configuration page       | Allowing setting of parameters (Time zone, Daylight saving, ...) so that Real Time Clock is accurate
| WiFi signal strength indicator | Easy visualisation of WiFi signal
| Ping watchdogs                 | Enabling cycling of socket power if pings to a nominated IP address fail



