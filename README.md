# my-dashboard-docker

This folder contains Docker Compose configuration and supporting files for the project infrastructure.

## Contents

- docker-compose.yml: Main orchestration file
- mysql/: Database initialization scripts
- nginx/: Web server configuration

## Usage

Run the stack:

```sh
docker-compose up -d
```

## Notes

- Environment variables are managed via .env files
- Logs and temporary files are ignored via .gitignore
