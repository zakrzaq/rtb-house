# RTB HOUSE FS Technical Task

## REQUIREMENTS

docker
docker compose (v.2)

## SETUP

This is parent project that requires **three** functional submodules. They can be setup using:

`git submodule add <url> .`

**FROTNEND CLIENT:** In `client` dir -> [rtb-client](https://github.com/zakrzaq/rtb-client)

**BACKEND SERVER:** In `server` dir -> [rtb-server](https://github.com/zakrzaq/rtb-server)

**DATABASE:** In `db` dir -> [rtb-db](https://github.com/zakrzaq/rtb-db)

### ENVs

Need to be setup in each submodule. Please refer to submodule README.

## RUN

`docker compose up`

