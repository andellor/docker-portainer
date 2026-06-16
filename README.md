# docker-portainer

Manages the installation and updates for Docker, Portainer, and Portainer Agent.

## Supported OS

- Debian/Ubuntu

## Usage

Make the script executable:

```bash
chmod +x setup.sh
```

Then run with one of the available arguments:

```bash
./setup.sh help
./setup.sh install-docker
./setup.sh install-portainer
./setup.sh install-portainer-agent
./setup.sh update-portainer-agent
```

## Roadmap

- Auto-install Docker if not detected when running `install-portainer` or `install-portainer-agent`