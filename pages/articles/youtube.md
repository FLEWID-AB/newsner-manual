---
title: Youtube
tags: [youtube, embed]
keywords: youtube, embed
last_updated: August 30, 2016
summary: "How to embed Youtube"
sidebar: mydoc_sidebar
permalink: articles-youtube.html
folder: articles
---

### 1. Embed code

Before:

```html
  <iframe width="560" height="315" src="https://www.youtube.com/embed/pSd9hiBGoE0" frameborder="0" allowfullscreen></iframe>
```

After:

```html
  <figure class="op-interactive"> <!-- Add this -->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/pSd9hiBGoE0" frameborder="0" allowfullscreen></iframe>
  </figure> <!-- Don't forget to close the tag! -->
```

