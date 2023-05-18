

- 前提条件:iphoneかandroidを持っていること

- 前提条件2:`expo`アプリをお手持ちのケータイにダウンロードしていること

## ソースコードのダウンロード

このリポジトリのソースコードをダウンロードしましょう


## build開始

```sh
docker-compose build
```

## bashを起動します

```sh
docker-compose run react_native bash
```

## アプリケーション初期設定

以下のコマンドを実行して、`testapp`プロジェクトを作成するコマンドを実行しましょう。

`testapp`は任意のコマンドに変えて問題ありません。

```sh
expo init testapp
```

もしテンプレートファイルの選択を迫られたときは...

```sh
› npx create-expo-app --template

? Choose a template: › - Use arrow-keys. Return to submit.
    ----- Managed workflow -----
    blank               a minimal app as clean as an empty canvas
❯   blank (TypeScript)  same as blank but with TypeScript configuration
    tabs (TypeScript)   several example screens and tabs using react-navigation and TypeScript
    ----- Bare workflow -----
    minimal             bare and minimal, just the essentials to get you started
```

この`blank (TypeScript)`をお勧めします。

```sh
❯   tabs (TypeScript)   several example screens and tabs using react-navigation and TypeScript
```

インストールが完了すれば、以下のようなログが見えるはずです。

```sh
✅ Your project is ready!

To run your project, navigate to the directory and run one of the following yarn commands.

- cd testapp
- yarn start # you can open iOS, Android, or web from here, or run them directly with the commands below.
- yarn android
- yarn ios # requires an iOS device or macOS for access to an iOS simulator
- yarn web
```

## `testapp`ディレクトリに移動

```sh
cd testapp
```

## start expo project

```sh
npx expo start --tunnel
```

こちらもなにか質問されたら... yを押しましょう。

```sh
Starting Metro Bundler
✔ The package @expo/ngrok@^4.1.0 is required to use tunnels, would you like to install it globally? ...y
```

## 形態を開いて、QRコードを読み込みましょう

もしプロジェクトの起動がうまくいった場合は、以下のようにQRコードを表示します。

これが表示されたらQRコードを読み込み、アプリケーションを起動しましょう。

```sh
> npm install --global @expo/ngrok@^4.1.0
Installed @expo/ngrok@^4.1.0
Tunnel connected.
Tunnel ready.
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
█ ▄▄▄▄▄ █▄▀ ▀ ▀ █ ██▄▄█ ▄▄▄▄▄ █
█ █   █ █   █▀ ▀█▄▀ ▄ █ █   █ █
█ █▄▄▄█ █▄█▀ ▄▀ ▄ ▀▀ ▀█ █▄▄▄█ █
█▄▄▄▄▄▄▄█▄█ █ █▄█ ▀▄▀▄█▄▄▄▄▄▄▄█
█▄▄  ██▄▀▄█ ▄ █▄█ ▄█▀▀▄▀█ ▄ █ █
█▄ ▀▄  ▄█▄  ▄▄  ▀█▄▀▀▀█▀▄▀▀██▀█
█▀ ▀▄█▄▄▀█▄▄▀ ▄▄▀█▄  █▄▀██▀▄ ▀█
█▀▄▄█▄▀▄ ██▀ █▄▄▀▄██▄▄ ▀█▄█▄ ▄█
█▄▀ █ ▀▄▄▀▀██▄█▄▀▄█▀▄▀▄█▀▄█▀▀▄█
█▄█▄▄ █▄██▄█▀█  ▄█▀▄▀█ ██▀  ▀██
██▄▄▄██▄▄ ▄▄██▄▄▄▀▄██ ▄▄▄ █▄  █
█ ▄▄▄▄▄ ██▀▀▀▀▀ █▄▄█▄ █▄█ ▀▄▄▀█
█ █   █ █▀▀█ █▀█ ▀  ▀▄ ▄    ▄ █
█ █▄▄▄█ █ ▄ █ ▀▄█ █▀█ █▀▄█ █▀▄█
█▄▄▄▄▄▄▄█▄██▄███▄███▄▄█▄█▄██▄██

› Metro waiting on exp://p4nnzh0.anonymous.19000.exp.direct
› Scan the QR code above with Expo Go (Android) or the Camera app (iOS)

› Web is waiting on http://localhost:19000

› Press a │ open Android
› Press w │ open web

› Press j │ open debugger
› Press r │ reload app
› Press m │ toggle menu

› Press ? │ show all commands

Logs for your project will appear below. Press Ctrl+C to exit.

```


<img src="./screenshot/react_native_start.jpg">

