# google-speechサンプル

## ライブラリ
- `google-cognitive-apis`

## 手順
1. `make init`で`protobuf`をインストールする
2. プロジェクト直下に`/tmp`を用意する
3. サービスアカウントに`Cloud Speech クライアント`権限を付与して、credentialファイルを生成する
4. credentialファイルを`cred.json`という名前で、作成した`/tmp`に置く
    （または、ソースコードでファイル名を指定している部分を修正する）
5. 音声ファイルを`test.wav`という名前で、作成した`/tmp`に置く
    （または、ソースコードでファイル名を指定している部分を修正する）
