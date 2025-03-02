# GitHub プロファイル検証アプリケーション

このプロジェクトは、Reclaimプロトコルを使用してGitHubユーザープロファイルの検証を行うReactアプリケーションです。

## 機能

- QRコードを使用したGitHubアカウントの認証
- GitHubユーザー情報（ユーザーネーム、アカウント作成年、昨年の貢献数）の表示
- Reclaimプロトコルによる検証プロセスの可視化

## 環境設定

`.env`ファイルに以下の環境変数を設定する必要があります：

```
REACT_APP_RECLAIM_APP_ID=your_app_id_here
REACT_APP_RECLAIM_APP_SECRET=your_app_secret_here
REACT_APP_RECLAIM_PROVIDER_ID=your_provider_id_here
```

## 利用可能なスクリプト

プロジェクトディレクトリで以下のコマンドを実行できます：

### `npm start`

開発モードでアプリを実行します。\
[http://localhost:3000](http://localhost:3000)を開いてブラウザで表示します。

コードを変更すると、ページは自動的にリロードされます。\
コンソールにlintエラーも表示されます。

### `npm test`

インタラクティブなウォッチモードでテストランナーを起動します。\
詳細については、[テストの実行](https://facebook.github.io/create-react-app/docs/running-tests)のセクションを参照してください。

### `npm run build`

本番用のアプリを`build`フォルダにビルドします。\
Reactを本番モードで正しくバンドルし、最高のパフォーマンスのためにビルドを最適化します。

ビルドは縮小され、ファイル名にはハッシュが含まれます。\
アプリをデプロイする準備ができました！

詳細については、[デプロイメント](https://facebook.github.io/create-react-app/docs/deployment)のセクションを参照してください。

### `npm run eject`

**注意：これは一方向の操作です。一度`eject`すると、元に戻せません！**

ビルドツールと設定の選択に満足していない場合は、いつでも`eject`できます。このコマンドはプロジェクトから単一のビルド依存関係を削除します。

代わりに、すべての設定ファイルと推移的依存関係（webpack、Babel、ESLintなど）をプロジェクトに直接コピーするため、それらを完全に制御できます。`eject`以外のすべてのコマンドは引き続き機能しますが、コピーされたスクリプトを指すようになるため、調整できます。この時点で、あなたは自分自身で対処する必要があります。

`eject`を使用する必要はありません。キュレートされた機能セットは小規模および中規模のデプロイメントに適しており、この機能を使用する義務はありません。ただし、準備ができたときにカスタマイズできない場合、このツールは役に立たないことを理解しています。

## 詳細情報

[Create React Appドキュメント](https://facebook.github.io/create-react-app/docs/getting-started)で詳細を確認できます。

Reactを学ぶには、[Reactドキュメント](https://reactjs.org/)をご覧ください。

### コード分割

このセクションは[こちら](https://facebook.github.io/create-react-app/docs/code-splitting)に移動しました。

### バンドルサイズの分析

このセクションは[こちら](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)に移動しました。

### プログレッシブウェブアプリの作成

このセクションは[こちら](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)に移動しました。

### 高度な設定

このセクションは[こちら](https://facebook.github.io/create-react-app/docs/advanced-configuration)に移動しました。

### デプロイメント

このセクションは[こちら](https://facebook.github.io/create-react-app/docs/deployment)に移動しました。

### `npm run build`が縮小に失敗する

このセクションは[こちら](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)に移動しました。
