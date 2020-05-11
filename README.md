# docker-react

## 前提

プロジェクトは、`reactstudy01`で作成します。  
変更したい場合は、`docker-compose.yml` と `init.sh` のプロジェクト名を変更してください。  
reactstudy01　→　変更後プロジェクト名

## 環境構築
### Dockerビルド

```
docker-compose build
```

### プロジェクト初期化

```
./init.sh
```

### コンテナ起動

```
docker-compose up
```

### 確認

```
http://localhost:3000/
```
