# 問題集まとめ

## 第 1 回

### 間違えたメモ

- 運用上の優秀性
  - ガバナンス、コンプライアンス、リスク監査には AWS Config、セキュリティ評価には Amazon inspector
- データベース
  - ビックデータのデータ分析には Amazon EMR、S3 等の SQL 分析には Amazon Athena
  - Amazon DynamoDB はデフォルトでマルチ AZ 構成
- ストレージ
  - EBS には自動バックアップ機能はない
  - S3 において MFA を使用して削除する際の認証を求めるにはバージョニングを有効にする
- サーバーレス
  - Amazon SQS はポーリング方式、Amazon SNS はプッシュ方式
- AWS の設計原則
- IAM・認証
  - オンプレミスの ID 管理と同様に権限を制御するには IAM を使用する

## 第 2 回

### 間違えたメモ

- コスト最適化
  - コスト見積もりを行う際に AWS を利用中であれば Cost Exproler、利用前では AWS Pricing Calculator
- ネットワーク
  - Route 53 では DNS 名前解決、ドメイン登録の他にファイアウォール(Route 53 Resolver DNS Firewall)が使用できる
  - **AWS Global Accelerator** はトラフィックパフォーマンスを向上させる
  - **Amazon Lightsail**は仮想プライベートサーバーを提供するサービス
- 運用上の優秀性
  - 望ましいビジネス成果を達成するためには **AWS プロフェッショナルサービス**を利用する
- AWS サポート
  - AWS CAF のセキュリティパースペクティブの機能は、データ保護とインフラストラクチャの保護
- 環境の自動化
  - Chef や Puppet を使用したインフラの設定自動化には**OpsWorks**を使用する
  - アプリケーションを構成してデプロイと管理を実施ができ、プロビジョニング、負荷分散、自動スケーリングなどの機能を提供するサービスは**AWS Elastic Beanstalk**
  - Docker コンテナイメージを AWS クラウドに保存するには**Amazon ECR**を利用する、**Amazon ECS**はコンテナを管理するサービス
- IAM・認証
  - IAM ポリシーは IAM ユーザ、IAM グループ、IAM ロールに紐づける、IAM ロールはサービスに紐づける
  - AWS リソースに対して一時的な認証情報を提供する機能は **AWS STS**
  - AWS サービスへのプログラム呼び出しを認証するためには、アクセスキーとシークレットアクセスキーが必要
- 移行・接続
  - AWS Snowball edge をテラバイト単位のストレージ移行に使用する。
- セキュリティ
  - **AWS Network Firewall** は AWS VPC において、ファイアウォールを展開するサービス
- データベース
  - リアルタイムランキング処理を行うアプリケーション向けの DB サービスは **Amazon Memory DB for Redis**
  - オンプレミス閑居うに AWS の DB(だけでなく、サービス、API、ツール)を使用するには**AWS Outposts**を使用する
  - **Amazon EC2 Image Builder**は、AMI の作成、テスト、メンテナンスを自動化するサービス
- AWS サービス詳細
  - **Amazon Comprehend** を使用して文書内容を検知して自動的に分類する
