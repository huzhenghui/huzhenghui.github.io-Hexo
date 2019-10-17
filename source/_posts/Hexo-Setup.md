---
title: Hexo Setup
comments: true
tags:
  - Hexo
categories:
  - - Hexo
    - Learn
keywords:
  - hexo
date: 2019-10-16 12:45:26
updated: 2019-10-17 12:43:55
---

# Hexo Setup

## 进入项目父目录

```bash 进入项目父目录
cd ~/OneDrive/Hexo
```

## 初始化项目

```bash 初始化项目
hexo init Init --no-install
```

## 进入项目文件夹

```bash 进入项目文件夹
cd Init
```

## 查看初始化文件

```bash 查看初始化文件
find . -path './themes/*/*' -prune -o -print | tree --fromfile . --noreport -F --sort=name -n | pbcopy
```

```plain 初始化文件
.
└── ./
    ├── _config.yml
    ├── package.json
    ├── scaffolds/
    │   ├── draft.md
    │   ├── page.md
    │   └── post.md
    ├── source/
    │   └── _posts/
    │       └── hello-world.md
    └── themes/
        └── landscape
```

## 安装依赖包

```bash 安装依赖包
npm install
```

## _config.yml

```bash _config.yml
cat _config.yml | pbcopy
```

```yaml _config.yml
# Hexo Configuration
## Docs: https://hexo.io/docs/configuration.html
## Source: https://github.com/hexojs/hexo/

# Site
title: Hexo
subtitle:
description:
keywords:
author: John Doe
language: en
timezone:

# URL
## If your site is put in a subdirectory, set url as 'http://yoursite.com/child' and root as '/child/'
url: http://yoursite.com
root: /
permalink: :year/:month/:day/:title/
permalink_defaults:
pretty_urls:
  trailing_index: true # Set to false to remove trailing index.html from permalinks

# Directory
source_dir: source
public_dir: public
tag_dir: tags
archive_dir: archives
category_dir: categories
code_dir: downloads/code
i18n_dir: :lang
skip_render:

# Writing
new_post_name: :title.md # File name of new posts
default_layout: post
titlecase: false # Transform title into titlecase
external_link:
  enable: true # Open external links in new tab
  field: site # Apply to the whole site
  exclude:
filename_case: 0
render_drafts: false
post_asset_folder: false
relative_link: false
future: true
highlight:
  enable: true
  line_number: true
  auto_detect: false
  tab_replace:

# Home page setting
# path: Root path for your blogs index page. (default = '')
# per_page: Posts displayed per page. (0 = disable pagination)
# order_by: Posts order. (Order by date descending by default)
index_generator:
  path: ''
  per_page: 10
  order_by: -date

# Category & Tag
default_category: uncategorized
category_map:
tag_map:

# Metadata elements
## https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta
meta_generator: true

# Date / Time format
## Hexo uses Moment.js to parse and display date
## You can customize the date format as defined in
## http://momentjs.com/docs/#/displaying/format/
date_format: YYYY-MM-DD
time_format: HH:mm:ss
## Use post's date for updated date unless set in front-matter
use_date_for_updated: false

# Pagination
## Set per_page to 0 to disable pagination
per_page: 10
pagination_dir: page

# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: landscape

# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
  type:
```

## package.json

```bash package.json
cat package.json | pbcopy
```

```json package.json
{
  "name": "hexo-site",
  "version": "0.0.0",
  "private": true,
  "scripts": {
    "build": "hexo generate",
    "clean": "hexo clean",
    "deploy": "hexo deploy",
    "server": "hexo server"
  },
  "hexo": {
    "version": ""
  },
  "dependencies": {
    "hexo": "^3.9.0",
    "hexo-generator-archive": "^1.0.0",
    "hexo-generator-category": "^1.0.0",
    "hexo-generator-index": "^1.0.0",
    "hexo-generator-tag": "^1.0.0",
    "hexo-renderer-ejs": "^1.0.0",
    "hexo-renderer-stylus": "^1.1.0",
    "hexo-renderer-marked": "^2.0.0",
    "hexo-server": "^1.0.0"
  }
}
```

## scaffolds

### scaffolds/draft.md

```bash scaffolds/draft.md
cat scaffolds/draft.md | pbcopy
```

```markdown scaffolds/draft.md
---
title: {{ title }}
tags:
---
```

### scaffolds/page.md

```bash scaffolds/page.md
cat scaffolds/page.md | pbcopy
```

```markdown scaffolds/page.md
---
title: {{ title }}
date: {{ date }}
---
```

### scaffolds/post.md

```bash scaffolds/post.md
cat scaffolds/post.md | pbcopy
```

```markdown scaffolds/post.md
---
title: {{ title }}
date: {{ date }}
tags:
---
```

## source

### source/_posts/hello-world.md

## themes

### themes/landscape