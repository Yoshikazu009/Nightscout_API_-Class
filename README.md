# Name（リポジトリ/プロジェクト/OSSなどの名前）

分かりやすくてカッコイイ名前をつける（今回は"hoge"という名前をつける）

"hoge"が何かを簡潔に紹介する

# DEMO

"hoge"の魅力が直感的に伝えわるデモ動画や図解を載せる

# Features

"hoge"のセールスポイントや差別化などを説明する

# Requirement

"hoge"を動かすのに必要なライブラリなどを列挙する

* huga 3.5.2
* hogehuga 1.0.2

# Installation

カレントディレクトリ下にファイル"nightscout_api.py“を配置する。

# Usage

コード例　Nightscoutにエントリーされた最新の血糖値を標準出力する。

```python
import nightscout_api
#最新の血糖値を取得して標準出力
api = Nightscout_API() #インスタンス定義
api.url = "https://xxxxxx.herokuapp.com" #NightscoutのURLを設定
print(api.get_sgv()) #最新の血糖値を標準出力する。
```

# Note

nstun

# Author

* 作成者   たかしま・よしかず
* E-mail  yoshikazu.takashima@nifty.com

# License

"nightscout_api.py" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
