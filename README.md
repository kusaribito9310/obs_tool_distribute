# OBSTool 配布ページ

DiscordのVC参加者とテキストチャットを、OBSのブラウザソースへ表示するWindows用ツールです。

## ダウンロード

- [最新版 OBSTool.exe](https://github.com/kusaribito9310/obs_tool_distribute/releases/latest/download/OBSTool.exe)
- [全旧バージョン対応の更新パッチ](https://github.com/kusaribito9310/obs_tool_distribute/releases/latest/download/OBSTool-update.exe)

初めて使う場合は `OBSTool.exe` をダウンロードしてください。インストールは不要です。

既に使用している場合は、OBSToolを終了してから `OBSTool-update.exe` を起動し、現在使用中のOBSTool exeを選択してください。どの旧バージョンからでも最新版へ更新でき、更新前のexeは同じフォルダへバックアップされます。

## 操作方法

1. Discordデスクトップ版を起動します。
2. `OBSTool.exe` を起動します。
3. 初回だけDiscordの連携画面で承認します。
4. Discordの開発者モードを有効にし、対象サーバーを右クリックして「サーバーIDをコピー」します。
5. OBSToolへGuild IDを入力し、「取得」を押します。
6. カテゴリ、VC、テキストチャンネルを選択し、「設定を保存して反映」を押します。
7. OBSでブラウザソースを追加し、URLへ `http://localhost:8080/overlay`、幅へ `1920`、高さへ `1080` を設定します。

表示位置は右側のプレビューでドラッグできます。VC枠・チャット枠の辺または四隅をドラッグするとサイズを変更できます。Discordの表示名をすぐ反映したい場合は「表示名を強制更新」を押してください。

## Discord Botコマンド

- `/obstool guide` — 操作方法
- `/obstool download` — 最新版exe
- `/obstool update` — 更新パッチ

## 動作条件

- Windows 10 / 11（64bit）
- Discordデスクトップ版
- OBS Studio
- 利用対象として承認されたDiscordアカウント

Node.jsなどの開発環境は不要です。

## Windowsの警告

コード署名証明書を設定していないため、初回起動時にWindows SmartScreenが表示される場合があります。その場合は配布元とファイル名を確認してから「詳細情報」→「実行」を選択してください。
