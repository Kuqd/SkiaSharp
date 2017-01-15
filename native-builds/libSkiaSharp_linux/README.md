Build libSkiaSharp for linux usage

set up you PATH to the toolchain:

```export PATH=`pwd`/buildtools/toolchain:$PATH```

the toolchain include `gn` and `ninja`.

Now configure your build :

```gn gen out/foo```

and build the default target :

```ninja -C out/foo```
