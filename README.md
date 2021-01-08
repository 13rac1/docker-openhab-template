# OpenHAB with Docker and Git Template

[OpenHAB][openhab] is a Java-based Home Automation system. This template
provides a pre-configured [Docker Compose][docker-compose] file and
`.gitignore` to ignore extraneous files for a reduced repository size.

Note: [openHABian][openHABian] is the recommended install method for Raspberry
Pi devices, but this configuration is ideal for multi-use devices.

[openhab]: https://www.openhab.org/
[docker-compose]: https://docs.docker.com/compose/
[openHABian]: https://www.openhab.org/docs/installation/openhabian.html

## Usage

1. Purchase a [GoControl Z-Wave/Zigbee HUSBZB-1 USB Hub][husbzb] or similar device.
2. Decide where to run OpenHAB, a Raspberry Pi 4 is ideal.
3. Install Docker and Docker-Compose
4. Clone your copy of this respository
5. `docker-compose up`

Make commits as needed.

[husbzb]: https://amzn.to/3i29311

## Reference

* The primary competition to OpenHAB is [Home Assistant][home-assistant]. Try
  it out also to compare before finalizing your setup.

[home-assistant]: https://www.home-assistant.io/

## TODO

Make more similar to openHABian by configuring:
* [Mosquitto](https://mosquitto.org/) MQTT broker
* The [InfluxDB](https://www.influxdata.com/) database to store home automation
  data and [Grafana](https://grafana.com/) to visualize it
* FIND, the[Framework for Internal Navigation and Discovery](https://www.internalpositioning.com/)
