# 一人でたびにでるもんアプリ
一人旅行向けアプリ。一人は寂しくない。楽しい。；；

## 構成
```
- backend: 
    - Go(Gin)
    - PostgreSQL
- frontend: 未定
```

## 開発時ルール
### ブランチ管理
ブランチは以下のルールで派生させて管理する
- 🚀：機能開発 `develop`ブランチから派生利用
- ✨：機能改善 `feature`ブランチから派生利用
- 🐛：バグ修正 `bugfix`ブランチから派生

### 課題管理
`github issue`を利用してプロジェクトの課題管理、機能開発を進める。
ブランチ名はissueで採番される番号を利用するため、
基本的には1. issueを作成→2. ブランチ作成 の順序で開発を進める
PRが承認されてマージが完了した際には適宜issueをcloseする。

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