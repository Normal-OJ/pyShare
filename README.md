# pyShare

## prerequisite

- [docker compose](https://docs.docker.com/compose/)

## memo

### Clone

`git clone --recurse-submodules https://github.com/Normal-OJ/pyShare.git`
`cd pyShare`
`git submodule foreach --recursive git checkout master`

### Run all services

`docker-compose up -d`

or if you wanna rebuild

`docker-compose up --build -d`
