---
title: "Layout: Header Video"
header:
  video:
    id: -PVofD2A9t8
    provider: youtube
categories:
  - Layout
  - Uncategorized
tags:
  - vedio
  - layout
---
# 食替

目前多数日麻平台采用的规则是**禁止任何形式的食替**。

- 此类平台包括但不限于：天凤、世嘉MJ、雀魂。

原因：吃碰的目的通常是减少向听数，加快和牌速度。但食替行为并没有减少向听数。于是有人认为这种行为“没有意义”、“没有道理”，觉得采取这种行为的人“不是在为了自己和牌而鸣牌，而是在故意妨碍他人和牌”。这种想法一传十十传百，肯定并采用这个规则的人越来越多，也就成了主流规则。

This post should display a **header with a responsive video**, if the theme supports it.

## Settings

| Parameter  | Required     | Description |
|----------  |---------     | ----------- |
| `id`       | **Required** | ID of the video |
| `provider` | **Required** | Hosting provider of the video, either `youtube` or `vimeo` |

### YouTube

To embed the following YouTube video at url `https://www.youtube.com/watch?v=-PVofD2A9t8` (long version) or `https://youtu.be/-PVofD2A9t8` (short version) into a post or page's main content you'd use: 

```liquid
{% raw %}{% include video id="-PVofD2A9t8" provider="youtube" %}{% endraw %}
```

{% include video id="-PVofD2A9t8" provider="youtube" %}

To embed it as a video header you'd use the following YAML Front Matter

```yaml
header:
  video:
    id: -PVofD2A9t8
    provider: youtube
```

### Vimeo

To embed the following Vimeo video at url `https://vimeo.com/212731897` into a post or page's main content you'd use: 

```liquid
{% raw %}{% include video id="212731897" provider="vimeo" %}{% endraw %}
```

{% include video id="212731897" provider="vimeo" %}

To embed it as a video header you'd use the following YAML Front Matter

```yaml
header:
  video:
    id: 212731897
    provider: vimeo
```