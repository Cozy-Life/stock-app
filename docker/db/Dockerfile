FROM postgres:14-alpine

# シェル設定
SHELL ["/bin/bash", "-c"]

# SQLファイルを初期化スクリプトの場所にコピー
COPY ./ddl/*.sql /docker-entrypoint-initdb.d/

