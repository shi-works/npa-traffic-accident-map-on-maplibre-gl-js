# 交通事故マップ on MapLibre GL JS
## Public Website
- https://shi-works.github.io/traffic-accident-map/
## サンプル画像

# traffic-accident-pmtiles
## データについて
- 本データは、警察庁が公開している、[交通事故統計情報のオープンデータ](https://www.npa.go.jp/publications/statistics/koutsuu/opendata/index_opendata.html)を[tippecanoe](https://github.com/felt/tippecanoe)で[PMTiles形式](https://github.com/protomaps/PMTiles)に変換したデータになります。
- オープンソースソフトウェアで構築

## データ配布
### 町丁・字等別
- `https://pmtiles-data.s3.ap-northeast-1.amazonaws.com/r2kokusei/r2ka01-47_JGD2011.pmtiles`(414.9MB)
- `https://pmtiles-data.s3.ap-northeast-1.amazonaws.com/r2kokusei/r2ka01-47_point_JGD2011.pmtiles`(71.5MB)

### 基本単位区
- `https://pmtiles-data.s3.ap-northeast-1.amazonaws.com/r2kokusei/r2kb01-47_JGD2011.pmtiles`(1.1GB)
- `https://pmtiles-data.s3.ap-northeast-1.amazonaws.com/r2kokusei/r2kb01-47_point_JGD2011.pmtiles`(347.5MB)

## ベクトルタイル設計情報
### ■ 町丁・字等別
#### 境界データ（r2ka01-47_JGD2011.pmtiles）
- 境界データそのものを可能な限り生かしたデータです。
- tippecanoeによるデータの間引きを行っていません。

#### 図形中⼼点（r2ka01-47_point_JGD2011.pmtiles）
- 町丁・字等名称や人口等のラベルを表示できるようにするためのポイントデータです。
- tippecanoeによるデータの間引きを行っていません。

### ズームレベル範囲
- 10-14

### 属性
- 境界データの属性はそのまま生かしています。
