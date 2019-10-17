---
title: Hexo Tag Plugins
comments: true
tags:
  - Hexo
categories:
  - - Hexo
    - Learn
keywords:
  - hexo
date: 2019-10-16 16:38:05
updated: 2019-10-17 13:00:51
---

# Hexo Tag Plugins

## Block Quote

### No arguments. Plain blockquote.

```
{% blockquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
{% endblockquote %}
```

{% blockquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
{% endblockquote %}

### Quote from a book

```
{% blockquote David Levithan, Wide Awake %}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{% endblockquote %}
```

{% blockquote David Levithan, Wide Awake %}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{% endblockquote %}

### Quote from an article on the web

```
{% blockquote Hu Zhenghui https://huzhenghui.github.io Hu Zhenghui's Blog %}
Quote from https://huzhenghui.github.io Hu Zhenghui's Blog
{% endblockquote %}
```

{% blockquote Hu Zhenghui https://huzhenghui.github.io Hu Zhenghui's Blog %}
Quote from https://huzhenghui.github.io Hu Zhenghui's Blog
{% endblockquote %}

## Code Block

### A plain code block

```
{% codeblock %}
alert('Hello World!');
{% endcodeblock %}
```

{% codeblock %}
alert('Hello World!');
{% endcodeblock %}

### Specifying the language

```
{% codeblock lang:javascript %}
alert('Hello World!');
{% endcodeblock %}
```

{% codeblock lang:javascript %}
alert('Hello World!');
{% endcodeblock %}

### Adding a caption to the code block

```
{% codeblock Alert %}
alert('Hello World!');
{% endcodeblock %}
```

{% codeblock Alert %}
alert('Hello World!');
{% endcodeblock %}

### Adding a caption and a URL

```
{% codeblock Alert https://developer.mozilla.org/zh-CN/docs/Web/API/Window/alert window.alert %}
alert('Hello World!');
{% endcodeblock %}
```

{% codeblock Alert https://developer.mozilla.org/zh-CN/docs/Web/API/Window/alert window.alert %}
alert('Hello World!');
{% endcodeblock %}

## Backtick Code Block

```
```javascript Alert https://developer.mozilla.org/zh-CN/docs/Web/API/Window/alert window.alert
alert('Hello World!');
``` 
```

```javascript Alert https://developer.mozilla.org/zh-CN/docs/Web/API/Window/alert window.alert
alert('Hello World!');
```

## Pull Quote

这是pullquote right之前的正文，这是pullquote right之前的正文，这是pullquote right之前的正文，这是pullquote right之前的正文，这是pullquote right之前的正文，这是pullquote right之前的正文，这是pullquote right之前的正文，这是pullquote right之前的正文，这是pullquote right之前的正文，这是pullquote right之前的正文，

{% pullquote right %}
这是pullquote right，这是pullquote right，这是pullquote right，这是pullquote right，这是pullquote right，这是pullquote right，这是pullquote right，这是pullquote right，这是pullquote right，这是pullquote right，
{% endpullquote %}

这是pullquote right之后的正文，这是pullquote right之后的正文，这是pullquote right之后的正文，这是pullquote right之后的正文，这是pullquote right之后的正文，这是pullquote right之后的正文，这是pullquote right之后的正文，这是pullquote right之后的正文，这是pullquote right之后的正文，这是pullquote right之后的正文，

这是pullquote left之前的正文，这是pullquote left之前的正文，这是pullquote left之前的正文，这是pullquote left之前的正文，这是pullquote left之前的正文，这是pullquote left之前的正文，这是pullquote left之前的正文，这是pullquote left之前的正文，这是pullquote left之前的正文，这是pullquote left之前的正文，

{% pullquote left %}
这是pullquote left，这是pullquote left，这是pullquote left，这是pullquote left，这是pullquote left，这是pullquote left，这是pullquote left，这是pullquote left，这是pullquote left，这是pullquote left，
{% endpullquote %}

这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，这是pullquote left之后的正文，

## jsFiddle

```plain jsFiddle https://jsfiddle.net/huzhenghui/b7janurh huzhenghui/b7janurh
{% jsfiddle huzhenghui/b7janurh result,js,html,css dark 400 200 %}
```

{% jsfiddle huzhenghui/b7janurh result,js,html,css dark 600 200 %}

## Gist

```plain Gist https://gist.github.com/huzhenghui/c6c2e76e68f92ed4d549f23c390a2397 helloworld.js
{% gist huzhenghui/c6c2e76e68f92ed4d549f23c390a2397 helloworld.js %}
```

{% gist huzhenghui/c6c2e76e68f92ed4d549f23c390a2397 helloworld.js %}

## iframe

```plain iframe https://huzhenghui.github.io Hu Zhenghui's Blog
{% iframe https://huzhenghui.github.io 600 200 %}
```

{% iframe https://huzhenghui.github.io 600 200 %}

## Image

```plain Image https://huzhenghui.github.io/css/images/banner.jpg Banner 
{% img center https://huzhenghui.github.io/css/images/banner.jpg 600 200 "Hu Zhenghui 'Banner'" %}
```

{% img center https://huzhenghui.github.io/css/images/banner.jpg 600 200 "Hu Zhenghui 'Banner'" %}

## Link

```plain Link https://huzhenghui.github.io Hu Zhenghui's Blog
{% link "Hu Zhenghui's Blog" https://huzhenghui.github.io External Title %}
```

{% link "Hu Zhenghui's Blog" https://huzhenghui.github.io External Title %}

## Include Code

### Embed the whole content of test.js

```plain include_code /downloads/code/package.json package.json
{% include_code lang:json package.json %}
```

{% include_code lang:json package.json %}

### Embed line 3 only

```plain include_code /downloads/code/package.json from:3 to:3 package.json
{% include_code lang:json from:3 to:3 package.json %}
```

{% include_code lang:json from:3 to:3 package.json %}

### Embed line 5 to 8

```plain include_code /downloads/code/package.json from:5 to:8 package.json
{% include_code lang:json from:5 to:8 package.json %}
```

{% include_code lang:json from:5 to:8 package.json %}

### Embed line 5 to the end of file

```plain include_code /downloads/code/package.json from:5 package.json
{% include_code lang:json from:5 package.json %}
```

{% include_code lang:json from:5 package.json %}

### Embed line 1 to 8

```plain include_code /downloads/code/package.json to:8 package.json
{% include_code lang:json to:8 package.json %}
```

{% include_code lang:json to:8 package.json %}

## Include Posts

### post_path

```plain post_path /2019/10/16/Hexo-Front-Matter/ Hexo-Front-Matter.md
{% post_path Hexo-Front-Matter %}
```

{% post_path Hexo-Front-Matter %}

### Display title of the post.

```plain post_link /2019/10/16/Hexo-Configuration/ Hexo-Configuration.md
{% post_link Hexo-Configuration %}
```

{% post_link Hexo-Configuration %}

### Display custom text.

```plain post_link /2019/10/16/Hexo-Commands/ Hexo-Commands.md
{% post_link Hexo-Commands 'Hexo Commands' %}
```

{% post_link Hexo-Commands 'Hexo Commands' %}

## Include Assets

### asset_path

```plain asset_path /2019/10/16/Hexo-Tag-Plugins/banner.jpg banner.jpg
{% asset_path banner.jpg %}
```

{% asset_path banner.jpg %}

### asset_img

```plain asset_img /2019/10/16/Hexo-Tag-Plugins/banner.jpg banner.jpg
{% asset_img banner.jpg Banner %}
```

{% asset_img banner.jpg Banner %}

### asset_link

```plain asset_link /2019/10/16/Hexo-Tag-Plugins/banner.jpg banner.jpg
{% asset_link banner.jpg Banner %}
```

{% asset_link banner.jpg Banner %}

## Raw

```plain Raw
Title: {{ title }}

{% raw %}
Title: {{ title }}
{% endraw %}
```

Title: {{ title }}

{% raw %}
Title: {{ title }}
{% endraw %}

## Post Excerpt

```plain "Post Excerpt" /2019/10/16/Hexo-Tag-Plugins/#more More
<!-- more -->
```

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
<!-- more -->
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.