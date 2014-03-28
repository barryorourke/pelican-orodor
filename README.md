pelican-orodor
==============

## Requirements

### Pelican

We use the pelican [assets plugin](https://github.com/getpelican/pelican-plugin/tree/master/assets), which uses the webassets python module:

```
pip install webassets
```

You'll also need to modify your *pelicanconf.py* to include the plugin, something like this should do the job:

```
PLUGIN_PATH = '/path/to/pelican/plugins/directory'
PLUGINS = ['assets']
```

### Bower

We use [bower](http://bower.io) to install bootstrap, font-awesome and the like.

Install *node.js* and *npm* using either your operating systems package manager or download it.

```
npm install bower
bower install
```

### SASS

We use [sass](http://sass-lang.com/) to generate our CSS files.


Install *ruby* using either your operating systems package manager or download it.

```
bundle install
```
