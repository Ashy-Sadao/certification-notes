# 問題集まとめ

## 第 1 回
### 間違えたメモ
* 運用上の優秀性
  * ガバナンス、コンプライアンス、リスク監査にはAWS Config、セキュリティ評価にはAmazon inspector
* データベース
  * ビックデータのデータ分析にはAmazon EMR、S3等のSQL分析にはAmazon Athena
  * Amazon DynamoDBはデフォルトでマルチAZ構成
* ストレージ
  * EBSには自動バックアップ機能はない
  * S3においてMFAを使用して削除する際の認証を求めるにはバージョニングを有効にする
* サーバーレス
  * Amazon SQSはポーリング方式、Amazon SNSはプッシュ方式
* AWSの設計原則
* IAM・認証
  * オンプレミスのID管理と同様に権限を制御するにはIAMを使用する