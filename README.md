# Tukan

A light theme for Zola adapted from Pelican.

[Live Preview](https://salif.github.io/zola-themes-collection/demo/tukan/)

![Screenshot](https://codeberg.org/salif/tukan/raw/branch/master/screenshot.png)

## Installation

You can add the theme as a submodule :

```bash
git submodule add --name tukan https://codeberg.org/salif/tukan.git themes/tukan
```

and enable the theme in your `config.toml`

```toml
theme = "tukan"
```

## Usage

You can personalize the following options in your `config.toml`:

```toml
title = ""
description = ""
generate_feeds = true

[extra]
title_pic = "/favicon.ico"
copyright = """Content under <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA</a> Licence"""
site_source = "https://github.com/example/example"
```

Categories will be added to the menu, and all articles from categories with

```toml
transparent = true
```

will be listed in the home page.
