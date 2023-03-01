# 職務経歴書

## 氏名

| key    | value                        |
| ------ | ---------------------------- |
| Name   | 戸田 康隆 (Yasutaka Toda)    |
| GitHub | https://github.com/ystktoda/ |

## 職務経歴（概要）

### ソフトウェア開発

- Web アプリケーション開発
  - PHP、Java、Ruby, JavaScript あわせて 15 年以上
  - 10 年以上、アーキテクトとして、新規システム構築やシステム更改のアーキテクチャ設計・構築

### 発注者支援

- プロジェクトマネジメント支援
  - 暗礁に乗り上げた基幹システム更改の立て直し計画立案、進捗管理、リリースまで支援
- エンジニアの教育・育成
  - 若手エンジニアの研修プログラム作成と実施

### 社内業務改善

- 開発標準の更新
  - 最新のフレームワークへ乗り換え、CI 導入、テストコード作成推進、ローカル開発環境の Docker 化、など
- 社内システムの改善

## スキル

### バックエンド

- PHP
  - Laravel
    - アーキテクトとして新規構築から担当
    - バージョン 5.5 から 10 まで段階的に upgrade
    - PHPUnit による Feature と Unit テストを実装
- Python
  - AWS Lambda におけるバッチ処理作成
  - AWS API Gateway + AWS Lambda にて、REST API の endpoint 作成
  - scikit-learn
    - 機械学習（教師あり学習）
    - データ取得、特徴量作成、モデル作成、予想結果出力を自動で行うシステムを独自に構築
  - スクレイピングして Slack 通知アプリ作成
- Ruby
  - Ruby on Rails
    - バージョン 5.2
    - RSpec によるテスト実装
- Java
  - SpringBoot
  - Java EE
    - バージョン 6 と 7。特に 6 では、古い独自フレームワークから JavaEE6 への移行を担当した
  - Seaser2

### フロントエンド

- Vue.js
  - Vue.js + Laravel の SPA の設計・開発
- React
  - Next.js + React (TypeScript) を用いて SSR にて管理画面の設計・開発
- Backbone.js
  - Backbone.js(Marionette.js) + CakePHP の SPA の開発

### その他

- Docker
  - Laravel や Ruby on Rails のローカル開発環境を Docker に移行
  - 本番環境用 Docker コンテナ作成
- AWS
  - EC2, RDS, ALB, Route 53 を用いて、Multi-AZ 構成で Web システムを配置
  - Amazon ECS を用いて、Docker コンテナ化された Laravel の Web アプリをサーバーレスで配置
  - AWS API Gateway + AWS Lambda にて、REST API の endpoint 作成
  - AWS CloudFormation や AWS SAM CLI を使用したインフラ構築やデプロイ
- UML
  - エンドユーザーの要求分析、要件定義、またシステムのアーキテクチャ設計に UML を活用

### IT以外の保有資格

- 税理士試験科目合格（簿記論、財務諸表論、消費税法）
- 宅地建物取引士
- MBA経営管理修士（専門職）の取得を目指して、事業創造大学院に在籍中

## 強み

- フロントエンド、バックエンド、インフラ（クラウド）のすべての分野にて設計、開発、テスト、リリースまで担当できる。
- 人前での話や会議のファシリテーションが得意。
- プログラミングに限らず、恒常的に知識をアップデートしている。
- 不動産賃貸業の法人を5年以上経営しており、実践に基づいた経営についての知識を保有している。

## やったことはないが興味があるもの

- 脳と IT の連携（ニューロフィードバックなど）
- 農業と IT の連携

## 職務経歴(詳細)

### 2022/11 - 現在: 株式会社アイデアログ

職務: IT アーキテクト

週 2 日勤務

#### 自社サービスのアーキテクチャ刷新

自社サービスのアーキテクチャ刷新プロジェクトを担当

- Frontend は Next.js + React (TypeScript) にて SSR や SSG を実現する
- Backend は Laravel
- AWS のサーバレスサービスにデプロイ

### 2020/04 - 2022/06: 株式会社 Everforth

職務: IT アーキテクト

週 2 日勤務

#### 自社サービス開発

EC サイトのバックエンドを担当

- AWS Lambda におけるバッチ処理作成 (Python, Scala)
- AWS API Gateway + AWS Lambda にて、REST API の endpoint 作成
- Scala にて、Web アプリケーションのバックエンド開発

