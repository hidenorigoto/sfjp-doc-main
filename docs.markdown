---
layout: default
title: Symfony ドキュメント
---

Symfonyドキュメント
===================

ユーザー会独自のドキュメントや、公式サイトの日本語ドキュメントへリンクなどをまとめています。


Symfony2関連
------------

#### Symfony2日本語ドキュメントポータル

  - [Symfony2 ドキュメント日本語版](http://docs.symfony.gr.jp)<br>
    Symfony2公式ドキュメント（クイックツアー、ガイドブック、クックブック、リファレンス）の翻訳と、日本ユーザー会オリジナルのBlogチュートリアル、アプリケーション開発チュートリアルがあります。


#### 英語公式ドキュメント

  - [Symfony2 Documentation](http://symfony.com/doc/current/)
  - [Symfony2 API](http://api.symfony.com/2.0/index.html)
  - [Doctrine2 ORM](http://www.doctrine-project.org/projects/orm/2.1/docs/en)
  - [MongoDB ODM](http://www.doctrine-project.org/docs/mongodb_odm/1.0/en/)
  - [Twig Documentation](http://twig.sensiolabs.org/documentation)



公式ドキュメント翻訳への参加方法
------------------------------

現在、公式ドキュメントの翻訳はGitHubを使って行われています。
[GitHubの使い方](github-howto)などを参考に、ご自分で翻訳したものを公式リポジトリへPull Requestする流れです。
（ユーザー会ドキュメント整備の流れと同じです）

  - [Symfony2 日本語ドキュメントのリポジトリ](http://github.com/symfony-japan/symfony-docs-ja)
  - [Symfony2 日本語ドキュメント翻訳手順](https://github.com/symfony-japan/symfony-docs-ja/wiki)
  - [Symfony2 英語ドキュメントのリポジトリ](http://github.com/symfony/symfony-docs)
  - [symfony 1.xドキュメントのリポジトリ](http://github.com/symfony/symfony1-docs)



ユーザー会ドキュメント整備への参加方法
------------------------------------

  - [ユーザー会ドキュメントへの参加方法](joining-userdocs)
    - [GitHub の使い方](./git/github-howto)
    - [Windows 上に Git 環境を構築する方法(TortoiseGit と msysGit)](./git/setup-git-windows)
    - [GitHub 上のリポジトリのフォーク、プッシュ、プルリクエスト](./git/git-fork-and-push)
  - [日本語表記ガイドライン](japanese-style)
  - [markdown早見表](markdown-sample)
  - [markdown簡易チェック](http://www.symfony-project.org/plugins/markdown_dingus)<br />
    markdownがどのようにレンダリングされるのかを、Webブラウザからテストできます。



1.4入門者向け
-------------

  - [symfony 1.4のインストール方法（入門者・評価向け）](docs/for-beginners/installation)
  - [Blogチュートリアル](docs/for-beginners/blog-tutorial/?sk=file&so=asc)<br />
    データベースの単一のテーブルに対する一覧、追加、削除、編集の機能をシンプルに実装するチュートリアルで、symfonyの基本を学ぶことができます。
    [CakePHPのブログチュートリアル](http://book.cakephp.org/ja/view/219/Blog)と同等のものを開発しますので、CakePHPとの機能比較の参考にしてください。


1.4向け公式ドキュメント日本語訳
-------------------------------

  - **A Gentle Introduction to symfony**<br />
    [HTML](http://www.symfony.gr.jp/docs/symfony1-docs/gentle-introduction/ja/?sk=file&so=asc) ([公式サイト内](http://www.symfony-project.org/gentle-introduction/1_4/ja/))<br />
    symfony 完全ガイドの内容を symfony 1.4 向けに書き直されたもので、特にフォームや ORM、メールまわりの内容が 1.4 向けに全面的に書き直されました。
    symfony 1.4 の基本をしっかり学びたい方は、ひととおり読まれるとよいでしょう。

  - **実践symfony 1.3 & 1.4(Doctrine) (Practical symfony)**<br />
    [HTML](http://www.symfony.gr.jp/docs/symfony1-docs/jobeet/ja/?sk=file&so=asc) ([公式サイト内](http://www.symfony-project.org/jobeet/1_4/Doctrine/ja/))<br />
    **実践symfony 1.3 & 1.4(Propel) (Practical symfony)**<br />
    [公式サイト内](http://www.symfony-project.org/jobeet/1_4/Propel/ja/?sk=file&so=asc)<br />
    Jobeetという仕事情報サイトを構築しながらsymfonyの機能を一通り学習できるチュートリアルです。
    フレームワークを使った開発やMVCについての知識はあって、symfonyでの実践的な開発手法をすぐに学びたいという方におすすめです。
    Doctrine版とPropel版に分かれている点に注意してください。symfony 1.3以降では、デフォルトではDoctrineです。

  - **symfony 1.3 & 1.4 リファレンスガイド (The symfony Reference Book)**<br />
    [HTML](http://www.symfony.gr.jp/docs/symfony1-docs/reference/ja/?sk=file&so=asc) ([公式サイト内](http://www.symfony-project.org/reference/1_4/ja/))<br />
    symfonyで使われている各種設定ファイルやイベントについてのリファレンスです。
    実際に開発する段階で参照することの多いドキュメントです。

  - **もっと知りたいsymfony (More with symfony 1.3 & 1.4)**<br />
    [HTML](http://www.symfony.gr.jp/docs/symfony1-docs/more-with-symfony/ja/?sk=file&so=asc) ([公式サイト内](http://www.symfony-project.org/more-with-symfony/1_4/ja/))<br />
    symfonyの使い方を一通り身につけた後、さらに高度な使い方を知りたい方向けのドキュメントです。
    また、symfony 1.3から利用できるSwiftMailerについての解説もこのドキュメントにあります。


  - **Doctrine ORM for PHP**<br />
    [HTML(公式)](http://www.doctrine-project.org/projects/orm/1.2/docs/manual/ja)<br />
    symfonyにバンドルされているORMのDoctrineのマニュアルです。


### symfony 1.x 旧バージョンのドキュメント

  - **symfony完全ガイド 1.2(The Definitive Guide to symfony 1.2)**<br />
    [PDF](http://cloud.github.com/downloads/masakielastic/masakielastic.github.com/sf-book-1.2-ja.pdf)<br />
    symfony 1.2時点でのドキュメントですが、symfony 1.4でも根本の部分は共通していますので、十分に役立ちます。
    symfonyの基本をしっかり学ぶ事ができます。
    入門者から中級者まで、一読をおすすめします。<br />
    symfony 1.4に対応した「Gentle introduction to symfony」も近日中に翻訳予定です。

  - **The symfony and Doctrine book**<br />
    [HTML(公式)](http://www.symfony-project.org/doctrine/1_2/ja/)<br />
    symfony 1.3以降でデフォルトとなったORMのDoctrineについて、symfonyからの使い方を説明したドキュメントです。
    スキーマの記述方法から、DQLの記述方法など、一通りのことが分かります。

  - **symfony Forms in Action**<br />
    [HTML](http://www.symfony-project.org/forms/1_2/ja/)<br />
    symfonyのフォームフレームワークsfFormについて、基本から解説したドキュメントです。
    また、ウィジェットやバリデーターの一覧もここにあります。



参考リンク
----------

  - [markdownの文法](http://blog.2310.net/archives/6)
