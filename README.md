# 職務経歴書

# 基本情報

| key | value|
|-----|------|
| 氏名 | 小島佑一 |
| GitHub | https://github.com/samuraikun |
| Qiita | https://qiita.com/samuraikun |

# スキル

## 言語

### 日本語

- ネイティブレベル

### 英語

- 日常会話レベル
- 英語の公式ドキュメントが読める程度

## アプリケーション開発

- Ruby
- Ruby on Rails
- JavaScript
  - jQuery
  - React
  - Vue
- DB
  - MySQL
  - PostgreSQL
  - MongoDB
  - Redis

## インフラ

### AWS

| 使用・構築経験 |
|--------------|
| EC2          |
| S3           |
| RDS          |
| API Gateway  |
| SWF          |
| Redshift     |
| CloudSearch  |
| Lambda       |

# 職務経歴

## 2019/01/07 - 現在 Crevo株式会社

- Rails によるサーバーサイド開発
- Vue.js, Vuexによるフロントエンド開発
- BEM, Grid Layout を活用したメンテナブルなCSSの設計と実装
- Atomic Design に基づいたコンポーネント設計及び実装
- Storybook によるコンポーネントの共通管理

## 2019/02/01 - 2019/04/03 ジラフ株式会社
- 土日週２のみのリモートによる開発
- React, TypeScriptによるフロントエンド開発


## 2016/04/01 - 2018/08/31 Sansan 株式会社

- https://jp.corp-sansan.com/
- Web アプリケーションエンジニアとして勤務

## 主な業務内容

- 名刺データ化サービスの開発・運用

### 開発を行ったシステムの特徴
- 名刺のデータ化をいくつかの工程に分け、１つの工程毎にマイクロサービスとして分離し、API連携を行う
- 実際の名刺画像から、各項目(氏名、会社名、住所など)をオペレーターによる人力の入力、OCRを利用した画像認識・機械学習による自動入力を利用した名刺に特化した入力システム
- 多様な言語の名刺に対応した入力システム
  - 日本語、英語、中国語、韓国語、フランス語、ドイツ語、スペイン語、ポルトガル語、タイ語、etc
- 多様な名刺のパターンを想定したノーマライズ処理(正規化処理)
- 名刺にあるいくつかの情報を利用した名寄せロジックの実装

### 開発システムの構成

- Ruby on Rails
- AWS
  - SWF (Amazon Simple Workflow)
  - RDS
    - Amazon Aurora
  - CloudSearch
  - Redshift
- マイクロサービスアーキテクチャ

## 担当業務
- 要件定義
- 仕様設計
- サーバーサイド(API)の設計・開発
- フロントエンドの画面設計・開発
- 施策の案出し及び調査のためのデータ抽出
- 検証ケースの考案・Qiita Teamによるドキュメント作成と検証の実行
- テスト
  - RSpec
  - Feature Test
- デプロイ・リリース
- 開発環境の改善
  - NewRelicの導入
  - Jenkins から CircleCI の導入・移行
  - Rubyのバージョンアップ移行(2.3.1 -> 2.5.1)
- エラー調査・改善
  - 発見したログを元に原因究明し、実装の修正

## Sansan株式会社での開発フロー

- 1週間毎にイテレーションを回すアジャイル開発体制
  - ストーリー(チケット)の見積もり
  - 実装
  - テスト
  - GitHubプルリクエストによるReview, Approve

# 業務外での活動

- 個人的に興味のあるフロントエンド分野の技術を調査・試行しています
- Web技術関係のイベントに参加し、自身の経験や知識に関して、アウトプットしています

### Vue.js

- Vue.js & Electorn で構成されたTODOアプリを開発しながらVue.jsについての記事を書きました
  - https://qiita.com/samuraikun/items/bb2939296bbead341293

### React.js

- フルスタック(MongoDB, Express, React, Node.js)な JavaScript アプリケーションを学習用に作成
  - https://github.com/samuraikun/node_with_react_app

### 技術書典

- 「Firebase によるサーバーレスシングルページアプリケーション」という書籍(同人誌)を執筆しました
  - https://techbookfest.org/event/tbf05/circle/47080001

# 前職及び現職で得た経験・スキル
- Ruby on RailsによるMVCアプリケーション開発経験
- RailsによるFat Model, Fat Controllerを回避するための開発経験
- RSpecを使用したテスト駆動開発
- Sidekiqを使用した非同期バックグラウンド処理の実装
- AWSにあるいくつかのサービスの使用経験
- プロダクトで使用するRubyのバージョンアップ実施
- BIツール(Redash)を使用したデータ集計
- 各種ツールの導入
  - CircleCI
  - NewRelic

# 業務以外で得た経験・スキル
- JavaScript(ES6)
- React, Redux
- Vue.js
- Node.js, Express
- Google App Engineを使用したSPAアプリケーションのプロトタイプ作成
- モブプログラミングによる React によるアプリケーション開発のハンズオン形式の勉強会のメンター
- Vue.jsとElectronを使用したTODOアプリケーションの開発
- Firebase を使用したサーバーレスなSPAの開発

# この先やっていきたいこと

## モダンなアーキテクチャを採用したフロントエンド開発

- 特に興味関心がある技術・概念
  - React.js, Vue.js 
  - TypeScript

## UI・UXが強みとなるプロダクトのサービス向上・改善

- ユーザーにストレスを与えないUIの実現
  - 高速な表示
  - 意図が明確な画面構成
  - 遅延のない操作

## メンテナブルかつスケールするバックエンドシステムの構築
- 変更に強いデータモデリング
- サーバーレスコンピューティングを用いた高スケーラビリティ・低コストなバックエンド処理
- 未然の事故を防ぐあるいは、被害を最小限に留めるのを可能とする監視システムの構築
