# kibana-elastalert
Docker image with kibana and elastalert plugin

# Building

```
docker build --build-arg KIBANA_VERSION=6.4.0 --build-arg ELASTALERT_PLUGIN_VERSION=1.0.0 -t kibana-alestalert:6.4.0 .
```

# Running

Please mount a kibana config.yml file to `/usr/share/kibana/config/kibana.yml`. Example config.yml file is provided in repo.
