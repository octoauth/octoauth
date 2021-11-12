# OctoAuth

*This project is used for development purposes only and contains commands and config files for OctoAuth development*

## Requirements

- docker-compose
- make

specific to frontend development
- vuejs

specific to backend development
- python
- virtualenv

## Quickstart

To clone all projects required for OctoAuth development, run

```
make clone
```

You can run all services to check that everything works fine using

```
docker-compose up
```

Services included:
- authorization-server
- account-dashboard
- fileserver
- development-proxy
- database
- database-ui
