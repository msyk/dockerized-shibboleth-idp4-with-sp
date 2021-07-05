こちらはShibbolethをDocker環境で動かすためのDockerfileです。インストール方法、使い方などは以下のブログをご覧ください！！  
https://tech-lab.sios.jp/archives/19270

--

上記レポジトリをクローンしました。takeiさん、大変に有効な情報と素材を提供いただきありがとうございます。

こちらでは、spに対して以下の変更を行いました。INTER-Mediatorに関係ない方々にとっては、PHP 7.4がShibboleth SPベースで動くと思っていただければと思います。

- PHP 7.4、composer、gitのインストール
- /secure/info.phpを追加（phpinfo()関数を実行します）
- SAMLのテストアプリをセットアップ（https://github.com/msyk/saml-trial）
- 上記内にINTER-Mediatorをセットアップ（https://github.com/msyk/INTER-Mediator）

新居雅行　Masayuki Nii nii@msyk.net
2021-07-05