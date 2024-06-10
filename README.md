# st - simple terminal

**st** configuration by steguiosaur

st is a simple terminal emulator for X which sucks less.

## Requirements

In order to build st you need the Xlib header files.

## Installation

Edit `config.mk` to match your local setup (st is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```console
make clean install
```

## Patches

Visit st patches at [https://st.suckless.org/patches/](https://st.suckless.org/patches/)

```console
patch -p1 < st-patch.diff
```

- `st-0.8.5-autocomplete-20220327-230120.diff`
- `st-anysize-0.8.1.diff`
- `st-bold-is-not-bright-20190127-3be4cf1.diff`
- `st-clipboard-0.8.3.diff`
- `st-delkey-20201112-4ef0cbd.diff`
- `st-glyph-wide-support-20230701-5770f2f.diff`
- `st-line_snap_delimiter-3bd7e43.diff`
- `st-moonfly-0.8.2.diff`
- `st-scrollback-20210507-4536f46.diff`
- `st-scrollback-mouse-20220127-2c5edf2.diff`
- `st-scrollback-mouse-altscreen-20220127-2c5edf2.diff`
- `st-scrollback-mouse-increment-0.8.2.diff`
- `st-scrollback-ringbuffer-0.8.5.diff`
