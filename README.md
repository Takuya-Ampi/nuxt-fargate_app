# nuxt-fargate_app

## インストール
$ npm ci

## Dockerfileのビルド
docker build -t nuxt-fargate_app .

### start
docker run -p 3000:3000 nuxt-fargate_app

上記実行後localhost:3000で確認できる
