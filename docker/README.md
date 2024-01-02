```
docker-compose up -d --build
```

```
docker-compose down
```

```
docker rm -f `コンテナid`
```

```
docker build -t `タグ名` Dockerfileのパス
```

```
docker run -it -v `ホストマシンパス`:`コンテナパス` `タグ名`
```
