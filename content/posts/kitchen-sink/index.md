---
title: "Kitchen Sink: Blowfish Features Demo"
date: 2023-10-27
draft: false
description: "A reference guide to all the cool features available in the Blowfish theme."
tags: ["demo", "reference", "markdown"]
categories: ["Tutorials"]
# Feature image for the article listing
image: "https://picsum.photos/id/1015/800/400"
showTableOfContents: true
---

This is a **kitchen sink** post. Keep this file in your draft folder to copy-paste snippets whenever you need them!

## 1. Alerts & Callouts
Blowfish has built-in shortcodes for highlighting text.

{{< alert icon="circle-info" >}}
**Info Alert:** This is good for general notes.
{{< /alert >}}

{{< alert icon="triangle-exclamation" cardColor="#e63946" iconColor="#1d3557" >}}
**Warning Alert:** Watch out! This uses custom colors.
{{< /alert >}}

## 2. Buttons & Badges
Great for calls to action or download links.

**Standard Button:**
{{< button href="https://google.com" target="_blank" >}}
Go to Google
{{< /button >}}

**Badges:**
I am a sentence with a {{< badge >}}New{{< /badge >}} badge and a {{< badge color="indigo" >}}Cool{{< /badge >}} badge.

## 3. Image Gallery
Blowfish automatically arranges images into a grid.

{{< gallery >}}
  <img src="https://picsum.photos/id/10/600/400" class="grid-w33" />
  <img src="https://picsum.photos/id/20/600/400" class="grid-w33" />
  <img src="https://picsum.photos/id/30/600/400" class="grid-w33" />
{{< /gallery >}}

## 4. Code Blocks
Standard markdown code highlighting works perfectly.

```python
def hello_world():
    print("Hello, Blowfish!")
    return True
```

## 5. Mermaid Charts
You can draw diagrams directly in markdown.

{{< mermaid >}}
graph LR;
    A[Start] --> B{Error?};
    B -- Yes --> C[Fix it];
    C --> D[Republish];
    B -- No --> D[Publish];
{{< /mermaid >}}

## 6. Typewriter Effect
A cool animation for text.

{{< typeit >}}
This text is being typed... 
Wait for it... 
**Done!**
{{< /typeit >}}

## 7. Timeline
Perfect for "About Me" pages or changelogs.

{{< timeline >}}
  {{< timelineItem icon="github" header="Created Repo" badge="2022" >}}
  Initial commit to the repository.
  {{< /timelineItem >}}
  
  {{< timelineItem icon="star" header="First Release" badge="2023" >}}
  Released version 1.0 to the public.
  {{< /timelineItem >}}
{{< /timeline >}}

## 8. GitHub Card
Showcase a repository automatically.

{{< github repo="nunocoracao/blowfish" >}}

## 9. YouTube Video
Embed videos responsively.

{{< youtube id="dQw4w9WgXcQ" >}}

---