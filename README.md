# 職務経歴書

## 氏名

|key|value|
|---|-----|
|Name|戸田 康隆 (Yasutaka Toda)|
|GitHub| https://github.com/ystktoda/ |

## 職務経歴（概要）

### ソフトウェア開発

- Webアプリケーション開発
  - PHP、Java、Ruby あわせて10年以上
  - 6年以上、アーキテクトとして、新規システム構築やシステム更改のアーキテクチャ設計・構築

### 発注者支援

- プロジェクトマネジメント支援
  - 暗礁に乗り上げた基幹システム更改の立て直し計画立案、進捗管理、リリースまで支援
- エンジニアの教育・育成
  - 若手エンジニアの研修プログラム作成と実施

### 社内業務改善

- 開発標準の更新
  - 最新のフレームワークへ乗り換え、CI導入、テストコード作成推進、ローカル開発環境のDocker化、など
- 社内システムの改善

## スキル

### バックエンド

- PHP
  - Laravel
    - アーキテクトとして新規構築から担当
    - バージョン5.5 から 6.0 まで段階的にupgrade
    - PHPUnitによるFeatureとUnitテストを実装
- Python
  - scikit-learn
    - 機械学習（教師あり学習）
    - データ取得、特徴量作成、モデル作成、予想結果出力を自動で行うシステムを独自に構築
  - スクレイピングしてSlack通知アプリ作成
- Java
  - SpringBoot
  - Java EE
    - バージョン6と7。特に6では、古い独自フレームワークからJavaEE6への移行を担当した
  - Seaser2
- Ruby
  - Ruby on Rails
    - バージョン5.2
    - RSpecによるテスト実装

### フロントエンド

- Vue.js
  - Vue.js + Laravel のSPAの設計・開発
- Backbone.js
  - Backbone.js(Marionette.js) + CakePHP のSPAの開発

### その他

- Docker
  - LaravelやRuby on Rails のローカル開発環境をDockerに移行
  - 本番環境用Dockerコンテナ作成
- AWS
  - EC2, RDS, ALB, Route 53 を用いて、Multi-AZ構成でWebシステムを配置
  - Amazon ECS を用いて、Dockerコンテナ化されたLaravelのWebアプリをサーバーレスで配置
- UML
  - エンドユーザーの要求分析、要件定義、またシステムのアーキテクチャ設計にUMLを活用

## 強み

- フロントエンド、バックエンド、インフラ（クラウド）のすべての分野にて設計、開発、テスト、リリースまで担当できる。
- 人前での話や会議のファシリテーションが得意。
- プログラミングに限らず、恒常的に知識をアップデートしている。

## やったことはないが興味があるもの

- 脳とITの連携（ニューロフィードバックなど）
- 農業とITの連携

## 職務経歴(詳細)

### 2017/10 - 現在 : 株式会社アクシア

職務: Webアプリケーションエンジニア、ITアーキテクト、業務改善

#### 自社サービス開発

プロダクトのリーダーとて、BtoBの自社サービスを設計、開発、運用している。

- Vue.js + Laravel のSPAにて構築
- Amazon ECS を用いて、Dockerコンテナ化されたLaravelのWebアプリをサーバーレスで配置
- AWS CLI にて、本番環境リリースの簡略化

#### 業務改善

社内の業務の品質や効率を上げるための活動を継続的に行っている。

- 開発標準の更新
  - 最新のフレームワークへ乗り換え、CI導入、テストコード作成推進、ローカル開発環境のDocker化、など
- 自社システムをアジャイル開発にて改善
- コミュニケーションツールとしてslackを導入
- 社内の知識共有のため、[Growi](https://docs.growi.org/ja/)を用いた社内wikiを構築
- 睡眠不足による生産性の低下を可視化するWebサイト構築 : [生産性睡眠グラフ](https://sleep.axia.co.jp/) (https://sleep.axia.co.jp/)
  - 参考: [睡眠時間を削ると人間はバカになる](https://axia.co.jp/2018-07-30) (https://axia.co.jp/2018-07-30)

#### 受託開発

PHP, Java, Rubyにて、様々なお客様のWebアプリケーションの受託開発を行っている。

- インフラを含めたシステム基盤から構築
- 新規システムの構築や、他社が開発したシステムを引き継いで改修もある
- お客様との打ち合わせもリモートで参加
- 常に複数のお客様の開発を並行して実施

### 2015/10 - 2017/10: ピースミール・テクノロジー株式会社

職務: ITアーキテクト（発注者支援として活動）

#### 農業/営農支援システム開発

生産性や経営の分析を行う帳票フレームワークの基盤と各種帳票の開発。また、顧客の若手のエンジニア教育。

- 帳票フレームワーク(JavaEE7)の基盤の設計・開発
- 若手エンジニアの研修プログラム作成と実施

#### 製造業/業務基幹システムの再構築

使い勝手が悪く、半分以上機能が使用されていない業務基幹システムを、限られた期間と予算の中で、最低限使えるように改善する。

- 顧客のシステム課の支援として、要件定義（AsIsとToBeの定義）
- 基本設計、進捗管理、総合テスト支援

### 2009/04 - 2015/09: 株式会社北海道CSK

職務: Webアプリケーションエンジニア、ITアーキテクト

#### 流通小売業/基幹システムの再構築

基幹システムの再構築プロジェクト。フレームワーク刷新や各種HW,MWのバージョンアップ、入替など

- アーキテクトチームリーダー
- 独自Javaフレームワークから、JavaEE6 (WebSphere) への移行。設計から実装・リリースまで担当
- SOA (WebSphere) を用いて、サービス間を連携。

#### アパレル/ECサイト新規構築

アパレルのECサイトパッケージのアドオン開発。デザイナーが作成したデザインを用いたUI開発や、クレジットカード決済用のRestful WebServiceの開発。

- プロジェクトリーダー
- Java / Oracle DB
- クレジットカード決済用のRestful WebServiceのアーキテクチャ設計・開発

### 2007/04 - 2009/03: 株式会社日本総合研究所

職務: Webアプリケーションエンジニア

#### クレジットカードWebサイト保守開発

- 設計・開発・テスト担当
- Java / Oracle DB

## 課外活動

### 機械学習を用いた競馬予想アプリ開発

機械学習(scikit-learn)を用いて、JRAの馬券買い目を予想するアプリケーションを独自に開発。

- 参考
  - https://github.com/ystktoda/prediction-jra-horseracing
  - https://www.facebook.com/yasutaka.toda.5/posts/1453449221408381

### Raspberry Pi とセンサーを用いた簡易アプリ開発

オフィスの動きを可視化するアプリケーションや、簡易入退室管理アプリを開発

- 参考
  - https://www.facebook.com/yasutaka.toda.5/posts/1587149391371696
  - https://www.facebook.com/yasutaka.toda.5/posts/1412595612160409