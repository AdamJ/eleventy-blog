---
layout: libdoc_page
permalink: configuration/open-graph-image/index.html
eleventyNavigation:
    key: Open Graph image configuration
    parent: Configuration
    title: Open Graph image
    order: 50
title: Open Graph Image - Configuration
description: How to manage Open Graph Image metadata
tags:
    - configuration
    - open-graph-image
    - SEO
---

Available into `_data/libdocConfig.json`:

```json
{
    "ogImageUrl": ""
}
```

The Open Graph Image is a metadata image URL that is displayed when a link to a LibDoc page is shared into a social network. By default, LibDoc configation `ogImageUrl` is used on every page but this parameter can be overridden on each page’s front matter with the same key `ogImageUrl`. Then you can customize each page of your project.