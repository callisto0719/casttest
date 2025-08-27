# Yattecast

https://callisto0719.github.io/casttest/

## プロジェクト構成

```
├── Gemfile                 # Ruby dependencies
├── Gemfile.lock           # Lock file for dependencies
├── LICENSE.txt            # ライセンス情報
├── _config.yml            # Jekyll設定ファイル
├── docker-compose.yml     # Docker Compose設定
├── favicon.ico            # ファビコン
├── feed.xml               # RSS/Atomフィード
├── index.html             # トップページ
├── _includes/             # Jekyllインクルードファイル
│   ├── footer.html        # フッター
│   ├── head.html          # HTML head部分
│   └── header.html        # ヘッダー
├── _layouts/              # Jekyllレイアウトテンプレート
│   ├── article.html       # 記事レイアウト
│   └── default.html       # デフォルトレイアウト
├── _posts/                # ブログ記事/エピソード
│   └── 2016-11-10-1.md    # サンプル記事
├── audio/                 # オーディオファイル
│   └── # podcastの音源が格納される
├── css/                   # スタイルシート
│   ├── _mixins.scss       # Sassミックスイン
│   ├── _variables.scss    # Sass変数
│   ├── main.scss          # メインスタイルシート
│   └── blocks/            # コンポーネント別スタイル
│       ├── _actor.scss
│       ├── _article.scss
│       ├── _base.scss
│       ├── _card.scss
│       ├── _container.scss
│       ├── _footer.scss
│       ├── _header.scss
│       ├── _list-group.scss
│       ├── _main.scss
│       ├── _markdown.scss
│       ├── _reset.scss
│       ├── _responsive.scss
│       └── _utilities.scss
├── docker/                # Docker設定
│   └── jekyll/
│       └── Dockerfile     # Jekyll用Dockerfile
└── images/                # 画像ファイル
    ├── artwork.jpg        # アートワーク
    ├── screenshot.png     # スクリーンショット
    └── actors/            # 出演者画像
        ├── alice.png
        └── bob.png
```

## 技術スタック

- **Jekyll**: 静的サイトジェネレータ
- **SCSS**: CSSプリプロセッサ
- **Docker**: コンテナ化環境
- **Ruby**: Jekyll実行環境
