# カリキュラム

このカリキュラムでは<a href="http://themes.elmastudio.de/tatami/">このシンプルなWordpress theme</a>のコピーを作ることを題材にします。<br>
具体的にはこのthemeのトップページと記事ページの2ページを作ることを課題とします。

- <a href="http://themes.elmastudio.de/tatami/" target="_blank">トップページ</a>
- <a href="http://themes.elmastudio.de/tatami/2012/12/12/tatami-premium-wordpress-theme/" target="_blank">記事ページ</a>

## カリキュラムの順序

### 1.HTMLの作成

目的：情報設計の理解とhtmlの理解および慣れること

1. デザインデータをよく見て情報設計をする
2. 今回作業用にGitのブランチを切る。`git checkout -b feature/html_draft`
3. 情報設計をもとに`source/index_draft.html`にトップページのhtmlを、 `source/article_draft.html`に記事ページのhtmlを記述する
4. 大枠htmlの記述が終わったら、remoteにpushしてmasterブランチに対してプルリクエストをする
5. 講師の確認をもらい、masterブランチに今回の作業をマージする

以上

### 2.hamlの作成

目的：hamlの理解および慣れること

1. 今回作業用にGitのブランチを切る。
 - git checkout master
 - git fetch
 - git pull origin master
 - git checkout -b feature/haml
2. 前項で作成したhtmlをhamlに変換する
 - 共通パーツをレイアウトに書き出す
 - `source/index.html.haml`にトップページのhamlを、 `source/article.html.haml`に記事ページのhaml記述する
3. hamlが書き終わったら、remoteにpushしてmasterブランチに対してプルリクエストをする
4. 講師の確認をもらい、masterブランチに今回の作業をマージする

以上

### 3.ヘッダーのcssをscssで書く

目的：htmlとcssの役割分担を理解すること。css,scssに慣れること

1. 今回作業用にGitのブランチを切る。
 - git checkout master
 - git fetch
 - git pull origin master
 - git checkout -b feature/header_css
2. `source/stylesheets/site.css.scss` にヘッダーのスコープを作ってスタイルを書く
3. メディアクエリを使ってスマートフォン時のスタイルも書く
4. ChromeとIE11でデザインどおりにレイアウトできていることを確認する
5. 完了したらremoteにpushしてmasterブランチに対してプルリクエストをする
6. 講師の確認をもらい、masterブランチに今回の作業をマージする

以上

### 4.ヘッダー以外ののcssをscssで書く

### 5.ヘッダー以外ののcssをscssで書く

### 6. jsで、、








