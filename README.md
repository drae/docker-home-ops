## My docker config for frostwolf.io (apollo)

Till there is an ansible script run, copy .env.sample to .env and change the variables then run:

```shell
set -a && . ../.env && cat docker-compose.yaml | envsubst | docker-compose up -d
```
