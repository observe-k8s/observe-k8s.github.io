# Observe k8s WG Website

This directory contains a [Hugo](https://gohugo.io) web site.

Add content by adding Markdown files to directories in [./content](./content).

Update layouts for each content type in [./layouts](./layouts/).

Configuration is set in [config.toml](./config.toml).

## Setting up a local dev instance

To set up a local dev environment make sure you have [Hugo Extended](https://gohugo.io/installation/linux/#editions) and [npm](https://www.npmjs.com/) installed, then run the following:

```bash
git clone git@github.com:observe-k8s/observe-k8s.github.io.git
cd observe-k8s.github.io
git submodule update --init --recursive
npm install
```

You can then run the site using `hugo server`.
