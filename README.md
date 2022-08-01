# training-redis
Redis with RedisInsight over Raspberry running on Docker

## Requirements
 - Docker compose

## Steps
### 1. Clone the repository
```shell
git clone https://github.com/sebastianaf/training-redis
cd training-redis
```
### 2. Expose the `-ports`
Uncomment the ports flag in `docker-compose.yml` to be able for access the services.

### 3. Change `org` and `project` names [Optional]
It's recommend to change all the names (in `docker-compose.yml`) named with `org` and `project` with your own organization name and project name.

### 4. Run
```shell
docker compose -p org-project up -d
```
After type and run the command go to [localhost:9020](http://localhost:9020)