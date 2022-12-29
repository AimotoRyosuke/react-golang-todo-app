# 起動方法
1. レポジトリをローカルにコピー
```
git clone git@github.com:AimotoRyosuke/react-golang-todo-app.git
```
2. プロジェクトに移動
```
cd react-golang-todo-app 
```
3. dockerイメージの作成
```
docker-compose build
```
4. dockerコンテナを起動
```
docker-compose up -d
```
5. 起動の確認
```
React
下記にアクセスできる（初回は3分、2回目以降1分程かかる）
http://localhost:3000/
```
```
Go
下記にアクセスできる
http://localhost:8000/
```
```
mysql
下記にアクセスできる
Host：127.0.0.1
Username：root
Password：root_password
Port：3306
```