# Elephpas Naumanni

## Abstract

よわよわな PHP環境 でWebサーバのログを直接確認することなくエラーログを確認するためのスニペット。

## Usage

1. プロジェクトのルートに `.htaccess` と `naumann`ディレクトリ 一式をアップロード
    - 既に `.htaccess` が存在する場合は中身を追記してください
2. `naumann/log`ディレクトリ の権限を `777` にする
3. 試験する。ログは適宜 `naumann/log\error_log.log` をテキストダウンロードして確認する