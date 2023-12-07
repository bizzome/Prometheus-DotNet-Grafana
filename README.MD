
# Observability with Prometheus and Grafana

This repository to demonstrates how to instrument and observe a simple .NET API.

## ☕ The stack
- Docker
- Docker Compose
- .NET (Inside Docker)
- K6 (Inside Docker)
- Prometheus (Inside Docker)
- AlertManager (Inside Docker)
- Grafana (Inside Docker)


## 💻  Prerequisites

Before you start, check if you have all the prerequisites:

-   `Docker` installed.
-   `Docker Compose` installed.

## ☕ Run the project

Go to the root folder of this project and simply run the command below:

`docker compose up -d`

## 🛎️  Alerts!

To receive alerts by e-mail, you should change the information in [this file here](https://github.com/bizzome/Prometheus---DotNet---Grafana/blob/master/alertmanager/alertmanager.yml)

## 🚀 Run a stress test with K6

Go to the root folder of this project and simply run the command below:

`docker run --net=host --rm -i grafana/k6 run - <k6/test.js`


## 😄 Improve this code!
Want to improve this repository? Feel free to open an issue with ideas or make a pull request.

Forked from [Barros42](https://github.com/Barros42/Prometheus-DotNet-Grafana)
