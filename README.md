# Dry-dock 

CI/Build environment. Uses docker-compose to build a local CI pipeline for testing. 

## Contains

- Archiva for maven repo
- Jenkins for CI
- gitlab for git repo

## Use

```
$docker-compose up
```

## Requires
- docker (tested with version 1.9.1)
- docker-compose (tested with version 1.5.1) 

## Services config
Still **NO** manual configuraiton for the services :disappointed:. 
The manual steps are here: [services-config.md](services-config.md)
