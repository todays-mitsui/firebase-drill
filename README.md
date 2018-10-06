# Firebase Drill

20181006 JavaScript つまみ食いハンズオン用

## 準備

### Node インストール

Node.js (npm) のインストールが必要です。
インストールされていない人は [公式サイト](https://nodejs.org/ja/) からダウンロードしてインストールしてください。

### firebase-drill をダウンロード

[JavaScript つまみ食いハンズオン用のリポジトリ](https://github.com/todays-mitsui/firebase-drill) を用意しています。
`git clone` するか、 ZIP 形式でダウンロードして手元に準備しておいてください。

### Google アカウントを作成

Google アカウントを持っていない方がいましたら作成しておいてください。
[Google アカウントの作成](https://accounts.google.com/signup/v2/webcreateaccount?hl=ja&flowName=GlifWebSignIn&flowEntry=SignUp) から新規アカウントを作成できます。


## きょう作るもの

![スクリーンショット](https://i.imgur.com/xtjNHQY.png)

Firebase を利用して簡易的なメッセージアプリを作成します。
HTML+CSS でインターフェースを作り JavaScript で制御する、いわゆる Web アプリケーションの形式です。

## Step.0 - Firebase プロジェクトを作成

ブラウザで [Firebase コンソール](https://console.firebase.google.com/?hl=ja) にアクセスして新しいプロジェクトを作成します。
プロジェクト名, プロジェクト ID ともに自由に設定して構いません。

プロジェクトを作成するとアクセストークンなどの重要な情報を取得できるようになります。

![リンク](https://i.imgur.com/I9G2F60.png)

![トークン取得](https://i.imgur.com/G9Uxvwl.png)

本日のデモを動かすのに使用しますので、わかりやすい場所にコピーして控えておいてください。


