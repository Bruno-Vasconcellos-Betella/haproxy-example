# haproxy-example


#### Run
```docker-compose up -d```


#### Description

On this example his possible to working a loadbalancer with 2 servers running and distributing the requests.

if one server down, only the UP server can response until the down server back to response on healthcheck.

#### Test

```curl localhost:3005```


#### Stats

To see the monitoring servers and stats access the url: `http://localhost:3005/stats`
this URL can be change on the file `haproxy.cfg`, param `stats uri {{pathStatsUri}}`, change this parameter if have a path conflict with de service running.
