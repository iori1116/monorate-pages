# モノレート GitHub Pages

このフォルダは、Yahoo!デベロッパー登録やApp Store申請で使うための公開ページ一式です。

## 公開するファイル

- `index.html`: サイトURL
- `privacy.html`: プライバシーポリシーURL
- `terms.html`: 利用規約URL
- `styles.css`: 共通スタイル

## GitHub Pagesで公開する流れ

1. GitHubで新しいリポジトリを作成します。
   - 例: `monorate-pages`
2. このフォルダの中身をリポジトリにアップロードします。
3. GitHubのリポジトリ画面で `Settings` を開きます。
4. `Pages` を開きます。
5. `Build and deployment` の `Source` を `Deploy from a branch` にします。
6. Branchを `main`、Folderを `/root` にします。
7. 数分後に公開URLが発行されます。

公開後のURL例:

```text
https://ユーザー名.github.io/monorate-pages/
https://ユーザー名.github.io/monorate-pages/privacy.html
https://ユーザー名.github.io/monorate-pages/terms.html
```

## 公開前に変更する場所

`privacy.html` と `terms.html` の以下を自分のメールアドレスに変更してください。

```text
your-email@example.com
```
