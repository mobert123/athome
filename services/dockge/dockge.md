# Dockge Installation

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