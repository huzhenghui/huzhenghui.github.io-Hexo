---
title: Hexo Commands
comments: true
tags:
  - hexo
categories:
  - - Hexo
    - Learn
keywords:
  - hexo
date: 2019-10-16 15:09:01
updated: 2019-10-17 12:22:22
---

# Hexo Commands

## init

```bash hexo init syntax
hexo init [folder]
```

```bash hexo init
hexo init
```

```bash hexo init no install
hexo init [folder] --no-install
```

## new

```bash hexo new syntax
hexo new [layout] <title>
```

```bash hexo new
hexo new "Title"
```

```bash hexo new debug
hexo new "Title" --debug
```

## generate

```bash hexo generate
hexo generate
```

```bash hexo generate and deploy
hexo generate --deploy
```

```bash hexo generate and deploy with debug
hexo generate --deploy --debug
```

## server

```bash hexo server
hexo server
```

```bash hexo server and open
hexo server --open
```

```bash hexo server and open with debug
hexo server --open --debug
```

## deploy

```bash hexo deploy
hexo deploy
```

```bash hexo deploy and generate
hexo deploy --generate
```

```bash hexo deploy generate with debug
hexo deploy --generate --debug
```

## clean

```bash hexo clean
hexo clean
```

```bash hexo clean with debug
hexo clean --debug
```

## list

```bash hexo list syntax
hexo list <type>
```

```bash hexo list page with debug
hexo list page --debug
```

```bash hexo list page
hexo list page | pbcopy
```

```plain hexo list page sample
INFO  Start processing
Date        Title  Path
2019-10-16         downloads/code/package.json
```

```bash hexo list post with debug
hexo list post --debug
```

```bash hexo list post
hexo list post | pbcopy
```

```plain hexo list post sample
INFO  Start processing
Date        Title               Path                          Category  Tags
2019-10-15  Hexo Deploy         _posts/Hexo-Deploy.md
2019-10-15  Hexo New            _posts/Hexo-New.md
2019-10-15  Hello World         _posts/hello-world.md
2019-10-15  Git Clone           _posts/Git-Clone.md
2019-10-16  Hexo Setup          _posts/Hexo-Setup.md
2019-10-16  Hexo Init           _posts/Hexo-Init.md
2019-10-16  Hexo-Configuration  _posts/Hexo-Configuration.md
2019-10-16  Hexo Commands       _posts/Hexo-Commands.md
```

```bash hexo list route with debug
hexo list route --debug
```

```bash hexo list route
hexo list route | pbcopy
```

```plain hexo list route sample
INFO  Start processing
Total: 36
├─┬ 2019
│ └─┬ 10
│   ├─┬ 15
│   │ ├─┬ Git-Clone
│   │ │ └── index.html
│   │ ├─┬ Hexo-Deploy
│   │ │ └── index.html
│   │ ├─┬ Hexo-New
│   │ │ └── index.html
│   │ └─┬ hello-world
│   │   └── index.html
│   └─┬ 16
│     ├─┬ Hexo-Commands
│     │ └── index.html
│     ├─┬ Hexo-Configuration
│     │ └── index.html
│     ├─┬ Hexo-Init
│     │ └── index.html
│     └─┬ Hexo-Setup
│       └── index.html
├── .nojekyll
├─┬ archives
│ ├─┬ 2019
│ │ ├─┬ 10
│ │ │ └── index.html
│ │ └── index.html
│ └── index.html
├─┬ css
│ ├─┬ fonts
│ │ ├── FontAwesome.otf
│ │ ├── fontawesome-webfont.eot
│ │ ├── fontawesome-webfont.svg
│ │ ├── fontawesome-webfont.ttf
│ │ └── fontawesome-webfont.woff
│ ├─┬ images
│ │ └── banner.jpg
│ └── style.css
├─┬ fancybox
│ ├── blank.gif
│ ├── fancybox_loading.gif
│ ├── fancybox_loading@2x.gif
│ ├── fancybox_overlay.png
│ ├── fancybox_sprite.png
│ ├── fancybox_sprite@2x.png
│ ├─┬ helpers
│ │ ├── fancybox_buttons.png
│ │ ├── jquery.fancybox-buttons.css
│ │ ├── jquery.fancybox-buttons.js
│ │ ├── jquery.fancybox-media.js
│ │ ├── jquery.fancybox-thumbs.css
│ │ └── jquery.fancybox-thumbs.js
│ ├── jquery.fancybox.css
│ ├── jquery.fancybox.js
│ └── jquery.fancybox.pack.js
├── index.html
└─┬ js
  └── script.js
```

```bash hexo list tag with debug
hexo list tag --debug
```

```bash hexo list tag
hexo list tag | pbcopy
```

```plain hexo list tag sample
INFO  Start processing
Name                  Posts  Path
Front matter              1  tags/Front-matter/
Hexo                      1  tags/Hexo/
hexo                      2  tags/hexo/
huzhenghui.github.io      1  tags/huzhenghui-github-io/
no-tag                    1  tags/no-tag/
```

```bash hexo list category with debug
hexo list category --debug
```

```bash hexo list category
hexo list category | pbcopy
```

```bash hexo list category sample
INFO  Start processing
Name                  Posts
Hexo                      2
Learn                     1
child-category            1
huzhenghui.github.io      1
operation                 1
parent-category           1
```

## version

```bash hexo version with debug
hexo version --debug
```

```bash hexo version
hexo version | pbcopy
```

```plain hexo version sample
hexo: 3.9.0
hexo-cli: 3.0.0
os: Darwin 19.0.0 darwin x64
node: 12.11.1
v8: 7.7.299.11-node.12
uv: 1.32.0
zlib: 1.2.11
brotli: 1.0.7
ares: 1.15.0
modules: 72
nghttp2: 1.39.2
napi: 5
llhttp: 1.1.4
http_parser: 2.8.0
openssl: 1.1.1c
cldr: 35.1
icu: 64.2
tz: 2019a
unicode: 12.1
```