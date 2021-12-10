# 業務経歴書

## 基本情報
|key|value|
|---|---|
|GitHub|[kobayashi-m42](https://github.com/kobayashi-m42)|
|GitHub(友人と共同で運営しているOrganization)|[nekochans](https://github.com/nekochans)|
|Qiita|[@kobayashi-m42](https://qiita.com/kobayashi-m42)|
|Zenn|[@kobayashi-m42](https://zenn.dev/kobayashi_m42)|
|個人プロダクト|[Mindexer](https://www.mindexer.net)(Qiitaのストックを整理するためのサービスです)|
|個人プロダクト|[LGTMeow](https://lgtmeow.com)(猫のLGTM画像を共有出来るサービスです)|
|Twitter|[@kobayashi-m42](https://twitter.com/kobayashi_m42)|

## 概要
Web系エンジニアです。現在は、フリーランスとして活動。

AWSを利用したインフラ構築、監視基盤の構築、バックエンドをメインとしています。

## 強み
- AWSを得意とし、インフラ、監視の設計・構築・運用が出来ます。
- コードによるクラウドインフラ構成管理の自動化。コード化することで、インフラを安全かつ効率的に管理します。
- テストコードや設計手法を工夫した、保守性・拡張性の高いシステムを構築するすることが可能です。
- アジャイル開発によるプロジェクト管理経験があり、アジャイル開発を用いたチームビルディングが出来ます。

主に新規開発や、サービスのリプレイスフェーズにおいて最もバリューを発揮出来るタイプです。

## 得意じゃない事
- Webデザイン(CSSの利用は可能)

## スキルレベル
スキルの習熟度の目安は下記の通りです。
- A:概ね理解し、開発に必要なスキルを持っている
- B:部分的に理解し、調べながら開発することが可能
- C:経験はあるが理解が浅く、勉強中

### 言語
|言語|レベル|備考|
|---|---|---|
|Go|A|REAT APIの作成|
|Kotlin|B|Spring Bootを使用してREAT APIを作成|
|TypeScript|A|フロントエンド、サーバーサイド共に利用|
|JavaScript|A|フロントエンド、サーバーサイド共に利用|
|PHP|A|Laravelを使用してREAT APIを作成。現在は使用していません。|
|Scala|C|Gatlingの実装に利用|
|HTML|A||
|CSS|B|Bulma、Bootstrapのフレームワークについても利用経験あり|
|Apex|A|Salesforceの開発。現在は使用していません。|
|VB.NET|B|過去に開発経験あり。現在は使用していません。|

### フレームワーク
|フレームワーク|レベル|備考|
|---|---|---|
|Spring Boot|A|REAT APIの開発に利用|
|Laravel|A|REAT APIの開発に利用|
|Express|A||
|React|A|社内向けのアプリケーション開発に利用|
|Vue.js|A|Vue.js + Vuex + vue-router + TypeScriptでのSPA開発|
|Nuxt.js|B|Vue.jsのプロジェクトを移行|
|Next.js|B|個人開発のアプリケーションで利用|

### クラウド

#### AWS
|サービス名|レベル|備考|
|---|---|---|
|EC2|A|Webサーバとして利用|
|ECS|A|本番環境でFargateを利用。EC2モードは開発環境のみで利用|
|RDS|A|Aurora MySQL、Aurora PostgreSQLを利用|
|S3|A|画像サーバやCloudFrontと合わせてSPAの配信等、様々な場面で利用|
|CloudFront|A|CDNとして利用|
|Lambda|B|インフラ周りのタスクやNuxt.jsを動作させるために利用|
|API Gateway|B|AWS Lambdaと組み合わせて利用|
|Route53|A|DNSサーバとしていつも利用|
|IAM|A||
|ALB|A||
|StepFunctions|A|バッチ処理で利用|
|DataSync|A||
|WAF|A||
|GuardDuty|A||
|Cognito|A|UserPoolを用いて認証基盤を構築。社内向けで利用|
|OpenSearch|A|KibanaによるALBアクセスログの可視化、Alertを利用した監視設定に利用|
|Organizations|A||
|CloudFormation|B|基本的にはTerraformを利用しているが、一部で利用|	

VPCやCloudWatch等のAWSを利用すれば必ず利用するような物は含めておりません。

### インフラ関連
|サービス名|レベル|備考|
|---|---|---|
|Docker|A|開発環境での利用、AWS ECSでの利用共に経験あり|
|Terraform|A|AWSの構成管理で利用|
|Datadog|A|監視基盤を構築|
|PagerDuty|B|導入したてで、まだ経験が浅いです|

### その他
|key|value|
|---|---|
|Salesforce|社内システムのでの利用。要件定義から開発・運用保守までを担当。|

## 目指しているエンジニア像
小・中規模のサービスをアーキテクチャから選定し高品質で運用コストが低いシステムを開発していきたいです。

その為にもフロント、バックエンド、インフラの各分野で利用出来る技術の幅を増やしていきたいと思っています。

## 主な業務経歴

### 社内向けアプリケーションの新規開発
- 利用した技術
  - Spring Boot、Kotlin
  - React、TypeScript
  - AWS(ECS Fargate/Aurora PostgreSQL)
- 担当業務
  - Reactを使用したフロントエンド開発
  - Spring Bootを利用したWebAPIの開発
  - TerraformによるAWSのインフラ構築
  - チューニング
- プロジェクトの成果
  - フロントエンドからインフラ構築まで全ての行程を担当

### 金融系企業でAWSを中心としたインフラの構築、監視基盤の構築
- 利用した技術
  - AWS
  - Datadog
- 担当業務
  - TerraformによるAWSのインフラ設計・構築・運用
  - Datadogを利用した監視体制の設計・開発・運用
  - AWSの運用に必要なツールの開発(Lambda + Go の組み合わせが多い)
  - AWSの運用改善
    - AWSのサービスを導入したセキュリティの強化、IAMアカウント管理見直し、コスト削減のための構成見直しなど
  - EC2上のアプリケーションをECS Fargateに移行
    - インフラの設計構築、監視設定、性能試験、チューニング、CI/CDの構築などを担当
  - EC2上のバッチ処理をStepFunctions + ECS Fargateに移行
    - インフラの設計構築、監視設定、CI/CDの構築などを担当
- プロジェクトの成果
  - 「EC2上のアプリケーションをECS Fargateに移行」に関して
    - EC2からFargateに変更することで、EC2の運用コストやAWSコストを削減した
    - 無停止によるリリースを行い、ユーザーに影響がで無い形で移行を完了させた
    - ECSでの開発経験を生かし、EC2からECSに移行する際の注意点を先行してチームに共有しすることで開発速度が向上した
  - 「EC2上のバッチ処理をStepFunctions + ECS Fargateに移行」に関して
    - EC2を常時起動する構成からバッチの実行時のみFargateを起動する構成に変更したため、EC2の運用コストやAWSコストを削減できた
    - StepFunctionsのエラー処理やLambdaによるエラーハンドリングを導入することで、AWS側で障害が発生した場合も自動で再実行する仕組みを導入し、安定的なバッチの実行環境を構築した
    - 開発の初期段階でCI/CDを導入することにより、チームの開発速度が向上した
  - 監視が不十分な状態から監視基盤を構築することで、サービスの異常にすぐに対応できる状態にした
  - チームにTerraformを扱ったことがあるメンバーが少なかったのでTerraformの社内向けの勉強会を開催し、インフラ担当者以外もTerraformを利用してAWSの設定ができるようになった
    - 勉強会を録画として残すことで、新規メンバーが参画した際もTerraformのキャッチアップできる環境になっている

### EC2で作成されているWebAPIをDockerに移行(Docker/AWS)
- 利用した技術
  - Docker
  - AWS ECS（Fargate）
- 担当業務
  - Dockerfileの作成やコンテナ実行基盤の設計等
  - TerraformによるAWSのインフラ構築
  - Gatlingを使用した性能試験の実施、チューニング
- プロジェクトの成果
  - ローカル開発環境のDocker移行により、チームメンバー間の環境構築における差異を最小化した 
  - デプロイを簡素化し、開発生産性を向上した

### メディア系Webアプリケーションの開発(Nuxt.js/Laravel/AWS)
- 利用した技術
  - Nuxt.js
  - TypeScript
  - Laravel
  - AWS(Lambda/API Gateway)
- 担当業務
  - Nuxt.js(TypeScript)を使用したフロントエンド開発
  - Laravelを利用したWebAPIの開発
  - TerraformによるAWSのインフラ構築 
- プロジェクトの成果
  - フロントエンドからインフラ構築まで全ての行程を担当
  
  当時Googleボットがまだ上手くSPAのJavaScriptを解析してくれなかったので、SSR（サーバーサイドレンダリング）が必要だと判断しNuxt.jsを導入しました。
  
  少しオーバーエンジニアリングかと思いましたが、結果的にフロントエンドの開発効率が良くなり、割と短期間でリリース出来ました。
  
### Salesforceを利用した社内システム開発(Apex/JavaScript)
- 利用した技術
  - Saleseforce
  - Apex
  - JavaScript
- 担当業務
  - アジャイル開発によるプロジェクト管理がメイン
  - ビジネスサイドとの調整、要件定義から開発・運用保守までを担当
  - JavaScriptを利用したフロントエンド開発
- プロジェクトの成果
  - もともと負債の多いシステムであったため、技術的負債を取り除き、サービスの継続的な開発・運用を可能とした
  - アジャイル開発でプロジェクト管理により、社内システムの短期間におけるリプレースを可能とした

  負債が重なることによってサービスの開発速度が低下し、テストコードがないことによって不具合が多発することを経験。設計やテストコードの重要性を実感しました。

  これ以降の開発においては最初の段階で設計を重要視し、テストを自動化するようにしています。
  
### 業務システムのリプレース(独自言語を利用したフロントエンド開発)
- 利用した技術
  - 独自言語
- 担当業務
  - 独自言語を利用したフロントエンド開発
  - 要件定義から保守・運用までを担当
- プロジェクトの成果
  - 当初は開発メンバとして参画したが、ユーザとの要件定義までを担当しプロジェクトに貢献した
  - 初めてのアジャイル開発であったため、アジャイル開発について書籍・勉強会等で学習しに必要な知識をチームに反映した
  
  独自言語であったため、調べても情報が出てこない、言語にバグがあっても対応されない等の理由でとても苦労しました。

  この経験があったことで、オープンソースの技術に興味を持ちました。

 
### 業務システムの新規開発(Vb.NET/SQL server)
- 利用した技術
  - Vb.NET
- 担当業務
  - 画面の作成
  - SQL Serverのビューを作成
  - テスト

## その他

新しい技術や領域にチャレンジするために個人開発をしています。

### 個人プロダクト (LGTMeow)
友人との共同開発で「LGTMeow」という猫のLGTM画像を共有出来るサービスを作成しました(2021年)。

- 利用した技術
  - Next.js、TypeScript
  - Go
  - Vercel(Next.jsを動作させるために利用)
  - AWS(S3/CloudFront/Lambda/API Gateway/Cognito)
- 担当業務
  - Next.jsを利用したフロントエンド開発
  - Goを利用したWebAPIの開発
  - TerraformによるAWSのインフラ構築

### 個人プロダクト (Mindexer)
友人との共同開発で「Mindexer」というQiitaのストックを管理するためのサービスを作成しました(2019年)。

- 利用した技術(詳細についてはこちらの記事に記載してあります。[AWS + Laravel + Vue.js でQiitaのストックを整理するサービスを作りました！【個人開発】](https://qiita.com/kobayashi-m42/items/14e137727ffda3bf79e7))
  - Vue.js
  - TypeScript
  - Laravel
  - AWS(S3/CloudFront/AWS ECS(Fargate))
- 担当業務
  - Vue.jsを利用したフロントエンド開発(デザイン含めて担当)
  - Laravelを利用したWebAPIの開発
  - TerraformによるAWSのインフラ構築
- 補足
  - QiitaAPIのOAuthを利用した認証・認可処理も構築しており、OAuthの知識もあります。

