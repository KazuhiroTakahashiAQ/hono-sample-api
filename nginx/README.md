# ビルド
```sh
// platformを指定してビルド
$ docker build --platform linux/amd64 -t hono-nginx:latest .
```

## Platform確認方法
- [ECSでNginxコンテナを起動時のexec /docker-entrypoint.sh: exec format error対応](https://zenn.dev/osachi/articles/32f61afe7f350f)
```sh
$ docker exec -it <container_id> /bin/bash
# uname -a
// amd64の場合
aarch64
```
