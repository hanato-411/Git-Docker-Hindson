# ベースとなるイメージを指定
FROM python:3.12-slim

# コンテナ内での作業ディレクトリを設定
WORKDIR /app

# ローカルの main.py をコンテナの /app/ にコピー
COPY main.py .

# コンテナが起動したときに実行されるコマンド
CMD ["python3", "main.py"]