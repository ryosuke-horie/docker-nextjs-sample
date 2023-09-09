# docker-Next.js-Sample

## 概要
Next.jsの開発環境をDockerで構築するサンプルアプリケーション。

## 参考記事
[Next.js(TypeScript) × docker(Compose V2) 最速構築Tips.](https://qiita.com/Keichan_15/items/4fc605895fef2a33b629)

## Next.jsを立ち上げるまでの手順
1. Dockerfile作成
2. compose.yaml作成
3. WSLで `docker compose run --rm app sh -c 'npx create-next-app . --typescript'`を実行
4. WSLで`docker compose up`を実行しNext.jsを起動