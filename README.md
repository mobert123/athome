# athome

This repository serves the purpose of storing config files and scripts that I use in my home network.

# Services

The following Services are currently used in my homelab and can be setup according to this documentation.

1. [Dockge](/README.md#dockge)
2. [Homer](/README.md#homer)

## Dockge
### Installation

1. Create Folders and download the `compose.yml` File.
```bash
mkdir /opt/dockge/ /opt/stacks/
curl -o /opt/dockge/compose.yml https://raw.githubusercontent.com/mobert123/athome/main/services/dockge/compose.yml
```
2. Start the Container
```bash
cd /opt/dockge/ && docker compose up -d
```
3. Access Dockge on `http://localhost:5001/`

## Homer
https://github.com/bastienwirtz/homer
### Installation
1. Create a Folder under `/opt/stacks/` and download the `compose.yml` File.
```bash
mkdir /opt/stacks/homer/
curl -o /opt/stacks/homer/compose.yml https://raw.githubusercontent.com/mobert123/athome/main/services/homer/compose.yml
```
2. Start the Container
```bash
cd /opt/stacks/homer/ && docker compose up -d
```
3. Configure the Dashboard under `/opt/stacks/homer/assets/config.yml`
4. Access Homer on `http://localhost:8081/`