■ 注意事項
　・# は入力不要です。

■ 各サービスのサイトへのアクセス先

  □ Code-Server
　　既にブラウザのタブで開いています

  □ GitHub リモートリポジトリ
	https://github.com/dis-ecstraining/ecs56
    ● Username: dis.ecstraining@gmail.com
    ● Password: Zaq12wsx@dis


  □ AWS CodePipeline パイプライン
	https://ap-northeast-1.console.aws.amazon.com/codesuite/codepipeline/pipelines/ecs56-pipeline/view?region=ap-northeast-1

  □ AWS ECR プライベートリポジトリ
	https://ap-northeast-1.console.aws.amazon.com/ecr/repositories/private/227436085244/ecs56-app?region=ap-northeast-1

  □ ECS タスク定義 
	https://ap-northeast-1.console.aws.amazon.com/ecs/v2/task-definitions/ecs56-family?status=ACTIVE&region=ap-northeast-1

  □ ECSクラスタ内のタスク
	https://ap-northeast-1.console.aws.amazon.com/ecs/v2/clusters/ecs56-cluster/tasks?region=ap-northeast-1

  □ 稼働中のWebサイト
　　手順書をご参照ください。


■ GitHubにソース、設定ファイルをアップロードするコマンド
  □ ローカルリポジトリの初期化
 　　# git init

  □ リモートリポジトリの設定
     # git remote add origin git@github.com:dis-ecstraining/ecs56.git

  □ リモートリポジトリの確認
     # git remote -v 

  □ ローカルリポジトリをリモートリポジトリに送付
 　　# git add .
     # git commit -m "3rd"
     # git push -f origin master
