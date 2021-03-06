# cv

## 基本情報

| key | value |
|-|-|
| 名前 | 比嘉 海斗 |
| 生息地 | 東京都 品川区 |
| 生年月日 | 1992年10月26日 |
| 動作環境 | MacBook Air Processor 1.2GHz Quad-Core Intel Core i7 Memory 16GB |
| Mail | kaito.higa.free@gmail.com |
| GitHub | [highsai-eng](https://github.com/highsai-eng) |
| Twitter | [@highsai_eng](https://twitter.com/highsai_eng) |
| FaceBook | [kaito.higa.3](https://www.facebook.com/kaito.higa.3) |

## 職歴
| started_at | ended_at | workplace | occupation | remarks |
|-|-|-|-|-|
| 2015-04 | 2017-03 | 株式会社インテリジェンスビジネスソリューションズ（現：パーソルプロセス＆テクノロジー株式会社） | エンジニア | 新卒入社 |
| 2017-04 | 2019-02 | フューチャーアーキテクト株式会社 | コンサルタント | 中途入社 |
| 2019-03 | null | フリーランスエンジニア | エンジニア | null |

## 資格
| date | name |
|-|-|
| 2011-08 | ITパスポート試験 |
| 2011-11 | 基本情報技術者試験 |
| 2012-06 | データベーススペシャリスト試験 |
| 2012-12 | 情報セキュリティスペシャリスト試験 |
| 2013-12 | ネットワークスペシャリスト試験 |
| 2014-06 | 応用情報技術者試験 |
| 2016-01 | Java Programmer Silver SE8 |

## 概要

- 主にWebアプリケーションのフロントエンドとバックエンドの設計及び開発を専門としています。
- フロントエンド開発においては、主にJavaScript、フレームワークとしてはVue.js、Nuxt.jsを用いた豊富な開発経験があります。アトミックデザインや、Unitテスト、SSRの導入も経験しています。
- バックエンド開発においては、主にJava、Go、PHP、フレームワークとしてはSpring、Gin、Laravelを用いた豊富な開発経験があります。また、データベース設計（論理、物理）の知見を活かしたデータモデリング、クリーンアーキテクチャ、ドメイン駆動設計を用いたアプリケーション設計を得意とし、変更に強いバックエンドアプリケーションを実装できることが強みです。サーバーレスアーキテクチャでの実装も経験しております（主にAWS Lambda, sam）。
- 小規模〜中規模サービスの新規開発、追加機能開発、リプレイスなどの案件で最もバリューを発揮できます。
- ごくたまに、コーポレートサイト等の静的Webページ作成、Wordpress構築、SEO対策も仕事として請け負っています。お仕事に関するお問い合わせはTwitterのDMなどからお気軽にどうぞ。

## スキル

- 実務で使用した技術のみ列挙しています。

### 言語

Java | Kotlin | Go | PHP | Python | JavaScript | TypeScript | HTML | CSS | SQL | Bash

### フレームワーク等

Struts | Seaser | Doma | Spring Framework | Gin | GORM | Larave | Flask | jQuery | Anguler | Vue.js | Nuxt.js

### DB/NoSQL

Oracle | MySQL | PostgreSQL | Redis | Memcached | MongoDB | Elasticsearch

### クラウド

#### AWS

VPC | Cloud Front | ELB | ALB | Route53 | IAM | Cloud Watch | EC2 | ECS(Fargate) | API Gateway | Lambda | S3 | ElastiCache(Redis) | RDS(MySQL|PostgreSQL) | Aurora | Redshift | Elasticsearch Service | SQS | SES | Code Pipeline | Amplify | Translate

### SaaS/PaaS/BaaS

GitHub | GitLab | Bitbacket | CircleCI | DataDog | Sentry | FullStory | Firebase

### その他

Terraform | Ansible | Docker | Apache httpd | Apache Tomcat | Apache MINA | Apache FtpServer | Apache SSHD | Oracle WebLogic Server | nginx | Grunt | Webpack | SASS | Kibana | LDAP | Active Directory | Jenkins | Zabbix | WebSphere MQ | HULFT | TestCafe

## バリューを発揮しやすい業務

- 全文検索サービスの導入
- サーバーレスアーキテクチャの導入
- クリーンアーキテクチャの導入
- アトミックデザインの導入
- Jestを使用したフロントエンドUnitテストの導入
- パッケージマネージャの導入
- 環境のコンテナ化（Docker化）
- クラウドアーキテクチャ設計（AWS）
- インターフェース設計（REST API、ファイル連携、etc.）
- データモデリング（概念、論理、物理）
- Angular、Vue.jsを使用したフロントエンド開発
- Spring、Gin、Laravel使用したバックエンド開発
- 逐次処理、並列処理のバッチ開発
- Javaを使用したFTP、SSHDサーバ及びクライアントの開発（需要ある？）
- 大規模システムリプレイスのコンサルティング業務

## 業務経歴

### テレビ視聴率分析サービスの開発（2019年）

【プロジェクト概要】テレビ視聴率を分析するSaaSサービスの開発及びバッチ処理の開発。

【担当業務】主にフロントエンドとバックエンドの設計、開発を担当。
使用言語はJavaScript、TypeScript、Go、PHP、Python。フレームワークはVue.js（SSR）、Laravel。
サーバー環境はAWS（ECS/Aurora/Redshift/Redis/API Gateway/Lambda）。
シミュレーション処理の非同期化のため、一部サーバーレスアプリケーションを導入。
既存バッチ処理の性能劣化が懸念されていたため、goroutineを使用した並列処理のアーキテクチャを導入。

- 追加機能全体のシステム処理方式の設計
- アトミックデザイン及びテスティングフレームワーク導入に関する調査
- UIコンポーネントのアトミックデザイン化
- コンポーネントのUnitテスト実装
- 非同期に関するクラウドアーキテクチャ設計
- Redisサーバのスペック見積もりとキャッシュ方式設計
- 総合テスト仕様書の作成

【主な成果】全体のシステム処理方式や、アトミックデザインとテスティングフレームワークを両立する実装ルールの策定など、開発の起動を乗せるとともに実装担当者としてチームに貢献。
またコンサルティング業務の経験からリリース後の品質面を担保するための結合及び総合テスト仕様書を作成。期間内に無事リリースを達成、社内表彰制度のMVPを取得。

### 高単価フリーランス人材と企業のマッチングサービス開発（2019年）

処理中。。。

### 物流システム顧客連携基盤（EDI）のDR環境構築及びセキュリティ通信機能の開発（2019年〜2019年）

処理中。。。

### 物流システムモバイル端末連携基盤用インターフェースシステム（EAI）の構築（2017年〜2018年）

処理中。。。

### 人事評価管理サービスの企画及びPOC（2017年）

処理中。。。

### インバウンドビジネスサービスのモバイルバックエンド構築及びモバイルアプリの開発（2016年）

処理中。。。

### YouTuber向けマッチング及び分析プラットフォームの構築（2015年〜2016年）

処理中。。。
