# 説明
CORS 対策できない場合に nginx でヘッダーを書き換えて回避するために使用できる

# 使い方
1. default.conf の `proxy_pass` を開発サーバーに向ける
1. `$ docker compose up`
1. ngrok で http 80 を公開するなど
