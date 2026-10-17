# kilo

A small terminal text editor written in C, in the spirit of [antirez's kilo](https://github.com/antirez/kilo).

Early work in progress. So far it puts the terminal into raw mode, turning off echo and canonical mode, and restores it on exit.

## Build

Requires a C compiler and make, on Linux or macOS.

```bash
make
./kilo
```
