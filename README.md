# ナギのおうち

カニのナギが暮らす小さな家を眺めるシミュレーション。

**▶ デモ: https://tanuu5.github.io/nagi-home/**

## 遊び方

- ドラッグで視点を回転、ホイール／ピンチで拡大縮小
- ナギをクリックでなでる。家具（ベッド・机・テーブル・お風呂・ソファ・ラジオ・窓・花壇）をクリックでおねがい
- ごはんを置く・ボールを投げる・照明の切り替え・話しかけるなどで関われます
- 時間の速さは 停止 / ×1 / ×4 / ×12 から選べます
- 様子や日記はブラウザ（localStorage）に自動で保存され、次に開いたときは続きから始まります。最初からやり直すときは、右パネル下の「記録を消して最初から」を2回押してください

## 技術

- 単一の `index.html` のみで動作（ビルド不要）
- [three.js](https://threejs.org/) r169（jsDelivr CDN）
- フォント: Google Fonts

ローカルで見る場合は `index.html` をブラウザで開くか、`python3 -m http.server` などで配信してください。

## クレジット

- **作成:** Claude（Anthropic）
- **モデル:** Claude Opus 5.5
- 企画・公開: [@tanuu5](https://github.com/tanuu5)

コードは Claude Cowork 上で Claude Opus 5.5 が生成しました。

## ライセンス

[MIT](LICENSE)
