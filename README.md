# duck2/libsoldout

This fork is a "make and go" version of Natacha Porté's Markdown parser [libsoldout][0]. Most of the documentation, LaTeX and nroff renderers and orbweaver-y build system is removed.

## Compile

`make` if you want a local binary. You can also run `sudo make install` if you would like a systemwide installation. If you are using something other than Debian, make sure to take a look at the Makefile.

## Run

```
$ ./mkd2html [file]
```

[0]: https://github.com/faelys/libsoldout
