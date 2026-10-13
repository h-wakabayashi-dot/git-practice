# ベースとなるイメージを指定 (Nginxの公式イメージを使用)
FROM nginx:latest

# ホスト（自分のPC）のindex.htmlを、コンテナ内のNginxが配信するディレクトリにコピー
COPY index.html /usr/share/nginx/html/index.html