# phrack-dark

Temporary repo for hosting phrack patch files.

## How to apply the patches

```console
# For the 'style.css' file
patch -p1 < style.css.patch

# For the 'Makemd.py' file
patch -p1 < Makemd.py.patch
```

> __Make sure to backup original files before applying the patches!__
