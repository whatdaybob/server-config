# Docker Compose Files

This is my personal compose files, it contains the below software.

## [HomeAssistant_Compose](/HomeAssistant_Compose)

- [Home Assistant](https://www.home-assistant.io/) - Open source home automation with local control as its primary goal.

- [Mosquitto MQTT](https://mosquitto.org/) - Open source and lightweight MQTT broker.

- [Mariadb](https://mariadb.org/) - relational database for Home Assistant, replaces the inbuilt recorder integration.

- [HA-Dockermon](https://philhawthorne.com/ha-dockermon-use-home-assistant-to-monitor-start-or-stop-docker-containers/) - Links HA to the Docker Engine.

- [Node-RED](https://nodered.org) - Flow-based programming for the Internet of Things. Used to create new sensors and automations.

- [Xbox Smartglass REST](https://github.com/OpenXbox/xbox-smartglass-core-python) - A custom built docker using the openxbox implementation of their Xbox One SmartGlass RESTful server to allow an Xbox as a media player in HA.

- [Home Assistant - Monitoring API](https://github.com/ned-kelly/ha-monitor-api/) - lightweight API designed to expose the system's current metrics as a simple JSON endpoint that your Home Assistant instance can query.

- [Zigbee2mqtt](https://www.zigbee2mqtt.io/) - An open-source Zigbee to MQTT bridge to get rid of proprietary Zigbee Bridges

- [Zigbee2MqttAssistant](https://github.com/yllibed/Zigbee2MqttAssistant) - A GUI for Zigbee2Mqtt running in docker.

- [ESPHome](https://esphome.io/) - A system to control your ESP8266/ESP32 by simple yet powerful configuration files and control them remotely through Home Automation systems.

- [Airconnect](https://github.com/philippe44/AirConnect/) - Allows you to use AirPlay to stream to UPnP/Sonos & Chromecast devices.

- [bt-mqtt-gateway](https://github.com/zewelor/bt-mqtt-gateway) - A bluetooth to MQTT gateway, easily extensible via custom workers.

## [Media_Compose](/Media_Compose)

- [NZBGet](https://nzbget.net/) - A full featured usenet downloader.

- [Sonarr](https://sonarr.tv/) - A Smart PVR for newsgroup.

- [Radarr](https://radarr.video/) - A fork of Sonarr to work with movies.

- [Tautulli](https://tautulli.com/) - A web application to monitor, view analytics, and receive notifications about my Plex Media Server.

## [Metrics_Compose](/Metrics_Compose)

- [Prometheus](https://prometheus.io/) - A time series database for long term storage of sensor data.

- [Grafana](https://grafana.com/) - A tool for beautiful monitoring and metric analytics.

- [cAdvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers.

- [Node exporter](https://github.com/prometheus/node_exporter) - Exporter to Prometheus for machine metrics.

- [Alertmanager](https://github.com/prometheus/alertmanager) - Handles alerts sent by client applications such as the Prometheus server.

- [Dozzle](https://github.com/amir20/dozzle) - Realtime log viewer for docker containers.

- [unifi-poller](https://github.com/unifi-poller/unifi-poller) - Collects UniFi controller data and reports it to Prometheus.

- [Adminer](https://www.adminer.org/) - Database management in a single PHP file.

## [Network_Compose](/Network_Compose)

- [GoDaddy-ddns](https://github.com/peteward44/docker-godaddy-ddns) - DDNS service for godaddy domains.

- [IPsec VPN Server](https://github.com/hwdsl2/setup-ipsec-vpn) - Used to encrypts my network traffic.

- [Caddy](https://caddyserver.com/) - HTTP/2 web server with automatic HTTPS.

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - network-wide software for blocking ads & tracking.

- [MongoDB](https://www.mongodb.com/) - Database used for my Unifi Controller.

- [unifi-docker](https://github.com/jacobalberty/unifi-docker/) - Dockerised Unifi Controller.
