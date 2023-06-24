## Edibleとは
『Edible』は規格外農産物を減らし、持続可能な社会の実現を目指します。 

味が同じでも形が悪いため、棄てられる農産物は全体の2-3割存在します。   
本サービスはそれら規格外農産物を減らし、世の中のフードロスを減らします。   
さらにSDGs Goal12の『つくる責任、つかう責任』達成に則しています。 

<img width="1440" alt="スクリーンショット 2023-06-08 1 52 53" src="https://github.com/zksytmkn/myapp_root/assets/86869822/75953b4b-22e1-4d0d-b11e-360f893724b8">

## URL
~~https://edible-app.com~~
(一時停止中)

## 機能一覧
・新規登録, ログイン, ゲストログイン, ログアウト  
・お問い合わせ, 利用規約, プライバシーポリシー  

・プロフィール, プロフィール編集, メールアドレス変更, パスワード変更, アカウント削除  
・フォロー, フォロー解除, フォロー一覧, フォロワー一覧  

・農産物の一覧, 詳細  
・農産物の出品, 編集, 削除  
・農産物のその他 （いいね, ないね, コメント, カートに入れる, 検索, 購入済み）  
・カート (カートから削除する)  
・レジ (購入する)  

・農家のつぶやきの一覧, 詳細  
・農家のつぶやきの投稿, 編集, 削除  
・農家のつぶやきのその他 （いいね, ないね, コメント, 検索）  

・コミュニティの一覧, 詳細  
・コミュニティの作成, 編集, 削除  
・コミュニティのその他 （参加する, 招待する, 参加者間のメッセージ, 参加者一覧, 検索）  

・注文の一覧, 詳細 (購入, 販売, 完了)  
・注文のその他 (出品者と購入者間のメッセージ, 注文状況の更新)  
・レスポンシブ対応  

## インフラ構成図
![infra drawio](https://github.com/zksytmkn/myapp_root/assets/86869822/26e4e5cc-9d1a-4e35-8bc5-58ecaa905c80)

## ER図
![edible drawio (2)](https://github.com/zksytmkn/myapp_root/assets/86869822/039bcbfc-1c3d-40b9-8dfd-5df312d193ca)

## 使用技術
### フロントエンド
- JavaScript
- Vue.js v2.7.14
- Nuxt.js v2.15.8 （SPAモード）
- Vuetify v2.6.10
- ESLint v8.40.0
- Jest v29.5.0

### バックエンド
- Ruby v3.1.2
- Rails v7.0.4 （APIモード）
- Rubocop v1.38
- Rspec v6.0.1

### インフラ
- MySQL v8.0.31
- Docker v20.10.21
- Docker Compose v2.13.0

### その他
AWS (ECR, ECS, Fargate, VPC, S3, Route53, ALB, RDS, ACM, etc.)
