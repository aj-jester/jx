# How to make a KOTS release

## Set 2 environment variables
`REPLICATED_APP`

`REPLICATED_API_TOKEN`

The KOTS [quickstart guide](https://kots.io/vendor/guides/quickstart/) goes into detail how to get these values.

## Run make command
From repo root, run
```shell
make --directory=kots release
```
