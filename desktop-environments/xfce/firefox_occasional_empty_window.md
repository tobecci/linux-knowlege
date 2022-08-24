[up](./README.md)

# Firefox occasionally showing an empty window in xfce

add the code below to `~/.profile`, the logout and login

```bash
if ! grep -w -q nvidia <(lsmod) ; then export
__EGL_VENDOR_LIBRARY_FILENAMES="/usr/share/glvnd/egl_vendor.d/50_mesa.json"
fi
```