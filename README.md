# nodejs-docker-webapp
Node.js Web アプリケーションを Docker 化する (https://nodejs.org/ja/docs/guides/nodejs-docker-webapp/)

### 環境構築
```
// build
$ docker build -t <your username>/nodejs-docker-webapp

// run
$ docker run -p 49160:8080 -d <your username>/nodejs-docker-webapp
```

