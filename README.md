# Japanese Sweets Shop LP（和菓子店 LP） [2周目]

CODEJUMP 初級編「和菓子店」課題の2周目の制作リポジトリです。

## 概要

和菓子店のWebサイト（1ページLP）のコーディングを行っています。Google Fonts（Noto Serif JP）を用いた縦書きレイアウトの実装、PC/SPでのヘッダー背景画像切り替え、スマホ時の要素非表示や表示件数の切り替え（お知らせ件数制御など）を実装します。

## コーディング仕様

- **使用フォント**: 
  - Google Fonts「`Noto Serif JP`」
- **コンテンツ幅**: 
  - ヘッダー / フッター / Google Map: 全幅（100%）
  - その他セクション: 1024px
- **ヘッダー**: 
  - PC / SPで背景画像を切り替え
  - 背景画像上にロゴ、メニュー、オンラインストアボタンを配置
- **お知らせ**: 
  - 表示件数を制御（PC: 5件 / SP: 3件）
- **商品のご紹介**: 
  - スマホ表示時のみタイトルの英語部分を非表示
  - テキストボックスは透過指定で画像上に重ね配置
- **レスポンシブ**: 
  - ブレークポイント: 768px
- **ブラウザ対応**: 
  - 縦書きレイアウト（`writing-mode: vertical-rl` 等）の崩れを防ぐ実装

## 使用技術

- HTML5
- SCSS / CSS3
- BEM (CSS設計)
- Live Sass Compiler
- Git / GitHub

## Demo

https://satoru-tanaka-1977.github.io/cj-beginner-store3-v2/

## 制作状況

制作中（2026.10.29〜）