---
title: Hexo Commands
date: 2019-10-16 15:09:01
tags:
---

# Hexo Commands

## init

```bash
hexo init [folder]
```

```bash
hexo init
```

```bash
hexo init [folder] --no-install
```

## new

```bash
hexo new [layout] <title>
```

```bash
hexo new "Title"
```

```bash
hexo new "Title" --debug
```

## generate

```bash
hexo generate
```

```bash
hexo generate --deploy
```

```bash
hexo generate --deploy --debug
```

## server

```bash
hexo server
```

```bash
hexo server --open
```

```bash
hexo server --open --debug
```

## deploy

```bash
hexo deploy
```

```bash
hexo deploy --generate
```

```bash
hexo deploy --generate --debug
```

## clean

```bash
hexo clean
```

```bash
hexo clean --debug
```

## list

```bash
hexo list
```

```bash
hexo list page
```

```bash
hexo list post --debug
```

```bash
hexo list post | pbcopy
```

```
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

```bash
hexo list route --debug
```

```bash
hexo list route | pbcopy
```

```
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

```bash
hexo list tag
```

```bash
hexo list category
```

## version

```bash
hexo version --debug
```

```bash
hexo version | pbcopy
```

```
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