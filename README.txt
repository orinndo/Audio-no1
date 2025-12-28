# GitHub Pages 用：QRで即再生する音声ガイド（最小セット）

このフォルダをそのまま GitHub にアップロードして Pages を有効化すると、
QRコード → Webページ → 音声再生 ができます。

## ファイル
- index.html  : 再生ページ（自動再生を試み、ブロックされたらボタン表示）
- guide1.m4a   : 音声（AAC）

## 手順（GitHub Pages）
1) GitHubで新規リポジトリ作成（例: audio-guide）
2) このフォルダの2ファイルをリポジトリ直下にアップロード
3) リポジトリ → Settings → Pages
   - Build and deployment: Deploy from a branch
   - Branch: main / (root) を選択 → Save
4) しばらくすると Pages のURLが表示されます
   例: https://<ユーザー名>.github.io/audio-guide/

## QRコード化するURL
- そのままトップでOK: https://<ユーザー名>.github.io/audio-guide/
（index.html が自動で開きます）

## 注意（iPhoneの自動再生）
iPhone/Safariは状況によって自動再生がブロックされることがあります。
その場合でも「▶︎ Tap to play」を1回押せば確実に再生できます。
