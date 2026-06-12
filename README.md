# BOUBA · KIKI — 共感覚タイピング

![HTML](https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Web Audio](https://img.shields.io/badge/Web_Audio_API-FF9900?logoColor=white)
![No Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)

**デモ: https://uzuchan.github.io/Bouba-Kiki-Typing/**

丸い形は「ブーバ」、尖った形は「キキ」と呼ばれやすい——心理学で知られるブーバ/キキ効果（音と形のクロスモーダル対応）を、タイピングで遊ぶ作品です。画面に浮かぶ形に合わせて言葉を打つと、音と光で形が応えます。

## スクリーンショット

<!-- TODO: スクリーンショットを docs/screenshots/ に置いて、下のコメントを外してください。 -->
<!--
![プレイ画面](docs/screenshots/play.png)
-->

## モード

- **play** — 浮かんでくる形に対応する単語をタイプして消していくゲームモード
- **instrument** — スコアを気にせず、タイピングを楽器のように鳴らして遊ぶ自由モード

## 技術

- 単一HTMLファイル（外部依存ゼロ）
- Canvas による形の描画とアニメーション
- Web Audio API による効果音の合成（音声ファイル不使用）
