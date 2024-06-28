[GitHub CI/CD実践ガイド――持続可能なソフトウェア開発を支えるGitHub Actionsの設計と運用](https://gihyo.jp/book/2024/978-4-297-14173-8)

## ［基礎編］

## 第1章　ソフトウェア開発とGitHub
- [x] 1.1　ソフトウェア開発
- [x] 1.2　CI/CD
- [x] 1.3　GitHub
- [x] 1.4　環境構築
- [x] 1.5　まとめ

## 第2章　GitHub Actionsの基礎概念
- [x] 2.1　GitHub Actionsをはじめよう
- [x] 2.2　GitHub Actionsの構成要素
- [x] 2.3　GitHub Actionsの実行
- [x] 2.4　GitHub Actionsのエラー
- [x] 2.5　ワークフローの起動方法
- [x] 2.6　ワークフローの実行管理
- [x] 2.7　ジョブの実行環境
- [x] 2.8　アクション
- [x] 2.9　GitHub Actionsの課金モデル
- [x] 2.10　まとめ

## 第3章　ワークフロー構文の基礎
- [x] 3.1　コンテキスト
- [x] 3.2　環境変数
- [x] 3.3　Variables
- [x] 3.4　Secrets
- [x] 3.5　式
- [x] 3.6　関数
- [x] 3.7　条件分岐
- [x] 3.8　ネーミング
- [x] 3.9　ステップ間のデータ共有
- [x] 3.10　GitHub APIの実行
- [x] 3.11　スターターワークフロー
- [x] 3.12　まとめ

## 第4章　継続的インテグレーションの実践
- [x] 4.1　プルリクエストによる継続的インテグレーションの起動
- [x] 4.2　自動テスト
- [x] 4.3　イベントのフィルタリング
- [x] 4.4　セットアップアクション
- [x] 4.5　静的解析
- [x] 4.6　タイムアウト
- [x] 4.7　シェル
- [x] 4.8　Concurrency
- [x] 4.9　継続的インテグレーションの黄金律
- [x] 4.10　自動テストの運用プラクティス
- [x] 4.11　静的解析の運用プラクティス
- [x] 4.12　まとめ

## 第5章　運用しやすいワークフローの設計
- [x] 5.1　ワークフロー設計の道具箱
- [x] 5.2　ロギング
- [x] 5.3　レポーティング
- [x] 5.4　チャット通知
- [x] 5.5　複数ジョブの実行制御
- [x] 5.6　マトリックス
- [x] 5.7　Environments
- [x] 5.8　キャッシュ
- [x] 5.9　アーティファクト
- [x] 5.10　まとめ

## 第6章　アクションによるモジュール化
- [x] 6.1　アクションの分類
- [x] 6.2　Composite Action
- [x] 6.3　メタデータ構文
- [x] 6.4　メタデータ構文とワークフロー構文の違い
- [x] 6.5　アクションの設計プラクティス
- [x] 6.6　まとめ

## ［実践編］
第7章　クリーンなリポジトリの維持
- [x] 7.1　コードレビュー
- [x] 7.2　ブランチの保護
- [x] 7.3　オーナーシップの維持
- [x] 7.4　クレデンシャルの混入防止
- [x] 7.5　ドキュメンテーション
- [x] 7.6　まとめ

## 第8章　Dependabotによる依存関係バージョンアップ
- [x] 8.1　依存関係
- [x] 8.2　Dependabot
- [x] 8.3　GitHub Actionsによる自動マージ
- [x] 8.4　Dependabotのワークフロー設計
- [x] 8.5　バージョンアップの影響範囲
- [x] 8.6　自動マージ戦略
- [x] 8.7　まとめ

## 第9章　GitHub Releasesによるリリース自動化
- [x] 9.1　ソフトウェアのリリース
- [x] 9.2　バージョニング
- [x] 9.3　アナウンス
- [x] 9.4　GitHub Releases
- [x] 9.5　リリースノートの自動生成
- [x] 9.6　リリースの自動化
- [x] 9.7　Gitタグの保護
- [x] 9.8　まとめ

## 第10章　GitHub Packagesによるパッケージ管理
- [x] 10.1　パッケージ
- [x] 10.2　GitHub Packages
- [x] 10.3　Container Registry
- [x] 10.4　GitHub Packagesの管理
- [x] 10.5　パッケージの自動リンクとパーミッションの継承
- [x] 10.6　コンテナイメージの自動リリース
- [x] 10.7　まとめ

## 第11章　OpenID Connectによるセキュアなクラウド連携
- [ ] 11.1　クラウドプロバイダのクレデンシャル
- [ ] 11.2　OpenID Connect
- [ ] 11.3　検証作業のリスクヘッジ
- [ ] 11.4　AWSにおけるOpenID Connectの利用準備
- [ ] 11.5　OpenID ConnectによるAWS連携
- [ ] 11.6　Cloud Rolesのセキュアな運用
- [ ] 11.7　まとめ

## 第12章　コンテナオーケストレーションのデプロイメント
- [ ] 12.1　サービス
- [ ] 12.2　実行環境の構築
- [ ] 12.3　デプロイ情報のVariables管理
- [ ] 12.4　デプロイの自動化
- [ ] 12.5　Environmentsを利用した複数環境デプロイ
- [ ] 12.6　デプロイメント設計
- [ ] 12.7　まとめ

## 第13章　アクションのオープンソース化
- [ ] 13.1　アクションの公開
- [ ] 13.2　アクションのテスト
- [ ] 13.3　アクションのリリースマネジメント
- [ ] 13.4　アクションのドキュメンテーション
- [ ] 13.5　GitHub Marketplaceへの公開
- [ ] 13.6　アクションの進化プロセス
- [ ] 13.7　まとめ

## ［応用編］
第14章　GitHub Actionsの高度な使い方
- [ ] 14.1　Reusable Workflows
- [ ] 14.2　動的なワークフロー定義
- [ ] 14.3　エラーハンドリング
- [ ] 14.4　コンテキストによるフロー制御
- [ ] 14.5　プライベートアクションとプライベートReusable Workflows
- [ ] 14.6　まとめ

## 第15章 GitHub Actionsのセキュリティ
- [ ] 15.1　ソフトウェアサプライチェーン
- [ ] 15.2　セキュリティの設計原則
- [ ] 15.3　GitHubのサービス特性
- [ ] 15.4　リポジトリの保護
- [ ] 15.5　サードパーティアクションのセキュリティ
- [ ] 15.6　スクリプトインジェクション
- [ ] 15.7　最小権限のパーミッション
- [ ] 15.8　シークレットマネジメント
- [ ] 15.9　Forkプルリクエスト対策
- [ ] 15.10　OpenID Connectハードニング
- [ ] 15.11　まとめ

## 第16章　セキュリティのシフトレフト
- [ ] 16.1　シフトレフト
- [ ] 16.2　依存関係の脆弱性スキャン
- [ ] 16.3　シークレットスキャン
- [ ] 16.4　アプリケーションセキュリティ
- [ ] 16.5　Infrastructure as Codeセキュリティ
- [ ] 16.6　継続的なセキュリティ改善
- [ ] 16.7　まとめ

## 第17章　GitHub Appsトークンによるクロスリポジトリアクセス
- [ ] 17.1　GitHubのクレデンシャル
- [ ] 17.2　GitHub Appsトークン
- [ ] 17.3　クロスリポジトリアクセス
- [ ] 17.4　GitHub Appsトークン生成の仕組み
- [ ] 17.5　GitHub Appsトークンの運用プラクティス
- [ ] 17.6　まとめ

## 第18章　継続的デリバリーの実践
- [ ] 18.1　組織パフォーマンス
- [ ] 18.2　バージョン管理戦略
- [ ] 18.3　テスト戦略
- [ ] 18.4　リリース戦略
- [ ] 18.5　データベースの変更管理
- [ ] 18.6　Infrastructure as Codeの変更管理
- [ ] 18.7　疎結合なアーキテクチャ
- [ ] 18.8　運用を忘れない
- [ ] 18.9　継続的な学び
- [ ] 18.10　まとめ
