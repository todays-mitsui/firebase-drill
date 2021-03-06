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

## Step.1 - 画面レイアウトを確認

GitHub からダウンロードしたフォルダを使ってアプリケーションを起動してみましょう。

Windows ならコマンドプロンプト、Mac ならターミナルを使ってフォルダを開きます。
そうしたら以下のコマンドを入力して Firebase にログインしてください。

```console
npm install
npm run login
```

ブラウザが開いて Google アカウントでのログインを求められます。
途中どのプロジェクトを使うのか尋ねられるので、ついさきほど作ったプロジェクトを選択してください。

つづいてプロジェクトをセットアップします。

```console
npm run init
```

Firebase のどの機能を有効化させるか尋ねられるので **Firestore** と **Hosting** を選んで有効化させてください。
ちなみに public フォルダを上書きして良いか聞かれるので **No を選んで上書きしないように** してください。

それではいよいよ簡易サーバーを立ち上げてアプリケーションを起動してみましょう。

```console
npm run serve
```

コマンドを実行したら [http://localhost:5000](http://localhost:5000) にアクセスしてください。
さきほどのスクリーンショットと同じような画面が表示されていれば、ひとまずアプリケーションの起動は成功しています。

## Step.2 - さぁコーディング

ここから先は実際にコードを書きながら進めます。
ステップ毎にコーディング済みのファイルを用意していますので、途中でわからなくなったらコードを確認してみてください。

- [Step.1](http://localhost:5000/step1.html)
- [Step.2](http://localhost:5000/step2.html)
- [Step.3](http://localhost:5000/step3.html)
- [Step.4](http://localhost:5000/step4.html)
- [Step.5](http://localhost:5000/step5.html)
- [Step.6](http://localhost:5000/step6.html)
