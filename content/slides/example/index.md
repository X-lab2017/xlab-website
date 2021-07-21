---
title: Slides
summary: An introduction to our website.
authors: []
tags: []
categories: []
date: "2019-02-05T00:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

# How to read a book on our website

[GitHub](https://github.com/gonggongjohn/CKAS) | [Website](https://gonggongjohn.github.io/ckas-website/)

---

## Find your misunderstanding

- Find a book you want to read
- Find a knowledge point while reading
- Clik it


---

## Show

We will show the result on the second screen

Press `Space` to play!

{{% fragment %}} Book {{% /fragment %}}
{{% fragment %}} **|** {{% /fragment %}}
{{% fragment %}} Result {{% /fragment %}}

---


## Our Result

We will show you:

- The definition
- The example which fit well to the user
- The application

---

## Design Map

![avatar](slide_img.png)

---

## How we make it

There are some of our code

```python
  model_config = Dict(model_config)
      backbone_type = model_config.backbone.pop('type')
      neck_type = model_config.neck.pop('type')
      head_type = model_config.head.pop('type')
      self.backbone = build_backbone(backbone_type, **model_config.backbone)
```
---

# Questions?

[Ask](https://spectrum.chat/academic)

[Documentation](https://sourcethemes.com/academic/docs/managing-content/#create-slides)
