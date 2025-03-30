# qbittorrent portforward

This is intended to run as a sidecar in a gluetun + qbittorrent setup. This will monitor the forwarded_port file and change that setting in qbittorrent.

## Configuration

|---|---|
| Environment Variable | Description |
| PORT_FORWARD_FILE | location of gluetun generated file |
| QBT_URL | location of the qbittorrent api |
