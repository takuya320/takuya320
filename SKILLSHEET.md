(最終更新日: 2026年3月28日)

# 自己PR
- バックエンドの開発経験が5年以上ある。直近はGoを用いた開発が多いです。
- インフラもAWSを利用した経験が豊富。GCPも現在副業で触れています。
- フロントエンドやネイティブも開発の経験があり、幅広い領域の知見を活かした開発が可能です。
- スピード感を持って仕様を形にし、ブラッシュアップしていくような開発が好きです。
- 裁量のある仕事が嬉しいです。
- 事業のあらゆる問題を幅広い技術の知見を用いて解決したり、プロダクトの安定運用に貢献できるテックリードを目指してます。

# 職務経歴

|                   年月 | 学歴・職歴                         | 備考                                                    |
| ---------------------: | :--------------------------------- | :------------------------------------------------------ |
|  2014年4月 – 2018年3月 | 青山学院大学　情報テクノロジー学科 | 研究はUnityを用いたドローン操縦システムの開発に従事     |
| 2018年4月 – 2021年12月 | ユナイテッド株式会社               | ソーシャルゲームやWebサービスの新規開発・運用に従事     |
|  2022年1月 – 2024年7月 | 株式会社サイバーエージェント       | 小売企業向けのアプリSDKや広告配信プロダクトの開発に従事 |
|            2024年8月 – | 株式会社Gaudiy                     | コミュニティサービスの新機能開発やデータ基盤構築に従事   |

## スキルセット
- Go, React, Next.js, Vue.js, TypeScript, Node.js, Java, SpringBoot, SAStruts, Scala, Python, Flutter, Swift, dbt
### クラウド
- AWS, GCP
### サーバー
- Linux, nginx, Apache Tomcat
### DB
- MySQL, PostgreSQL, Redis, Snowflake, BigQuery, Spanner
### CI/CD
- GithubActions, Jenkins, GitLab Runner
### 監視
- Datadog, CloudWatch, CloudLogging
### その他
- Docker, Terraform, Swagger, Google Apps Script, Lima, Mantis, GitLab, BitBucket, SendGrid, DevCycle, GKE, Datastream, Dataflow, AWS DMS

# 担当プロジェクト

## ソーシャルゲームの新規開発

■ 使用技術
- Java, AWS(ECS Fargate), MySQL, Node.js, Google Apps Script

■ 開発時期
- 2018年4月 - 2020年3月

<details>
<summary>プロジェクトの詳細</summary>

### プロジェクト内容

- RestAPIで通信を行うiOS・Android向けソーシャルゲーム（Unity）
- エンジニア15人くらいのチーム

### 担当

- サーバサイドのエンジニアとしてクライアントエンジニアと相談しながら、要件を整理しDBの設計から実装まで行いました。
- リリース後は追加機能の設計・実装とオンコール対応を行いました。

### 実績

サーバサイド
- APIをJavaで実装
- 管理画面をthymeleafで実装
- Redisを用いてゲームイベントのリアルタイムランキング機能を実装
- Node.jsでサーバ側の負荷テストツールを自作し、かつ複数ユーザの操作を自動化しデバッグ用ツールとしても活用
- クライアントエンジニアとの共有のために、Swaggerを用いてAPIドキュメントを更新があるたびに自動生成
- JUnitでユニットテストの導入
- サービスクローズ時のリソースの削除などの対応
</details>


## ソーシャルゲームの運用・機能追加

■ 使用技術
- Java, AWS(EC2), PostgreSQL, JavaScript(CreateJS)

■ 開発時期
- 2020年4月 - 2020年12月

<details>
<summary>プロジェクトの詳細</summary>

### プロジェクト内容
- DAU約4万人のiOS・Android向けソーシャルゲーム
- エンジニア5人くらいで開発

### 担当
- フォーマット化されたゲーム内イベントの運用と効率化を行いました。
- DBのログやエンドポイントの計測結果からボトルネックとなっている部分の特定・改善を行いました。
- AWS旧環境を新しい環境に移行・コスト削減行いました（Saving Plans、リザーブドインスタンスの適用）。
- オンコール対応を行いました。

### 実績

#### フロントエンド
- WebView, Velocity, HTML, CSS(SCSS) , JavaScript(Angular.js)で実装
- Adobe Animate CCアニメーションの組み込み

#### バックエンド
- Javaで実装
- PostgreSQLのクエリ改善
- TwitterAPI利用 + Twitterカード対応

