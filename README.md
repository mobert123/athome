# athome

This repository serves the purpose of storing config files and scripts that I use in my home network.

# Services

The following Services are currently used in my homelab and can be setup according to this documentation.

## Dockge
### Installation

1. Create Folders and download the `compose.yml` File.
```bash
mkdir /opt/dockge/ /opt/stacks/
curl -o /opt/dockge/ https://raw.githubusercontent.com/mobert123/athome/main/services/dockge/compose.yml
```
2. Start the Container
```bash
cd /opt/dockge/ && docker compose up -d
```
3. Access Dockge on `http://localhost:5001/`