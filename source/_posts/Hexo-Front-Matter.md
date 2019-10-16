---
title: Hexo-Front-Matter
date: 2019-10-16 16:17:03
updated: 2019-10-16 16:19:21
comments: true
tags:
  - Hexo
  - Front matter
categories:
  - [Hexo]
keywords:
  - Hexo
  - Front matter
---

# Hexo Front Matter

## scaffolds/post.md

```bash
cat scaffolds/post.md | pbcopy
```

```yaml
---
title: {{ title }}
date: {{ date }}
updated: {{ date }}
comments: true
tags:
  - no-tag
categories:
  - [parent-category, child-category]
keywords:
  - no-keyword
---
```