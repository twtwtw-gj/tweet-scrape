# TWEET SCRAPE

TwitterでツイートをAPI取得したり、Post送信したりするスクリプト群です。

main.py, post.py, request.pyがメインとして使えます。

### Usage

1. Twitterにアクセスして、Consumer keyその他取得する。
2. configure.pyファイルを作成して、以下を書き込む。
```Python
CONSUMER_KEY = <Consumer Key>
CONSUMER_SECRET = <Consumer Secret>
ACCESS_TOKEN = <Access Token>
ACCESS_TOKEN_SECRET = <Access Token Secret>
```
3. 実行する。
```bash
pip install -r requirement.txt
python main.py
```
このとき、Python3を利用すること。
