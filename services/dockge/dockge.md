# Dockge Installation

1. Create a folder for Dockge and another folder for the Stacks
```
mkdir /opt/dockge/ /opt/stacks/
```
2. Download `compose.yml` 
```
cd /opt/dockge/
curl -O https://github.com/mobert123/athome/blob/main/services/dockge/compose.yml
```
3. Start Dockge `docker compose up -d`