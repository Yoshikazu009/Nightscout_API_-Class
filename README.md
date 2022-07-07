# Nightscout API Class

Nightscoutに格納された血糖値をAPIコールして取得するクラス

## ファイル名 nightscout_api.py

## メソッド

### get_sgv() 最新の血糖値を取得するメソッド

# Requirement

* requests

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

実行結果

```text
306
```


# Note

インスタンス変数urlの値を利用者のNightscoutのURLに書き換える。

# Author

* 作成者   たかしま・よしかず
* E-mail  yoshikazu.takashima@nifty.com

# License

"nightscout_api.py" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
