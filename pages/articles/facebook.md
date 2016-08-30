---
title: Facebook embeds
tags: [embeds]
keywords: facebook, post, facebook post, facebook video, video, embedd
last_updated: August 30, 2016
summary: "How to embed different facebook types"
sidebar: mydoc_sidebar
permalink: articles-facebook.html
folder: articles
---

General
=
Embedding facebook posts is pretty straight forward. **Never** load any script as we already do this.


Embed Facebook Posts
-

### 1. Start with the post ###
Click on the arrow in the upper right corner of the post you want to embed.
{% include image.html file="facebook/post-step-1.png" alt="Jekyll" caption="" %}

### 2. Select Embed ###
Click on embed (might be in your language as in the image, ie swedish.)
{% include image.html file="facebook/post-step-2.png" alt="Jekyll" caption='In this case its "bädda in"' %}

### 3. Iframe code ###
Select the iframe code inside the input field and copy it ```ctrl+c```
{% include image.html file="facebook/post-step-3.png" alt="Jekyll" caption='' %}

### 4. Insert the code into the article (optional) ###
When inserting it you can help the system by wrapping the code with a ```<figure>``` element.

Before:

```html
  <iframe src="https://www.facebook.com/..." width="500" height="482" style="border:none; overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>
```

After:

```html
  <figure class="op-interactive"> <!-- Add this -->
    <iframe src="https://www.facebook.com/..." width="500" height="482" style="border:none; overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>
  </figure> <!-- Don't forget to close the tag! -->
```


## Facebook Videos

### 1. Get started ###
Start by clicking uppe right arrow on the video.
{% include image.html file="facebook/video-step-1.png" alt="Jekyll" caption='Click on embed, in this case its "Bädda in"' %}

### 2. Get started ###
Select the iframe code and copy it, ```ctrl+c``. You can select the "Include full post" option if you want to. 
{% include image.html file="facebook/video-step-2.png" alt="Jekyll" caption='Click on embed, in this case its "Bädda in"' %}

### 3. Insert the code into the article (optional) ###
When inserting it you can help the system by wrapping the code with a ```<figure>``` element.

Before:

```html
  <iframe src="https://www.facebook.com/..." width="400" height="400" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true" allowFullScreen="true"></iframe>
```

After:

```html
  <figure class="op-interactive"> <!-- Add this -->
    <iframe src="https://www.facebook.com/..." width="400" height="400" style="border:none; overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>
  </figure> <!-- Don't forget to close the tag! -->
```