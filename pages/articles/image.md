---
title: Image
tags: [image]
keywords: image, figcaption, caption
last_updated: August 30, 2016
summary: "How to work with images"
sidebar: mydoc_sidebar
permalink: articles-image.html
folder: articles
---

### 1. Images in general
When adding images it normaly looks like this

```html
  <figure> <!-- We should always wrap the images in figure so it follows the latest HTML standards -->
    <img src="..."> <!-- This is the actual image -->
    <figcaption>
      <!-- This is the caption, reference to the image, note that this could be a link -->
    </figcaption>
  </figure>
```

### 2. Images with caption
When inserting images you always get the option of adding a caption to the image. However if you miss to do this when inserting the image you can always add it later on.
Before:

```html
  <figure>
    <img src="...">
  </figure>
```

After:

```html
  <figure>
    <img src="...">
    <figcaption>
      <a href="http://the-url-to–what-ever" target="_blank">
        Here you should write your figcaption
      </a>
    </figcaption>
  </figure>
```

### 3. Images without caption
In those cases where you don't have any caption you should always remove the caption. Otherwise Instant Articles will complain about it when publishing it to IA.


```html
  <figure>
    <img src="...">
    <figcaption> <!-- Remove this and everything below until the close of this tag -->
    </figcaption> <!-- Remove this -->   
  </figure>
```

After:

```html
  <figure>
    <img src="...">
  </figure>
```