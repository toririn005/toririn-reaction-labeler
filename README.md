# とりりん リアクションラベラー

iPhone Safari対応の静的Webアプリです。既存のPython切り抜きツールは変更しません。

## 公開方法（GitHub Pages）
1. GitHubで新しい公開リポジトリを作成します（例: toririn-reaction-labeler）。
2. `index.html` をリポジトリのルートにアップロードします。
3. Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save。
4. 発行された HTTPS URL を iPhone Safari で開きます。
5. Safariの共有メニューから「ホーム画面に追加」も可能です。

注意: 公開リポジトリではソースコードは公開されますが、入力したラベルはこの版ではブラウザ内のみに保存され、GitHubへ送信されません。
YouTube動画は埋め込み可能な動画のみ再生できます。Safariの再生制約で操作が制限される場合があります。
ブラウザのデータ削除に備え、JSONバックアップとCSV書き出しを定期的に行ってください。
CSV列: video_id,time_seconds,label。時刻は動画先頭からの秒数です。
現在の版は動画1本分を端末内に保持します。別動画に切り替える前にCSV/JSONを保存してください。
