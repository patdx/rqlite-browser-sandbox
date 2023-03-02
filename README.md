# How to use

In one terminal, run:

```sh
rqlited -node-id 1 -auth config.json -http-addr localhost:4100 node1
```

In another terminal, run:

```sh
caddy run Caddyfile --watch
```
