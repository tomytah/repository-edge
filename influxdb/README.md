# Community Hass.io Add-ons: InfluxDB

[![Release][release-shield]][release] ![Project Stage][project-stage-shield] ![Project Maintenance][maintenance-shield]

[![Discord][discord-shield]][discord] [![Community Forum][forum-shield]][forum]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

Scalable datastore for metrics, events, and real-time analytics.

## About

InfluxDB is an open source time series database optimized for high-write-volume.
It's useful for recording metrics, sensor data, events,
and performing analytics. It exposes an HTTP API for client interaction and if
often used in combination with Grafana to visualize the data.

This add-on comes with Chronograf & Kapacitor pre-installed as well. Which
gives you a nice InfluxDB admin interface for managing your users, databases,
data retention settings, and lets you peek inside the database using the
Data Explorer.

[Click here for the full documentation][docs]

![Chronograf in the Home Assistant Frontend][screenshot]

## WARNING! THIS IS AN EDGE VERSION!

This Hass.io Add-ons repository contains edge builds of add-ons. Edge builds
add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/hassio-addons/repository>

[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg
[buymeacoffee]: https://www.buymeacoffee.com/frenck
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg
[discord]: https://discord.gg/c5DvZ4e
[docs]: https://github.com/hassio-addons/addon-influxdb/blob/b0d982f/README.md
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io/t/community-hass-io-add-on-influxdb/54491?u=frenck
[maintenance-shield]: https://img.shields.io/maintenance/yes/2018.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[release-shield]: https://img.shields.io/badge/version-b0d982f-blue.svg
[release]: https://github.com/hassio-addons/addon-influxdb/tree/b0d982f
[screenshot]: https://github.com/hassio-addons/addon-influxdb/raw/master/images/screenshot.png