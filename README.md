# Next.jsのインストール
dockerコンテナにNext.jsのアプリケーションを作成する方法

## envファイル
```
cp .env.sample .env
```

## Next.jsアプリの作成
```
docker-compose build
```

## Dockerコンテナの起動（デーモン）
```
docker-compose up -d
```