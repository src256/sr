Simple Responsive Skin for PukiWiki
===================================

PukiWiki 1.5.1対応のシンプルなレスポンシブスキンです。

- [デモサイト](https://srcw.net/pukiwiki/)

作成にあたり[PukiwikiレスポンシブSkin](http://reddog.s35.xrea.com/wiki/Pukiwiki%E3%83%AC%E3%82%B9%E3%83%9D%E3%83%B3%E3%82%B7%E3%83%96Skin.html)を参考にさせていただきました。

## 実行環境

- PukiWiki 1.5.1

## インストール方法

- GitHubからダウンロードします。
```
$ git clone https://github.com/src256/sr.git
```
- srディレクトリをPukiWikiのskinディレクトリ以下にコピーします。
```
$ cp -a sr ~/public_html/wiki/skin
```
- default.ini.phpを編集しsr.skin.phpを読み込みます。
```
define('SKIN_FILE', DATA_HOME . SKIN_DIR . '/sr/sr.skin.php');
```
- 外見をカスタマイズする場合srディレクトリ内にsr-custom.cssを作成します。


## ライセンス

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)
