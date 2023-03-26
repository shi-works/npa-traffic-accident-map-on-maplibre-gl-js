# 交通事故マップ on MapLibre GL JS
## Public Website
- https://shi-works.github.io/traffic-accident-map/
## サンプル画像
![image](https://user-images.githubusercontent.com/71203808/227756339-943c5006-102e-4c1e-9ff7-f9c5318571a3.png)

# traffic-accident-pmtiles
## データについて
- 本データは、警察庁が公開している、[交通事故統計情報のオープンデータ（2019年、2020年、2021年）の本票](https://www.npa.go.jp/publications/statistics/koutsuu/opendata/index_opendata.html)を[tippecanoe](https://github.com/felt/tippecanoe)で[PMTiles形式](https://github.com/protomaps/PMTiles)に変換したデータになります。
- オープンソースソフトウェアで構築

## データ配布
- `https://pmtiles-data.s3.ap-northeast-1.amazonaws.com/traffic-accident/honhyo_2019-2021_convert_v2.pmtiles`(171.5MB)

## ベクトルタイル設計情報
- 本票そのものを可能な限り生かしたデータです。
- tippecanoeによるデータの間引き（自動）を行っています。

### ズームレベル範囲
- 0-14

### 属性
- 本票の属性はそのまま生かしています。
- ただし、属性については、コード表をもとに読みやすい形式に変換しています。

## PMTiles Viewer
- PMTilesはPMTiles Viewerで閲覧することができます。
- https://protomaps.github.io/PMTiles/
