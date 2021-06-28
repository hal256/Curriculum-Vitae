# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|田村悠|
|Qiita|[@hal_256](https://qiita.com/hal_256)|

## プログラムについてのスキル
### 言語
- PHP
- JavaScript
- TypeScript
- Go
- Python
- Liquid

### フレームワーク

- Laravel
- React.js
- Next.js
- Vue.js
- Nuxt.js
- WordPress

## インフラについてのスキル

### 構築経験がある主要なAWSリソース
- Route53
- EC2
- ELB
- RDS
- CloudFront
- DynamoDB
- ElasticCache
- ECR
- ECS(Fargate)
- APIGateWay
- AppRunner
- Redshift
- S3
- Lambda
- CloudWatch
- AWS Glue
- CodeCommmit
- CodePipeline
- CodeBUild
- CodeDeploy


### その他の使用経験
- Heroku
- Vercel
- terraform



## 強み
要件定義、設計、開発、インフラ構築、保守運用まで一人で対応できます。
必要ならデザイナー、他の作業者もこちらで探してシステムを完成させることができます。


### 要件定義、設計について
ヒアリングの上ドメイン駆動設計に基づきユースケース図、ドメイン制約について記述した資料を作成しています。

### 開発について
技術選定から対応しています。
以前はRestAPIを使用していましたが、スケールしやすさとSchemaからTypeScriptの型を作成できるのが便利で最近はGraphQLを使用すること多いです。

### インフラ構築について
terraformとAWSを使用して要件にあったシステムを構築できます。

### 保守運用について
Sentryによるアプリケーション層でのエラー監視、CloudWatchによる負荷、50xレスポンスの監視を行いSlackや、メール通知で対応しています。


## 経歴


### 定期購入システムの構築

BASEFOODのストアと連携する定期購入システムの構築を行いました。

柔軟な配達日指定機能や複雑な条件指定ができるクーポン機能等をテスト駆動で組み込みし、複雑な仕様に安全に対応できるようにしています。

インフラについてはterraformを使用し、IaCを実現しました。これにより本番環境の安全な管理だけでなく、複数のテスト環境を容易に管理できるになりました。

このプロジェクトではDockerを使用し、デプロイ環境、ローカル開発環境での差異が少ない環境を構築するだけではなく、ローカルでのCIテスト実行を実行できるようになり、CI実行後の最終成果物の確認も容易にしました。

機能が複雑になり、発生したエラーの検証を簡単にするためにSentryによるアプリケーションエラー監視を導入しました。Sentryの導入によりエラー追跡、ユーザーへのフォローがやりやすくなりました。

BASEFOODではテレビ露出や、ネットメディアへの掲載など急激にアクセスが増えることがあるので、サーバー過負荷や多すぎる50xレスポンスをCloudwatchを使用し通知するシステムを構築しました。
これにより、問題をいち早く検知したり、ECSのスケールアウトで対応できるようになりました。

#### 使用した主な技術、言語
- PHP
- JavaScript
- Laravel
- Docker
- CodePipeline
- RDS
- ECS
- Sentry
- terraform

#### 担当範囲
- 要件定義
- 設計
- 組み込み
- インフラ構築
- 保守運用


----
### Shopifyストアの構築
[黒船亭](https://www.kurofunetei.co.jp/)のShopifyストアを構築しました。
Shopifyアプリを使用し、定期購入を実現しました。

#### 使用した主な技術、言語
- Github Action
- Liquid

#### 担当範囲

- Shopifyのテックリード
- マークアップからShopifyテーマ組み込み
- アプリ選定、設定

----

### Shopifyストアの構築

[BASEFOOD](https://shop.basefood.co.jp/)のShopifyストアを構築しました。

定期購入連携等の複雑な機能が多くShopifyのテーマでは珍しくVue.jsを使用しています。

#### 使用した主な技術、言語
- CodePipeline
- CodeBuild
- Liquid
- Vue.js

#### 担当範囲
- Shopifyのテックリード
- マークアップからShopifyテーマ組み込み



---
### WordPressブログの作成
[BASEFOOD Magazine](https://basefood.co.jp/magazine/)のWordpressブログを構築しました。

WordPressでは一般的なEC2+S3+RDSを使用して構築を行いました。
また、テーマの一部改修も担当しました。

#### 使用した主な技術、言語
- terraform
- S3
- RDS
- EC2


#### 担当範囲
- 要件定義
- WordPressテーマの改修
- インフラ構築
----

### Webサイトインフラ構築

[BASEFOOD](https://basefood.co.jp)のインフラを構築しました。
こちらは他のページと違い静的なhtmlを返すので、ドメイン直下をCloudFrontにし、高速なレスポンスを実現しました。


#### 使用した主な技術、言語
- terraform
- CloudFront
- EC2


#### 担当範囲
- インフラ構築

----
### BI分析基盤の作成

BASEFOODにて社内で使用するRedshift+Metabaseを使用したBI分析基盤を作成しました。

#### 使用した主な技術、言語
- terraform
- Metabase
- Redshift
- lambda
- CloudWatch Event
#### 担当範囲
- インフラ構築


----
### 予約システムの構築

塾トビラ(閉鎖済み)の開発を担当しました。

Vue.jsを使ったインタラクティブなUXを実現しました。
多くのアクセスが想定されるWEBサイトではなかったので、EC2を使用しインフラコストの少ないシステムを構築しました。

#### 使用した主な技術、言語
- Vue.js
- Laravel
- EC2
- RDS

#### 担当範囲
- 要件定義
- 設計
- 組み込み
- インフラ構築
- 保守運用


### 執筆歴
* [Next.js+GrapqhQLでShopifyアプリを開発する](https://qiita.com/hal_256/items/07626bb0621bc6c8eef8)
