# rails-tutorial202403

by copilot

## このリポジトリについて

このリポジトリは、[Ruby on Rails チュートリアル](https://railstutorial.jp/)の学習用リポジトリのようなものです。

## ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)に従って、[MIT ライセンス](https://opensource.org/licenses/MIT)で公開されています。

## 使い方 

### インストール（動作未確認）

```bash
$ git clone
$ cd rails-tutorial202403
$ bundle install
$ yarn install
$ rails db:migrate
```

### 起動（動作未確認）

```bash
$ rails server
```

### テスト（動作未確認）

```bash
$ rails test
```

### デプロイ（動作未確認）

```bash
$ git push heroku main
$ heroku run rails db:migrate
```

## その他

### 作成時メモ

```bash
rails new rails-tutorial202403 -T -S -M -d mysql --skip-spring --webpack=react
```