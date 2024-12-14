# homebrew-tap

いまのところ、自分で作った小さなスクリプトを置いています。

## 使い方

0. このリポジトリを tap として登録する。`brew tap aromarious/tap`
1. `brew install <formula>` でインストールする

## インストールできる Formula

### [`display-rotate`](https://github.com/aromarious/display-rotate)

指定した画面を 90 度回転するコマンド。モバイルディスプレイの縦横を気軽に変更するため、BetterTouchTool で 🌐R に割り当てて使っています。thanks to [`displayplacer`](https://github.com/jakehilborn/displayplacer)

### [`clear-notifications`](https://github.com/aromarious/clear-notifications)

Mac の通知を一括消去するコマンド。macOS Sequoia 15.2 (24C101) にて動作確認済み。これも BetterTouchTool で ⇧🌐N に割り当てて使っています。

注） 実動部分は Applescript で書いてあるため、いつまで動くかわかりません。
