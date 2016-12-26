# libduck2/libsoldout

This fork is a "make and go" version of Natacha Porté's Markdown parser [libsoldout][0]. Most of the documentation, LaTeX and troff renderers and orbweaver-y build system is removed.

## Compile

`make` if you want a local binary. You can also run `sudo make install` to copy the resulting `mkd2html` binary to the PREFIX mentioned in the Makefile.

## Run

```
$ ./mkd2html [file]
```

[0]: https://github.com/faelys/libsoldout
