# Personal Nextcloud with Docker

This is a self-hosted Nextcloud setup using Docker on a Linux server, configured without a domain.

## Contents

- `docker-compose.yml` — service definitions
- `setup-scripts/init-lvm.sh` — optional LVM mounting script
- `.gitignore` — excludes sensitive folders

## Usage

```bash
docker-compose up -d

