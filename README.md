# sweets_sdk
Sweets all services SDK

## How to use
```
# Check services update and upgrade
# ※Select the appropriate branch
$ git submodule foreach git pull origin develop

# Bulid and start
$ docker-compose build
$ docker-compose up
```

## Service List
- POS API
    - http://0.0.0.0:3000
- POS APP
    - http://0.0.0.0:13000
- Tpay API
    - http://0.0.0.0:9000
- Reader
    - http://0.0.0.0:8000
