# C++ Boilerplate

---

## Overview

Simple starter C++ project with:
    - cmake
    - googletest
    - vscode integration (ycmd / cmaketools)

## Installation

```
$ git clone --recursive https://github.com/xwvvvvwx/cpp-boilerplate.git
$ cd vendor/YouCompleteMe && ./install.py --all
```

## YouCompleteMe

- Comes with YouCompleteMe integration preconfigured, but you will need to point vscode to an installation:

```js
// .vscode/settings.json
{
    ...
    "ycmd.path": "<YOUR_PATH_HERE>",
    ...
}
```
