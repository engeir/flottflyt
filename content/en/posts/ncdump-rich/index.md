---
categories: ["Projects"]
contributors: ["Eirik Rolland Enger"]
date: 2022-07-16T22:28:55-06:00
description: "Introducing Doks, a Hugo theme helping you build modern documentation websites that are secure, fast, and SEO-ready  by default."
excerpt: "Pretty-print a preview of netCDF files using Rich"
homepage: true
images: ['nnn-demo.png']
lastmod: 2020-11-04T09:19:42+01:00
lead: "Introducing Doks, a Hyas theme build by the creator of Hyas. Doks helps you build modern documentation websites that are secure, fast, and SEO-ready  by default."
link: "https://ncdump-rich.readthedocs.io/"
pinned: true
tags: [python, CLI]
title: "Rich NcDump"
weight: 50
---

<!-- # Rich NcDump  -->

**Rich NcDump** is a repository made to be able to quickly preview `netCDF` files. It is
useful when you just want to see the metadata, and it is packaged with `pip`!

To install, you can simply do

```bash
pip install ncdump-rich
```

or even better, by using [`pipx`](https://github.com/pypa/pipx) which installs it in a
nice, isolated environment:

```bash
pipx install ncdump-rich
```

If you are like me and you think browsing through your files is a lot easier in a
terminal file manager compared to Finder, Nautilus and so on, then this previewer
fits perfectly into the previwing plugins that exists for for example
[nnn](https://github.com/jarun/nnn) and [lf](https://github.com/gokcehan/lf).

````bash=10
nc) fifo_pager ncdump-rich -i "$1" ;;
``````

![ncdump-rich-example](https://raw.githubusercontent.com/engeir/ncdump-rich/main/demo/nnn-demo.png)