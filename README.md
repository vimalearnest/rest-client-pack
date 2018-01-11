rest-client-pack
================

rest client pack based on https://github.com/pashky/restclient.el

# install

Once you clone the repo, go to the repo directory

```bash
$ git submodule init
$ git submodule update
```
In your `.emacs-live.el` add this snippet:
```elisp
(live-add-packs '("/path/to/rest-client-pack"))
```
