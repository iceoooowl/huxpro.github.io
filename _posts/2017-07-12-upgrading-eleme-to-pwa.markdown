---
layout:       post
title:        "Test"
subtitle:     "Test post"
date:         2017-07-12 12:00:00
author:       "ZhangYao"
header-img:   "img/in-post/post-eleme-pwa/eleme-at-io.jpg"
header-mask:  0.3
catalog:      true
multilingual: true
tags:
    - 前端开发
    - JavaScript
    - PWA
---

<!-- Chinese Version -->
<div class="zh post-container">
    {% capture about_zh %}{% include posts/2017-07-12-upgrading-eleme-to-pwa/zh.md %}{% endcapture %}
    {{ about_zh | markdownify }}
</div>

<!-- English Version -->
<div class="en post-container">
    {% capture about_en %}{% include posts/2017-07-12-upgrading-eleme-to-pwa/en.md %}{% endcapture %}
    {{ about_en | markdownify }}
</div>
