# Terraform

なんとなく使い方がわかった

## やったこと
- TerraformのDockerコンテナで指定したコマンドを実行するシェルスクリプトを作成
- ローカルの.configをコンテナにマウントして設定を引き継ぐ
- init, plan, apply
- tfstateをCloud Storageで管理
- 秘匿したい情報をtfvarsで保持
- 利用するサービスごとにmoduleを定義
- moduleの中で複数のresourceを定義(バックエンド用、フロントエンド用など)

## 知りたいこと
- 複数環境の管理方法
