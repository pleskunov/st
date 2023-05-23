# st

## Description
This is a personal, experimental build of [st](https://st.suckless.org).
This build is done using [st-flexipatch](https://github.com/bakkeby/st-flexipatch).

## Patches
1. [alpha](https://st.suckless.org/patches/alpha/)
2. [blinking cursor](https://st.suckless.org/patches/blinking_cursor/)
3. [boxdraw](https://st.suckless.org/patches/boxdraw/)
4. [font2](https://st.suckless.org/patches/font2/)
5. [Ligature support](https://st.suckless.org/patches/ligatures/)
6. [scrollback](https://st.suckless.org/patches/scrollback/) with mouse wheel.
7. [xresources](https://st.suckless.org/patches/xresources/)

## Requirements
In order to build st you need the Xlib header files.

## Installation

```bash
git clone https://github.com/pleskunov/st.git
cd st
doas make clean install
```
