<h1 align="center">Welcome to Monitoring 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> Monitoring solution setup with influx, grafana and telegraf.

Stack
- **Influxdb**: open source time-series database. (DB)
- **Grafana**: open source observability dashboards. (UI)
- **Telegraf**: influxdb data collection agent. (Metrics collector)

## Usage

Deploy the services.
```sh
docker-compose up 
```

#### Grafana
- http://localhost:3000
  - Default credentials (admin/admin)

#### Connect Grafana with the Influx data source.

- host. `http://influxdb:8086`

#### Telegraf

- Telegraf have started running, and inserting data on influxdb database. Name is specified in `telegraf.conf`


I attach a .json dashboard already configured for telegraf. (Import it)


## Author

👤 **Pablo Ospino**

* Website: https://ospino.me
* Github: [@ospinooo](https://github.com/ospinooo)
* LinkedIn: [@pabloospino](https://linkedin.com/in/pabloospino)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_