### 2017/10 - 2020/09: 株式会社アクシア

職務: Web アプリケーションエンジニア、IT アーキテクト、業務改善

2020/04 - 2020/09 の期間は週 3 日で勤務

#### 自社サービス開発

プロダクトのリーダーとて、BtoB の自社サービスを設計、開発、運用している。

- Vue.js + Laravel の SPA にて構築
- Amazon ECS を用いて、Docker コンテナ化された Laravel の Web アプリをサーバーレスで配置
- AWS CLI にて、本番環境リリースの簡略化

#### 業務改善

社内の業務の品質や効率を上げるための活動を継続的に行っている。

- 開発標準の更新
  - 最新のフレームワークへ乗り換え、CI 導入、テストコード作成推進、ローカル開発環境の Docker 化、など
- 自社システムをアジャイル開発にて改善
- コミュニケーションツールとして slack を導入
- 社内の知識共有のため、[Growi](https://docs.growi.org/ja/)を用いた社内 wiki を構築
- 睡眠不足による生産性の低下を可視化する Web サイト構築 : [生産性睡眠グラフ](https://sleep.axia.co.jp/) (https://sleep.axia.co.jp/)
  - 参考: [睡眠時間を削ると人間はバカになる](https://axia.co.jp/2018-07-30) (https://axia.co.jp/2018-07-30)

#### 受託開発

PHP, Java, Ruby にて、様々なお客様の Web アプリケーションの受託開発を行っている。

- インフラを含めたシステム基盤から構築
- 新規システムの構築や、他社が開発したシステムを引き継いで改修もある
- お客様との打ち合わせもリモートで参加
- 常に複数のお客様の開発を並行して実施

### 2015/10 - 2017/10: ピースミール・テクノロジー株式会社

職務: IT アーキテクト（発注者支援として活動）

#### 農業/営農支援システム開発

生産性や経営の分析を行う帳票フレームワークの基盤と各種帳票の開発。また、顧客の若手のエンジニア教育。

- 帳票フレームワーク(JavaEE7)の基盤の設計・開発
- 若手エンジニアの研修プログラム作成と実施

#### 製造業/業務基幹システムの再構築

使い勝手が悪く、半分以上機能が使用されていない業務基幹システムを、限られた期間と予算の中で、最低限使えるように改善する。

- 顧客のシステム課の支援として、要件定義（AsIs と ToBe の定義）
- 基本設計、進捗管理、総合テスト支援

### 2009/04 - 2015/09: 株式会社北海道 CSK

職務: Web アプリケーションエンジニア、IT アーキテクト

#### 流通小売業/基幹システムの再構築

基幹システムの再構築プロジェクト。フレームワーク刷新や各種 HW,MW のバージョンアップ、入替など

- アーキテクトチームリーダー
- 独自 Java フレームワークから、JavaEE6 (WebSphere) への移行。設計から実装・リリースまで担当
- SOA (WebSphere) を用いて、サービス間を連携。

#### アパレル/EC サイト新規構築

アパレルの EC サイトパッケージのアドオン開発。デザイナーが作成したデザインを用いた UI 開発や、クレジットカード決済用の Restful WebService の開発。

- プロジェクトリーダー
- Java / Oracle DB
- クレジットカード決済用の Restful WebService のアーキテクチャ設計・開発

### 2007/04 - 2009/03: 株式会社日本総合研究所

職務: Web アプリケーションエンジニア

#### クレジットカード Web サイト保守開発

- 設計・開発・テスト担当
- Java / Oracle DB

## 課外活動

### 機械学習を用いた競馬予想アプリ開発

機械学習(scikit-learn)を用いて、JRA の馬券買い目を予想するアプリケーションを独自に開発。

- 参考
  - https://github.com/ystktoda/prediction-jra-horseracing
  - https://www.facebook.com/yasutaka.toda.5/posts/1453449221408381

### Raspberry Pi とセンサーを用いた簡易アプリ開発

オフィスの動きを可視化するアプリケーションや、簡易入退室管理アプリを開発

- 参考
  - https://www.facebook.com/yasutaka.toda.5/posts/1587149391371696
  - https://www.facebook.com/yasutaka.toda.5/posts/1412595612160409
