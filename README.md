# リポジトリ名
https://github.com/hashiguchi1544/web_api

## どのようなプログラムか
WebAPIを利用した複数のプログラム。
- ぐるなび店舗の検索
- 本日の占いアプリ

(APIのアクセスキーは、環境変数にしてます)

## 学習目的
Pythonによるリクエスト、JSONによるレスポンスの流れの理解。

## 作成したプログラム
#### 占いアプリ

> 星座を選べば、その星座の本日の占い結果を表示する


##### ぐるなびの店舗検索
> 任意の検索ワードを入力したら、そのキーワードに適した店舗情報を表示する
## ディレクトリ
```bash
├── README.md
├── main
│   ├── fortune   ← 占い配信 Web ad Fortune 無料版 API
│   │   ├── choose_sign.py
│   │   └── fortune_api.py
│   └── gurunavi   ← ぐるなびAPI
│       └── guru_navi_app.py
├── memo.md

```

## 利用API
おもに無料枠やお試し版を利用。

[GURUBAVI WEB SERVICE](https://api.gnavi.co.jp/api/scope/)

[JugemKey](http://jugemkey.jp/api/waf/api_free.php)