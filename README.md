# iBoot64Patcher
*A universal iboot patcher for arm64 devices*

## Why do I restored this?
*Because it's more lightweight compared to [ra1nsn0w](https://github.com/tihmstar/ra1nsn0w)*

### How to compile?
**Requires: `libgeneral` `libinsn` `img3tool` `img4tool` `libpatchfinder`**

```Bash
$ git clone https://github.com/mast3rz3ro/iBoot64Patcher-tihmstar
$ cd iBoot64Patcher-tihmstar
$ ./autogen.sh
$ make
$ make install
```

* Or you can automatically compile and install it via:
```Bash
u="https://raw.githubusercontent.com/mast3rz3ro/libimobiledevice-builder/refs/heads/main/build-utils.sh" && \\
curl -sL "$u" | bash -s -- "iboot64patcher-tihmstar" --no-virtual
```

### Credits
**Original Author: @tihmstar and thanks to the contributors.**
