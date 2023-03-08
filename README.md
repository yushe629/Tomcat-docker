# nginx - Tomcat docker sample
nginxとTomcatをdocker上で動かすサンプル

## 環境設定
```
    $ cd nginx-server/conf.d
    $ cp nginx_sample.conf nginx.conf
```
`nginx.conf`の`location.proxy_pass`をローカルIPに書き換える


## 起動
```
    docker-compose up --build
```

