# RAKwireless Document Center [![Build Status](https://travis-ci.org/RAKwirelessDev/rakwireless-docs.svg?branch=master)](hhttps://travis-ci.org/RAKwirelessDev/rakwireless-docs)
This is a [VuePress](https://vuepress.vuejs.org/) site which [Travis](https://travis-ci.org/TheThingsNetwork/docs) automatically tests and builds to the [docs-deploy](https://github.com/RAKwirelessDev/rakwireless-docs/tree/docs-deploy) branch to be served via [Laravel Forge](https://forge.laravel.com/) as a static site.

# Documentation
Check out our docs at https://docs.rakwireless.com/.

# Install
```bash
# install globally
yarn global add vuepress # OR npm install -g vuepress

# start writing
vuepress dev docs

# build
vuepress build docs
```