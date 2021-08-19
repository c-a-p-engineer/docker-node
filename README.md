# Docker node環境

# Requirement
* [docker](https://www.docker.com/)

# Install
`.env.example` をコピー `.env` を作成。
各種設定値を修正。

Docker起動
```
docker-compose up -d --build
```

コンテナに入る
```
docker exec -it node sh
```

# Usage

## Nginx
http://localhost:8080/

# Note

# Author
* [こぴぺたん](https://twitter.com/c_a_p_engineer)

# License
[MIT license](https://en.wikipedia.org/wiki/MIT_License).
