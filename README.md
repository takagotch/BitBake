### bitbake
---
https://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html

```py
src_uri = (d.getVar('SRC_URI', True) or "").split()
fetcher = bb.fetch2.Fetch(src_uri, d)
fetcher.download()

rootdir = l.getVar('WORKDIR', True)
fetcher.unpack(rootdir)

```

```
```

```
```


