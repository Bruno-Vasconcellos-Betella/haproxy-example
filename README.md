# haproxy-example


#### RUN
```docker-compose up -d```


#### Description

On this example his possible to working a loadbalancer with 2 servers running and distributing the requests.

if one server down, only the UP server can response until the down server back to response on healthcheck.
