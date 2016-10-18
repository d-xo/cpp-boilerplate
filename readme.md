# C++ Boilerplate

---

## Overview

Simple starter C++ project with:

- cmake
- googletest
- boost
- vscode integration (ycmd / cmaketools)

## Installation

- Checkout the repo (and submodules)
```
$ git clone --recursive https://github.com/xwvvvvwx/cpp-boilerplate.git
```

- Install boost
```
$ cd vendor/boost
$ bash ./bootstrap.sh
$ ./b2
```

## Configuration

- Comes with YouCompleteMe integration preconfigured, but you will need to point vscode to an installation:

```js
// .vscode/settings.json
{
    ...
    "ycmd.path": "<YOUR_PATH_HERE>",
    ...
}
```
