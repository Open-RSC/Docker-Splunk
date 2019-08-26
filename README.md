This allows a Docker container for Splunk to be quickly deployed and routed through the Docker Nginx proxy.

You will need to modify the following fields in ".env"

```
# Nginx
NGINX_HOST=rsccabbage.com
```

You will need to edit within this folder "etc/system/default/props.conf" to set the server timezone

```
[default]
TZ = America/New_York
```