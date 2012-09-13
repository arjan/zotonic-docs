zotonic-docs
============

Zotonic documentation, as it should be.


Building the docs
=================

You need to run `make stubs` to generate some stub documents to pull in all doc-* from the modules/ tree.
Also, the generation needs to know where it can find the zotonic sources, which should be defined by the ZOTONIC_SRC environment variable (absolute path, please).

When the stubs are in place, build the html docs by running:

```
  $ make html
```

`make help` is there to guide you to what other targets are available.
