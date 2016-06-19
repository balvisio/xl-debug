xl-debug
========

Small utility that

  1. Creates the Xen guest in paused state
  2. Attaches the gdbsx server to the Xen guest
  3. Allows you to connect gdb and waits for it to exit
  4. Destroys the Xen guest


## Installation
We assume you have [gdbsx installed](https://unigornel.org/doku.php?id=development:debugging).


```
sudo install -m 0755 xl-debug /usr/local/bin/xl-debug
```

## Usage

```
# xl-debug -h
# xl-debug -f config.xen -n minios
```
