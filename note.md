# Storybookについて調べる

## 調査タスク

- [ ] storyとは？
- [ ] Markdownで仕様書が書ける？
  - 以下のサイトに記載してあった
    - [StoryBook駆動で新規システムの開発を試してみた | ドクセル](https://www.docswell.com/s/kght6123/KNVL2Z-2022-01-27-211430#p1)
- [ ] Fetch APIのモックが書ける？
  - 以下のサイトに記載してあった
    - [StoryBook駆動で新規システムの開発を試してみた | ドクセル](https://www.docswell.com/s/kght6123/KNVL2Z-2022-01-27-211430#p1)
- [ ] コンポーネントのビジュアルテストができる？


## メモ

- UIのカタログを作成するツール
- UIコンポーネントの管理、テストをすることができる
- React、Vue、Angularなどの主要なJSフレームワークで導入できる
- 各コンポーネントのUIやpropsに応じた挙動の確認ができる
  - Webアプリ上でpropsを指定し、その値を受け取ったコンポーネントを表示することができる。
- コンポーネント単位でドキュメントを用意することができる
- Storybookにコンポーネントを登録するためには、storyというものをJavaScriptで記述する必要がある
- storyの書き方の一つとしてCSF(Component Story Format)があり、CSFはESmoduleをベースとして記述している書き方で、default export/named exportから構成されている
- ローカルでStorybookのwebアプリを起動することができ、そのwebアプリ上でコンポーネントの挙動等を確認することができる

### Storybookのメリット

- コンポーネント駆動型開発ができる
- ページと分離してUIコンポーネントを開発できる
- UIコンポーネント開発時のサンドボックスとして利用できる
  - Storybookを利用しない場合、UIコンポーネントの動作確認にそこそこ手間がかかる
    - UIコンポーネントを表示するまでに手順が必要がある
    - 動作確認のために親コンポーネント等を変更する必要がある
    - など
- APIをモックできる
- UIコンポーネントに対するビジュアルテストができる
- UIコンポーネントのドキュメントを作成することができる
- コンポーネント開発を分担することができる

## 環境構築

コマンドメモ
```
# Install Storybook ( for Vue2 )
$ npx sb init --type vue

# Start Storybook
$ npm run storybook
```


## 参考サイト

* [storybookを理解する](https://zenn.dev/kyo9bo/articles/bd37f814b33909)
* [Storybookについて調べてみました。](https://tech.stmn.co.jp/entry/2021/05/17/155842)
* [StoryBook駆動で新規システムの開発を試してみた | ドクセル](https://www.docswell.com/s/kght6123/KNVL2Z-2022-01-27-211430#p1)
* [Storybookを使ってコンポーネントを管理できるようにしよう](https://www.techpit.jp/courses/109/curriculums/112/sections/841/parts/3119)
* [Storybookを使ってプロダクトのデザイン管理をやってみた](https://service.plan-b.co.jp/blog/tech/29109/)
* [Storybookを導入してみてわかった、導入おすすめプロジェクトの特徴](https://fintan.jp/page/378/)
* [Storybook を腐らせずに運用しよう](https://qiita.com/keik/items/e275394d454b8b136826)
* [今さらながらStorybookを使ってみたら良いツールだった](https://www.ey-office.com/blog_archive/2020/11/18/storybook-is-good-tool/)
* [Storybook First な開発のススメ](https://blog.ojisan.io/storybook-first-develop/)
