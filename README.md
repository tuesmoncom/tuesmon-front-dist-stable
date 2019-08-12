# Tuesmon Front #

![Kaleidos Project](http://kaleidos.net/static/img/badge.png "Kaleidos Project")

This repo is a compiled versión of https://github.com/tuesmoncom/tuesmon-front

## Installation ##

* Clone the repo
* Expose the `dist` directory under a static file web server
* Rename dist/js/conf.example.json to conf.js if you want to change settings

More information about the different installation methods (production, development, vagrant, docker...) can be found here http://tuesmoncom.github.io/tuesmon-doc/dist/#_installation_guide.


## For Devs ##

To regenerate branches ```master``` and ```stable```

```
git checkout master; node dist.js master
git checkout stable; node dist.js stable
```

## Community ##

[Tuesmon has a mailing list](http://groups.google.com/d/forum/tuesmoncom). Feel free to join it and ask any questions you may have.

To subscribe for announcements of releases, important changes and so on, please follow [@tuesmoncom](https://twitter.com/tuesmoncom) on Twitter.
