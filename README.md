Heroku Buildpack: MPlayer
=========================

This is a Heroku Buildpack to use [MPlayer](http://www.mplayerhq.hu/).


Usage
-----

With [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi),

```
$ heroku config:add BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git

$ cat .buildpacks
https://github.com/heroku/heroku-buildpack-ruby.git
https://github.com/a2ikm/heroku-buildpack-yasm.git
https://github.com/a2ikm/heroku-buildpack-mplayer.git
```
