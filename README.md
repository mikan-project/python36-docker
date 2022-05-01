# 未完Study用 Python Docker コンテナ

Version: 3.6.x
Installed Package:

- discord.py

## 使い方

1. Docker Desktop をインストール
2. このレポジトリをcloneする

```bash
git clone git@github.com:mikan-project/python36-docker
```

3. cloneしたディレクトリ上で以下のコマンドを実行
   
```bash
docker compose up -d
```

4. 以下のコマンドを実行して、CLIを起動
```bash
docker exec -it python3.6 bash
```

5. `python --version`を実行して、Pythonのバージョンが出れば起動完了