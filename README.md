# CoderDojo Kumano

https://coderdojo-kumano.github.io/

## 記事の書き方

`_posts` 以下のディレクトリに以下の要領で記事を追加し、プルリクエストをください。

### ファイル名

`2016-12-19-hello.md` のように `日付-タイトル.md` というフォーマットのファイル名で記事を作成してください。

この例では、`/2016/12/19/hello/` という URL になります。

### 記事

記事は以下のフォーマットで書いてください。

```
---
layout: post
title: Welcome to jekyll!
subtitle: Jekyll is a blog-aware, static site generator in Ruby https://jekyllrb.com
date: 2016-05-20 21:11:27
author: Takayuki Miyauchi
header-image: path/to/image.png
---
ここから記事の本文。

記事はマークダウンフォーマットで書いてください。
```


## ローカル環境でのプレビュー

```
$ git clone git@github.com:coderdojo-kumano/coderdojo-kumano.github.io.git
$ cd coderdojo-kumano.github.io
$ bundle install --path vendor/bundle
$ bundle exec jekyll serve
```