#### インフラ
- EC2のSavong Plans、RDSのリザーブドインスタンス、ElastiCacheのリザーブドノードを購入
- AWSのリソースを把握しコスト削減を実施（EC2を新しくて安いインスタンスに移行、不要なリソースの削除）
- Jenkinsを用いてチェックツールなどを定期実行

#### その他
- 社内のGitLabを運用
- デバッグ進捗管理用のMantisを運用
- ChatOpsの導入
</details>

## プロフィール作成Webサービスの新規開発

■ 使用技術
- Java, AWS(EC2), PostgreSQL, TypeScript(Vue.js)

■ 開発時期
- 2021年1月 - 2021年12月

<details>
<summary>プロジェクトの詳細</summary>

### プロジェクト内容
- プロフィール作成Webサービス
- WebViewを用いてアプリ版もリリース
- エンジニア3人、デザイナー1人、ビジネス1人で開発・運用

### 担当
- インフラ環境の設計から構築を全て担当しました。（お名前.comでドメイン取得、https化、CloudFrontの設置、オートスケール化、ダウンタイム0のデプロイ）
- フロントエンドとバックエンドどちらの設計・機能実装にも関与しました。
- リリース後はオンコール対応を行いました。

### 実績
#### フロントエンド
- TypeScript + Vue.jsで実装
- SEO対策
- WebSocketの導入

#### バックエンド
- Javaで実装
- AWS S3への画像アップロード処理を実装
- DBマイグレーションツールFlywayの導入
- 全文検索エンジンpg_bigmの導入
- 決済プラットフォームStripeの導入

#### インフラ
- 開発環境・本番環境を一人で担当
- Amazon EC2 Auto Scalingでオートスケール対応
- JenkinsやGitlabのWebhookを用いてビルド・デプロイを自動化
- CloudWatchアラーム設定、追加メトリクスの取得
</details>


## 小売店アプリ向けSDKの追加機能開発、運用

■ 使用技術
- Go, AWS(API Gateway, Lambda → ECS Fargate), MySQL, DataDog, Snowflake, TypeScript(React, next.js), Swift

■ 開発時期
- 2022年1月 - 2023年3月

<details>
<summary>プロジェクトの詳細</summary>

### プロジェクト内容
- スマホがビーコンやNFCタグをトリガーとして、アプリ上でコンテンツを配信可能にするSDK
- バックエンド2人、Fフロントエンド人、iOS1人、Android1人、データサイエンティスト1人、ビジネス2人

### 担当
- サーバーサイドエンジニアとして、機能要件定義から開発まで担当
- インフラは前職の経験を生かしてメインで担当
- Snowflakeによるログ分析基盤の開発も担当
- プロジェクトの開発進捗に応じてフロントエンド、ネイティブ（iOS）の開発も

### 実績
#### バックエンド
- Goで実装
- MySQLを使い、DBボトルネックの特定、改善
- k6による負荷テストのシナリオ作成と実施

#### インフラ
- AWSのインフラ環境をterraformでコード管理
- DataDogによる監視を導入
- ログをSnowflakeに保持するための機構の開発

#### フロントエンド
- TypeScript + React（next.js）で管理画面を開発
- Swaggerによるドキュメント作成

#### iOS
- SwiftでSDKの追加機能を開発

#### その他
- SDK導入方法すり合わせのため顧客アポに同席
- 顧客アプリへのSDK導入時に結合テストを設計・実施
- 導入時の知見から追加機能の提案、設計を実施
- 脆弱性診断の依頼、修正

</details>


## 広告配信プロダクトの新規開発

■ 使用技術
- Go, AWS(ECS Fargate), Scala（armeria）, MySQL, DataDog, Python(Prefect), TypeScript(React)

■ 開発時期
- 2023年4月 - 2023年10月

<details>
<summary>プロジェクトの詳細</summary>

### プロジェクト内容
- ドラッグストア向けのアプリ/EC向けの広告配信プロダクトの開発
- バックエンド6人、フロントエンド1人、データサイエンティスト1人、ビジネス3人

### 担当
- 小売店のアプリ会員情報を利用してターゲティング配信と計測を行うサーバーの実装
- 配信設定を行う管理画面の開発

