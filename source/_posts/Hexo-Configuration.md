---
title: Hexo Configuration
comments: true
tags:
  - huzhenghui.github.io
  - hexo
categories:
  - - huzhenghui.github.io
    - operation
keywords:
  - hexo
date: 2019-10-16 15:42:25
updated: 2019-10-17 12:23:18
---

# Hexo Configuration

## Site

```yaml Site
# Site
title: Hu Zhenghui's Blog
subtitle: Blog Subtitle
description: Blog Description
keywords: Hexo
author: hu@daonao.com
language: zh-CN
timezone: Asia/Shanghai
```

## URL

```yaml URL
# URL
## If your site is put in a subdirectory, set url as 'http://yoursite.com/child' and root as '/child/'
url: https://huzhenghui.github.io
root: /
permalink: :year/:month/:day/:title/
permalink_defaults:
```

## Directory

```yaml Directory
# Directory
source_dir: source
public_dir: public
tag_dir: tags
archive_dir: archives
category_dir: categories
code_dir: downloads/code
i18n_dir: :lang
skip_render:
```

## Writing

`auto_detect`需要设置为`false`，如果设置为`true`，可能遇到`TypeError: Cannot set property 'lastIndex' of undefined`报错

```yaml Writing
# Writing
new_post_name: :title.md # File name of new posts
default_layout: post
titlecase: false # Transform title into titlecase
external_link: true # Open external links in new tab
filename_case: 0
render_drafts: false
post_asset_folder: true
relative_link: false
future: true
highlight:
  enable: true
  line_number: true
  auto_detect: false
  tab_replace: 4
```

## Home page setting

```yaml Home page setting
# Home page setting
# path: Root path for your blogs index page. (default = '')
# per_page: Posts displayed per page. (0 = disable pagination)
# order_by: Posts order. (Order by date descending by default)
index_generator:
  path: ''
  per_page: 10
  order_by: -date
```

## Category & Tag

```yaml Category & Tag
# Category & Tag
default_category: uncategorized
category_map:
tag_map:
```

## Date / Time format

```yaml Date / Time format
# Date / Time format
## Hexo uses Moment.js to parse and display date
## You can customize the date format as defined in
## http://momentjs.com/docs/#/displaying/format/
date_format: YYYY-MM-DD
time_format: HH:mm:ss
```

## Pagination

```yaml Pagination
# Pagination
## Set per_page to 0 to disable pagination
per_page: 10
pagination_dir: page
```

## Extensions

### Extension - Themes

```yaml Extensions
# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: landscape
```

### Extension - Deployment

```yaml Deployment
# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
  type: git
  repository: git@github.com:huzhenghui/huzhenghui.github.io.git
  branch: master
  ignore_hidden: false
```

## Include/Exclude Files or Folders

```yaml Include/Exclude Files or Folders
include:
  - ".nojekyll"
```