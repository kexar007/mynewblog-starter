---
title: "The Beauty of Mountains"
date: 2023-11-30
draft: false
description: "A demonstration of how featured images look in the Blowfish theme."
tags: ["nature", "demo"]
categories: ["Photography"]

# --- FEATURED IMAGE SETUP ---
# Option 1: Use an online URL (easiest for testing)
#image: "https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80"

# Option 2: Use a local file (Best for production)
# 1. Create a folder: content/posts/featured-demo/
# 2. Move this .md file inside it (content/posts/featured-demo/index.md)
# 3. Add an image named "featured.jpg" to that folder.
# 4. Delete the 'image:' line above. Blowfish finds "featured.jpg" automatically.
# ----------------------------

showTableOfContents: true
---

This post demonstrates how a **Featured Image** appears in Blowfish. 

If you look at the **homepage** or the **blog list**, you will see the mountain image displayed above this post's title. When you open this page, the image is displayed as a large hero banner at the top (depending on your layout settings).

## Why use Featured Images?

1. **Visual Appeal:** They make your blog index look professional.
2. **Social Media:** When you share this link on Twitter or LinkedIn, this image will show up in the preview card.
3. **Context:** It sets the mood for the article before the reader starts reading.

## How to switch to a local image?

Right now, this post is using a URL from Unsplash. To make it local:

1. Create a folder named `featured-demo` inside `content/posts/`.
2. Rename this file to `index.md` and move it inside that folder.
3. Paste your own image into that folder and name it `featured.jpg`.
4. Remove the `image: "..."` line from the top of this file.

That's it! Blowfish loves "Page Bundles" (folders with an `index.md` and images inside).