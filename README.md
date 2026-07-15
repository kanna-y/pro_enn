# かげさんぽ

## アプリ概要

かげさんぽは、暑い日でも安全で快適に散歩ができるようにサポートするアプリです。

地図上に日陰、自動販売機、休憩スポットなどを表示し、利用者が熱中症のリスクを避けながら涼しく散歩できることを目的としています。

---

## 主な機能

- 地図上へのスポット表示
- スポットの検索機能
- カテゴリごとの絞り込み
- スポット詳細情報の表示
  - 名称
  - 営業時間
  - 定休日
  - 備考
- 現在地の表示
- 気温情報の表示

---

## 実行方法（使い方）

### ローカルで実行する場合

1. リポジトリをダウンロードまたはクローンします。

```bash
git clone https://github.com/ユーザー名/pro_enn.git
```

2. `index.html` をブラウザで開きます。

または、VS Code の Live Server を利用して実行してください。

### GitHub Pages

公開ページ

```
https://kanna-y.github.io/pro_enn/
```

---

## 使用したデータ

### オープンデータ

- 自動販売機
- 休憩スポット
- 病院
- その他施設情報

### 独自データ

- 日陰スポット
- 日向（危険エリア）
- 現地調査によって収集した情報

データは GeoJSON 形式で管理しています。

---

## 使用技術

- HTML
- CSS
- JavaScript
- GeoJSON
- GitHub Pages

---

## 使用ライブラリ

- Leaflet
  - https://leafletjs.com/

---

## 外部API

- OpenStreetMap
- Open-Meteo API

---

## ライセンス

### 地図

- OpenStreetMap Contributors

### ライブラリ

- Leaflet

### 天気情報

- Open-Meteo API
