## Docker compose file for Grafana and dependancies on a Raspberry Pi

Setting up a repo to track changes to my docker-compose file that will pull and run the following containers;
- Prometheus (time series database)
- cadvisorARM (provides docker container metrics, but in ARM flavour)
- Grafana (visualise data)
- Redis (noSQL database, required for cadvisor)

You can read more about my projects over on https://ducko.uk