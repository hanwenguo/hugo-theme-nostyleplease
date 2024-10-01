+++
title = 'Test TOC, deatails and styles'
date = 2024-08-18T13:34:54+02:00
draft = true
toc = true
tocBorder = true
+++

## Table of Content
### What it is?
TOC is the box you see at the very top of this post. It may be framed (or not).
### How to enable TOC?
To enable it, all you need to do when creating a new post at the very top is to insert the code:
```toml
toc = true
tocBorder = true
```
You can of course find this post (../themes/nostyleplease/content/posts/test-toc-and-details.md) and open in editor to see how it's working.

## Details
### What it is?
It's HTML standard sadly not supported native by markdown. But this theme support it anyway. So... sometimes you want to hide something.
{{< details summary="Click me" >}}
A lot of text or something else.
{{< /details >}}
### How to use "Details"?
Well you need to inspect this post and see by yourself. It's very easy. Take look at ../themes/nostyleplease/content/posts/test-toc-and-details.md.

## Styles
Okey. So if you want to change color-theme you can:
- go to ../themes/nostyleplease/config.toml and find:

  ```toml
  appearance = "auto"
  ```
  you can change it to 2 predefined styles: **light** and **dark**. It can be also set to **auto** and the color scheme will match the user's system style.
- you can add new style or modify **auto** option, just edit CSS in ../themes/nostyleplease/assets/main.scss :-). It's easy, if you are able to operate Hugo - you can do it.
