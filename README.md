# 社会・弱点克服テスト

iPhone・iPadのSafari向け、社会の復習用Webテストです。

- `index.html`：20問のオリジナル問題、採点・解説、漢字の手書き練習、JSON/CSV出力と履歴の復元に対応
- 解答履歴は端末内のブラウザ保存領域に保存し、GitHubには自動送信しません
- 手書きの漢字は自動文字認識せず、正答と見比べて手動判定します
- ブラウザの保存データが消える場合に備えて、結果のJSONを定期的にバックアップしてください

## GitHub Pagesでの公開設定

**Settings → Pages → Build and deployment** で次を選択します。

1. Source：**Deploy from a branch**
2. Branch：**main**、Folder：**/(root)**
3. **Save**

公開後のURLは https://ohtsufsh-glitch.github.io/shakai-quiz/ です。

**注意：** 公開リポジトリの問題やHTMLは誰でも閲覧できます。氏名、受験番号、解答結果などの個人情報をGitHubにコミットしないでください。JSON/CSVには解答内容と日時などが含まれるため、保存・共有には注意してください。
