My Homescapes - Android PWA

GitHub Pagesで公開する手順:
1. GitHubのブラウザ版で新しいPublicリポジトリを作成。
2. このフォルダ内の7ファイル（index.html, style.css, app.js, sw.js, manifest.webmanifest, icon-192.png, icon-512.png）をリポジトリの最上位へアップロード。
3. Settings > Pages > Build and deployment > Deploy from a branch を選択。Branch: main、Folder: /(root) を保存。
4. Pagesに表示されたHTTPS URLをAndroidのChromeで開き、メニューから「ホーム画面に追加」または「アプリをインストール」。
5. データは各端末のブラウザ内に保存。設定（歯車）からJSONバックアップを定期的に書き出してください。

注意: GitHub Pagesで公開するコードは誰でも閲覧可能です。タスクデータ自体はアップロードされず、端末内に保存されます。アプリ削除・ブラウザデータ削除などで消えることがあるのでバックアップ必須です。
