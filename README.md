# Tukan

A light theme for Zola adapted from Pelican.

![Live Preview](https://salif.github.io/zola-themes-collection/demo/tukan/)

![Screenshot](./screenshot.png)

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

[extra]
title_pic = "/favicon.ico"
license = """Content under <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA</a> Licence"""
```

Categories will be added to the menu, and all articles from categories with

```toml
transparent = true
```

will be listed in the home page.
