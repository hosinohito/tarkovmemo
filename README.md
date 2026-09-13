# Tarkov Memo

GitHub Pagesで公開する個人メモサイトです。

## 記事の追加

`_posts/`に次の形式でMarkdownファイルを追加します。

```text
YYYY-MM-DD-記事の名前.md
```

先頭には次の情報を付けます。

```yaml
---
layout: post
title: 記事タイトル
date: 2026-09-14
category: NOTE
tags: [tag]
---
```

記事は`main`ブランチへのcommit後、GitHub Pagesによって自動公開されます。

