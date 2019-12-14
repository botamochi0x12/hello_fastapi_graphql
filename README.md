## インストール
```bash
$ git clone https://github.com/sattosan/hello_fastapi_graphql.git

$ docker-compose up -d --build
```

## GraphiQLにアクセス
http://127.0.0.1:8000/graphql

## クエリの実行
```graphql
{
  hello(name: "FastAPI")
}
```