# Gallery Site Portfolio

ポートフォリオサイト「Gallery Site Portfolio」のソースコードです。  
こちらは提出用に作成したものです。
Vue.jsを使用して、画像の切り替えやフィルタリング、クリックした画像の拡大表示などのインタラクションを実現しています。

## 概要

このポートフォリオサイトは、ギャラリー展示をテーマにして制作しました。  
ユーザーが画像を快適に閲覧できるよう、レスポンシブデザインやアニメーションなどを活用しています。

## 主な特徴・機能

- **画像スライドショー**  
  トップページにおいて、vegasライブラリを使用して画像のスライドショーを実現しています。
  画像は時間経過により自動的に切り替わります。

- **画像フィルタリング**  
  画像をカテゴリーごとにフィルタリングする機能があり、
  ユーザーが「Flower」「Sky」「Forest」などのカテゴリーを選択することで、該当する画像のみが表示されます。

- **画像の拡大表示**  
  画像をクリックすると、lightbox2を使用してその画像が画面いっぱいに表示され、
  さらに矢印を押すことで次の画像へ簡単に移動できます。

- **レスポンシブデザイン**  
  デスクトップおよびモバイル環境で快適に閲覧可能です。

- **ギャラリー表示**  
  Masonryレイアウトを使用し、画像の魅力を最大限に引き出すギャラリーを作成しています。  
  `vue-masonry-css` と `masonry-layout` を活用しています。

## 使用技術

### 言語とフレームワーク

- **HTML / CSS / JavaScript**
- **Vue.js**（フレームワーク）
- **Vite**（ビルドツール）

### ライブラリとツール

- **Vue.js**（フレームワーク）
- **Masonry Layout**（ギャラリー表示）
- **vue-masonry-css**（Masonryレイアウト）
- **Vegas**（背景アニメーション）
- **Normalize.css**（CSSリセット）
- **Lightbox2**（画像ライトボックス）
- **gh-pages**（GitHub Pagesデプロイ）
- **Sass**（CSSプリプロセッサ）
- **Stylelint**（CSSコード品質管理）