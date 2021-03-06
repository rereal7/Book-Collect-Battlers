# Book-Collect-Battlers

## コンセプト
最強の仲間を探し出せ！

## What is?
- このゲームは、読んだ本を登録すると、その本のステータスを解析します。
- 本を登録するとあなたのチームの兵士となります
- 登録した本から最大3冊を選んで最強のパーティーを作れ！

## How to?
- ISBNコードを入力して本を登録します
- これまで登録した本の中から代表として3冊まで選びます

## Feature
- 本別ランキング
- ユーザー別ランキング (ユーザーの戦闘力だけ→パーティーの詳細が見れる)
- ユーザー同士の対戦とか？
- 本には属性があるとか？

=========================
## 解決したい課題と解決のためのアプローチ
- 読書したいけどなかなか習慣づかない→読んだ本で楽しむゲームがあったら面白いのでは？

## 使用技術
- [openBD 書誌情報の取得API](https://openbd.jp/)
- 言語: PHP (Laravel)
- Server: AWS

## 実現したい機能
1. ISBNコードで本を登録する・一覧が見れる・ステータスを解析する（HP, 攻撃, 防御, 総合戦闘力)
2. これまで登録された本のランキングを表示する
3. パーティー機能の追加（パーティーの作成・更新ができる）
4. 編成したパーティーをユーザー同士で戦わせることができる
