# SampleAppDocker

Rails Tutorial 第3章を実行するための環境です。

## 使い方
```
$ git clone https://github.com/atarubift/sample_app_docker.git
$ docker-compose build
$ docker-compose up -d
$ docker-compose run --rm web bundle exec rails db:create
```



