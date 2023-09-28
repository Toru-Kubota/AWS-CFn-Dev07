# パッチマネージャーを使用したパッチ適用
## 構成
* Amazon Linux 2023用のパッチベースラインを作成
* EC2インスタンスにPatchGroupタグの付与
* パッチグループを作成してパッチベースラインと対象インスタンスの紐付け
* メンテナンスウインドウを作成し実行間隔を指定
* メンテナンスウインドウターゲットを作成しパッチグループと紐付け
* メンテナンスウインドウタスクでパッチ適用タスクを指定
* AWS-RunPatchBaselineドキュメントがRun Commandで実行される

![sc-cfn-dev07](https://github.com/Toru-Kubota/AWS-CFn-Dev07/assets/102895466/176fe118-68e1-4985-a4b7-44b8997faddd)
