# Introduction
This is a custom fork of the popular
[Vim-markdown](https://github.com/plasticboy/vim-markdown) plugin. As of now, this fork is
simply a way of tracking personal changes to the default functionality of the base plugin
and allows me to quickly set theses changes across multiple systems.

# Changes

1. Remove `indent` file. This file messes with automatic indentation of lists; I'm not
   really sure why the plugin attempts to do this. Vim can handle this indentation
   perfectly on its own.
2. Add support for wiki-style links (`[[<link>]]` syntax). This includes conceal and
   highlight modifications. Code alterations inspired by [this pull
   request)(https://github.com/plasticboy/vim-markdown/pull/478).
