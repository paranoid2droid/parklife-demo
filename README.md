# parklife — 関東の公園で出会える生き物

関東 4 都県（東京・神奈川・千葉・埼玉）の **209 公園**、**2,982 物種**、**約 29,000 観察記録** を、
公園公式ページ + iNaturalist の研究グレード観察データから収集した可視化デモ。

🔗 **Demo**: https://paranoid2droid.github.io/parklife-demo/

## 機能

- 地図で公園を探す（Leaflet + OpenStreetMap）
- 月 / 分類 / 駐車場有無で絞り込み
- 物種名・学名・公園名で全文検索
- 各物種の写真（iNaturalist 提供）

## データソース

- 東京都立公園（東京都公園協会）— 「花の見ごろ情報」
- 神奈川 / 千葉 / 埼玉県立公園 — 各サイト
- iNaturalist Research Grade observations（locale=ja, place=Japan）
- 各種 species.scientific_name は日本語版 Wikipedia の taxobox 由来
- 駐車場情報は各公園 access ページから抽出

## ステータス

- v1（2026-04-30）: 関東 4 都県をカバー。
- 駐車場情報はまだ約 1/3 の公園で「不明」です（団体利用のみのケースなど慎重に判断中）。
