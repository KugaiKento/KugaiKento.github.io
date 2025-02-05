---
permalink: /
title: "Rubyのjekyllを使ってGithub pagesにデプロイしてみた"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

お楽しみ会で先生がGithub Pagesを使うよーみたいなことを言ってた気がするのでせっかくなのでシンプルにHTMLだけじゃなくてJekyllという静的サイトジェネレーター(SSG)を使ってみました。
ちなみに左のアイコンは友達がかいてくれた絵です。お気に入りです。

Ruby ? Jekyll ? とは
======
3年生はwebの技術に関係する科目が多いと思います、PHPでショッピングサイトを作成したり、Javascriptを使う機会が多かったと思います。ですがRubyはあまり馴染み
が無い人が多いのではないでしょうか。
## Rubyとは
Rubyとは日本発のプログラミング言語で皆さんが普段使っているPHP同様オブジェクト指向のプログラミング言語です。ただし他のプログラミング言語との違いとして、オブジェクト指向のプログラミング言語の中でも、コードの書きやすさと読みやすさが特徴的なプログラミング言語といえます。通常、コードを書くときは、セミコロンや、カッコを省略してしまうと、syntax errorなどが出たりと思った通りに実行できないことが多いです。ですがRubyはセミコロンを省略しても実行できるので、かなり文章量を省略することが出来ます。

## Rubyを使うと出来ること
Rubyを使えば、WebサイトやWebアプリ・スマホアプリ・APIなどが開発が得意な言語で、サーバーサイドの処理に長けていることからweb系のシステム開発に重宝されています。

Jekyllとは?
======
ではその中でもJekyllとは何なのかというと、Jekyllは静的なウェブサイトやブログを作成するためのオープンソースの静的サイトジェネレーター(SSG)でRubyで開発されています。HTMLをあまり書くことなく、MarkDownなどをベースにコンテンツを記述し、HTMLやCSSも使えて外観や構造も管理できます。このサイトもJekyllを使っていて記事もMarkDownを使って記述しています。  
みなさんは普通サイトを作るときにはHTMLで文字を入力したりすることが多いと思います。ブログを作るなら外部のCMSのAPIキーを入力してデータを持ってきてそれを表示、というステップを踏む必要がありますが、Jekyllを使うとその作業が減るためかなり便利なものになっております。  
さらにJekyllには無料のテーマやテンプレートが多くあり、一から作る必要がないものが多いので、すぐ自分のブログを構築出来たりGithub Pagesとも相性がいいのでデプロイも無料でできるというのが魅力的です。皆さんも気になったら就活のポートフォリオブログなどでも一度使ってみてください!

<!-- Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
