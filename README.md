Asatsuyu
====

Sipmle Resposive Tumblr Theme.

Contents First, コンテンツの邪魔をしないシンプルなテンプレート。

## How to use
テーマのTumblrへの適用方法です。
### 1. インストール
- theme.htmlを開く
- Tumblrダッシュボード「外観を編集」→「テーマの編集」から編集画面を開く
- 「HTMLを編集」からソースコード画面を開く
- もともと記述されているソースコードをバックアップする
- theme.htmlのソースコードを、tumblrのソースコード画面へ貼り付ける
- 保存する

### 2. 初期設定
- 外観オプションを設定する
    - タイトル：サイトのタイトル
    - 説明：サイトの概要説明。ページ下部のABOUTに表示される。

- テーマオプションを設定する
    - ThemeColor：サイトのアクセントとなるカラー。選択時のハイライトカラーとして採用される。

    - analytics：Google Analytics解析用コードを設定。

    - Writer：著者を設定。フッターのCopyright欄に設定される名前。

    - Ctg1～Ctg6：Postのカテゴリ名を設定

    - Ctg1Url～Cteg6Url：カテゴリのリンクを設定。カテゴリに設定するタグ名を用いて、"/tagged/【カテゴリ名】"のように指定する。


## TIPS for Posts
投稿時のTIPS
### Postの構成
下記のような構成で記述すると、表示がきれいにまとまります。

    # Postのタイトル
    
    一覧ページに表示するイントロ句・紹介文。
    縦幅を考慮すると50文字程度がおすすめ。

    [[MORE]]

    本文



### アイキャッチ画像の指定
Photosetを投稿した際、デフォルトでは、1枚目の画像をアイキャッチ画像として一覧へ表示されますが、本テーマでは、2枚目以降の画像を指定することも可能です。

1. Post投稿画面を開き、複数前の写真をアップロードする
2. 写真のレイアウトを変更する
3. 右上の歯車マークをクリックし、フレンドリーURL欄に、"任意の文字列+pnX"(Xに指定したい写真の番号を設定)と入力する  
例えば、小旅行に関するPostに4枚の写真をアップロードし、3枚目の写真をアイキャッチとして使用したい場合は、"小旅行pn3" のように指定する
4. 投稿する