### 実績
#### バックエンド
- ターゲティング配信と計測を行うためのAPIの開発
- AWS FireLens、FluentBit、Firehoseを用いたログ転送フローの設計・実装
- Cognitoによる認証とSMSを用いた2段階認証の構築
- Casbinを用いた認可処理の仕組みを実装
- PrefectとPythonでファイル連携時のワークフローを構築
- GoogleAdManagerのAPIを呼び出す処理をScalaで実装
- 企業間のファイル連携システムの運用
- 外部ベンダーシステムとのファイル連携とバッチ実行フローの設計・実装

#### インフラ
- AWSのインフラ環境をterraformでコード管理
- DataDogによる監視を実施

#### フロントエンド
- Reactで管理画面を開発
- Swaggerによるドキュメント作成

</details>


## NFTを用いたコミュニティ作成アプリの新規開発（副業）

■ 使用技術
- Go, GCP(CloudRun), MySQL, Flutter

■ 開発時期
- 2023年8月 - 10月

<details>
<summary>プロジェクトの詳細</summary>

### プロジェクト内容
- バックエンド3人、Flutter1人、デザイナー1人、ビジネス1人で開発

### 担当
- バックエンドのAPI開発とGCPのインフラ整備を担当
- Flutterを用いて、アプリ側の開発も対応

### 実績
- Terraform管理しているGCP環境のCI/CDを導入
- エラーログとGCPアラートのSlack通知基盤の構築
- ディープリンクを用いた招待機能の設計・実装（ユニバーサルリンクにも対応）
- GithubActionsでterraformを用いてGCP環境のCI/CDを構築
- stream_chat_flutterを用いたチャット機能の実装
- 追加機能のバックエンドAPI開発

</details>


## LLMを用いた広告配信効率化システムの開発

■ 使用技術
- Go, GCP(ClourRun), PostgreSQL, GraphQL, TypeScript(React), SendGrid, DevCycle, Azure OpenAI Service

■ 開発時期
- 2023年11月 - 現在

<details>
<summary>プロジェクトの詳細</summary>

### 担当
- バックエンとGCPのインフラ開発を担当

### 実績
- エラーログとGCPアラートのSlack通知基盤の構築
- フィーチャーフラグ管理ツールの導入（DevCycle）
- メール送信基盤の構築（SendGrid）

</details>


## グローバル向けエンタメコミュニティサービスの新機能開発

■ 使用技術
- Go, GCP(Cloud Run Jobs, Cloud Workflows), AWS(Fargate, DynamoDB), MySQL, Redis, TypeScript(React), Datadog, Terraform, GithubActions, Connect RPC

■ 開発時期
- 2024年8月 - 2026年1月

<details>
<summary>プロジェクトの詳細</summary>

### プロジェクト内容

- 海外ユーザーを中心としたアニメ・マンガ関連のコミュニティプラットフォームの新機能開発

### 担当

- バックエンドの設計・開発を担当

### 実績

#### バックエンド
- 既存認証基盤を活用した認証の仕組みの設計・実装
- GCP・AWSをまたいだマルチクラウド構成のデータ集計ジョブの開発
- DynamoDBの導入
- 新機能のバックエンド設計・実装
- レガシーDB由来の文字化け問題の調査・対応
- フロントエンド行動ログ基盤の導入
- gRPC（Connect RPC）の導入

</details>


## データ基盤構築・toBダッシュボード開発

■ 使用技術
- Python, Next.js, Go, dbt, Terraform, GithubActions, GCP(GKE, Spanner, Datastream, Dataflow, BigQuery), AWS(DMS)

■ 開発時期
- 2026年1月 - 現在

<details>
<summary>プロジェクトの詳細</summary>

### プロジェクト内容

- データ基盤の構築と、それに付随するtoB向けダッシュボードの開発

### 担当

- データ基盤の設計・構築およびダッシュボード開発を担当

### 実績

#### データ基盤
- dbtによるデータETLパイプラインの構築
- AWS DMS・Datastream・Dataflowを組み合わせたマルチクラウド構成のデータリアルタイム同期基盤の構築
- Gemini APIを活用したデータパイプラインの構築
- Pythonによるデータ分析ジョブの開発
- 外部データプロバイダーの選定（他社比較・データ取得要件の整理・契約交渉を主導）

#### フロントエンド / バックエンド
- Next.jsによるtoB向けダッシュボードの開発（フロントエンド・バックエンド両方を実装）
- ログ取得要件の整理およびフロントエンドでのログ計測実装（GDPR/CCPA対応を含む）
- フィーチャーフラグの導入

#### インフラ
- Terraformによるインフラのコード管理
- GithubActionsによるCI/CDの構築

</details>
