# 一人でたびにでるもんアプリ
一人旅行向けアプリ。一人は寂しくない。楽しい。；；

## 構成
```
- backend: 
    - Go(Gin)
    - PostgreSQL
- frontend: 未定
```

## 前提条件
以下が利用できる環境での開発を想定します。
- WSL2
- Docker / Docker Compose

## 動作確認
### backend
1. .envファイルの作成
`.env.example`をコピーして.envを作成する
```
cd backend
cp .env.example .env
```
2. コンテナ立ち上げ
```
docker compose up -d
```

### frontend
未実装