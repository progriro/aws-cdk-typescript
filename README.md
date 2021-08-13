# Welcome to your CDK TypeScript project!

This is a blank project for TypeScript development with CDK.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template

 ## AWS CDK (Cloud Development Kit) とは

AWS リソースを 構成要素(construct) としてプログラムで書き、それらを組み合わせて実行するとデプロイできるというツールキットです。開発者視点では、AWSのインフラを TypeScript などのプログラミング言語を使って定義・デプロイできます。裏では、CDKプログラムを実行することで CloudFormation テンプレートを生成、そのテンプレートを使ってデプロイすることになります。これにより、プログラミング言語で実装することによるIDEや型補完の恩恵と、 CloudFormation でデプロイすることによるバリデーションや ChangeSet レビューの恩恵をいいとこどりできます。

## 参考
- [class Instance (construct)](https://docs.aws.amazon.com/cdk/api/latest/docs/@aws-cdk_aws-ec2.Instance.html)
- [Working with the AWS CDK in TypeScript](https://docs.aws.amazon.com/cdk/latest/guide/work-with-cdk-typescript.html)
- [Amazon EC2 インスタンスタイプ](https://aws.amazon.com/jp/ec2/instance-types/)
- [AWS CDK が GA! さっそく TypeScript でサーバーレスアプリケーションを構築するぜ【 Cloud Development Kit 】](https://dev.classmethod.jp/articles/aws-cdk-ga-serverless-application/)
- [AWS-CDK for TypeScriptで色んなサービスをデプロイする](https://qiita.com/is_ryo/items/f04e05768c91c21f3699)