コンソールログを使用するためのエクステンションクラス
=================================

概要
--------------------------------------------------
`console()->log('fooo');`
で、ブラウザのコンソールに、ログを出力できるようになるエクステンションです。


MarkdownExtraに関する詳細は、

https://michelf.ca/projects/php-markdown/extra/

を参照して下さい。

パッケージ管理
--------------------------------------------------
EnviConsoleExtensionパッケージをEnviMvcにバンドルさせるには、

`envi install-bundle new https://raw.githubusercontent.com/EnviMVC/EnviConsoleExtension/master/bundle.yml`

コマンドを実行します。

インストール・設定
--------------------------------------------------

パッケージがバンドルされていれば、

`envi install-extension {app_key} {DI設定ファイル} console`

コマンドでインストール出来ます。

