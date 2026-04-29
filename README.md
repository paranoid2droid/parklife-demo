# parklife — 関東の公園で出会える生き物

関東 4 都県の公園 **209 件** ／ 物種 **2,982 種** ／ 観察記録 **約 29,000 件**。
公園公式サイトと iNaturalist の研究グレード観察データから収集。

🔗 **インタラクティブ Demo**: <https://paranoid2droid.github.io/parklife-demo/>

## 中身

| ファイル | 用途 |
|---|---|
| [`index.html`](index.html) | ブラウザで開く可視化 demo（地図 + 物種写真 + フィルタ） |
| [`REPORT.md`](REPORT.md) | 多様性チャンピオン・各分類のトップ常連・月別ハイライト |
| [`BIRDS.md`](BIRDS.md) | 鳥類季節レポート（留鳥 / 冬鳥 / 夏鳥） |
| [`ENDEMIC.md`](ENDEMIC.md) | 小笠原・八丈の固有種 |
| [`parks_md/`](parks_md/INDEX.md) | 公園 1 件ごとの種リスト Markdown（209 件） |
| [`parklife.json`](parklife.json) | 全データ JSON snapshot（16 MB） |
| [`park_species.ndjson`](park_species.ndjson) | (公園, 物種) 流式 NDJSON（8 MB） |

## データソース

- 東京都公園協会の公式サイト「花の見ごろ情報」
- 神奈川 / 千葉 / 埼玉 県立公園の各サイト
- iNaturalist Research Grade observations（locale=ja, place=Japan, 半径 1.5 km）
- iNaturalist Plant Phenology annotations（開花月のしぼり込み）
- 物種学名は日本語版 Wikipedia の taxobox から抽出

## 状況

- v1（2026-04-30）: 関東 4 都県 100% 公園カバー、98% 物種に学名と写真。
- 駐車場情報は約 2/3 の公園で確定（団体予約のみのケース等は慎重に「不明」のまま）。
- 小笠原・八丈の固有種カバレッジは v1 範囲外（移動コストを考えて優先度低）。
