# Tango Loop (PWA)

## GitHub Pages で公開する手順
1. GitHub で新しいリポジトリを作成(例: `tango-loop`、Public)
2. このフォルダの中身(index.html, sw.js, manifest.webmanifest, icons/, .nojekyll)をリポジトリ直下にアップロード
3. Settings → Pages → Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして Save
4. 1〜2分後に `https://<ユーザー名>.github.io/tango-loop/` で公開されます

## スマホにインストール
- iPhone(Safari): 共有ボタン → 「ホーム画面に追加」
- Android(Chrome): メニュー → 「アプリをインストール」

## 更新するとき
index.html を差し替えたら、sw.js の `CACHE = 'tango-loop-v2'` の番号を上げてください(v2, v3…)。

## データについて
学習データはその端末・そのブラウザのlocalStorageに保存されます。端末間の同期はありません。
設定 →「バックアップ」で .json ファイルに書き出し・読み込みができます(機種変更やデータ消去の備えに)。
