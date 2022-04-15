# Software for CO2 Monitor


MQTT driver (HomeAssistant conventions).
Based on https://github.com/dmage/co2mon and https://github.com/wirenboard/wb-mqtt-co2mon


For newer MT8057 revisions, please add -n command line switch to `DAEMON_ARGS`
in `/etc/init.d/co2mon-ha-mqtt` initscript.

## See also

  * [Original driver](https://github.com/dmage/co2mon)
  * [Original MQTT driver by WirenBoard](https://github.com/wirenboard/wb-mqtt-co2mon)
  * [HomeAssistant MQTT Conventions](https://www.home-assistant.io/docs/mqtt/discovery)
  * [ZyAura ZG01C Module Manual](http://www.zyaura.com/support/manual/pdf/ZyAura_CO2_Monitor_ZG01C_Module_ApplicationNote_141120.pdf)
  * [RevSpace CO2 Meter Hacking](https://revspace.nl/CO2MeterHacking)
  * [Photos of the device and the circuit board](http://habrahabr.ru/company/masterkit/blog/248403/)
  * [Pre-alpha of GNOME Shell Extension](https://github.com/dmage/gnome-shell-extensions-co2mon)
