# zeebe-docker-compose

Creating exprimental zeebe profiles

## gateway-cluster-simple monitor (WIP)

standalone gateway + 3 node cluster + simple monitor

Simple monitor is always trying to connect to `node0`, and when simple monitor starts and `node0` is not ready, while other nodes are, it wont connect to other nodes.
Throws `Unable to get live cluster connection` exception.
