# Vue.js Hands-on

## Vue.js を使う目的とメリット

- 目的：JS でラクにアプリケーションを作成するため
- メリット：汎用的な（仕様変更に強い）設計ができる

### JavaScript を使う目的

- DOM を操作
- 非同期でデータを取得

  👉 アプリケーションを作る

### JavaScript フレームワークとは

- JS でアプリケーションを制作する際の便利機能をパッケージしたもの

  👉 素の JS で書くと面倒なことも、すでに機能化されている

- フレームワークを使うことで、実装方法を共通化することができる

  👉  同じ要件に対して、記述方法を統一することができる

### Vue.js とは

#### Vue.js 単体はテンプレートライブラリ

- 記述方法は HTML にマスタッシュやディレクティブを記述して使用する

  👉  学習コストが低い

- Vue.js で DOM を操作する際の考え方

  👉  データを変更することで DOM を操作する（ **データバインド** ）

- Vue.js は機能をパーツ化できる

  👉  機能単位でパーツ化し、組み合わせて設計できる（ **コンポーネント** ）

- ルーターやストアシステムなどのモジュールを組み合わせることでフレームワーク的なものになる

  👉  段階的に機能を追加できる（ **プログレッシブ** ）

- アニメーション用の機能も持っている

  👉  UX を考慮したアプリケーションの作成が（比較的）容易にできる

## Vue.js の設計パターン

### データバインディング

- データにより View を操作する
- イベント発火時にデータを操作し、View を変える

  👉  DOM と関数に依存関係がなくなり、それぞれ追加・削除などの改修がラクにできる

### コンポーネント

- 機能として独立しているコンポーネントを組み合わせて開発

  👉  他コンポーネントに依存させないことで、追加・削除などの改修がラクにできる

[参考：イメージで伝える「Vue.js とは」](https://lab.aratana.jp/entry/2017/12/09/000000)

## Hands-on Practice

実際に制作してみましょう！

### その前に

**Vue 用デバッガ**：Vue.js devtools for [Chrome](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=ja) or [Firefox](https://addons.mozilla.org/ja/firefox/addon/vue-js-devtools/)

※ インストールしたら **devtools** の詳細設定で「ファイルの URL へのアクセスを許可する」を ON にしてください。

![ファイルの URL へのアクセスを許可する](https://user-images.githubusercontent.com/3617124/51724845-964e1080-20a2-11e9-8d7a-6f36f31c24bb.png)

**おすすめエディタ**：[Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/) & Vue VS Code Extension Pack
