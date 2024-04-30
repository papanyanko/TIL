# Terraform

なんとなく使い方がわかった

## やったこと

### GraphQLの勉強の過程でCI/CDの構築に使った

- TerraformのDockerコンテナで指定したコマンドを実行するシェルスクリプトを作成
- ローカルの.configをコンテナにマウントして設定を引き継ぐ
- init, plan, apply
- tfstateをCloud Storageで管理
- 秘匿したい情報をtfvarsで保持
- 利用するサービスごとにmoduleを定義
- moduleの中で複数のresourceを定義(バックエンド用、フロントエンド用など)

### 詳解Terraformを読んだ

- オートスケールするEC2クラスタとそこにアクセスするロードバランサーを作った

## 知りたいこと
- IAMとかクレデンシャルのベストプラクティスがいまいちわからん
- 複数環境の管理方法
