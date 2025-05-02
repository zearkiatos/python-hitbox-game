# Description

This is a python 🐍 game 🎮 demo with pygame. This is the hitbox game to demo advance gameloop and scenes concept

# Made with

[![Python](https://img.shields.io/badge/python-2b5b84?style=for-the-badge&logo=python&logoColor=white&labelColor=000000)]()

# How to run

## How to install

### How to install in mac 🍎 and linux 🐧

```sh
$ make install

#or

$ sh run.sh; install
```

### How to install in Windows 🪟

```sh
$ sh run.sh; install
```

### Only with python and for all systems

```sh
$ pip3 install -r requirements.txt
```

## How to run the game 🎮

### How to run in mac 🍎 and linux 🐧

```sh
$ make run

#or

$ sh run.sh; run-web
```

### How to run in Windows 🪟

```sh
$ sh run.sh; run-web
```

### Only with python and for all systems

```sh
$ python3 main.py
```

## How to run the game 🎮 on a web 

### How to run in mac 🍎 and linux 🐧 on a web

```sh
$ make run-web

#or

$ rm -rf build
$ mkdir -p build/web
$ cp -rf assets build/web || true
$ cp -rf esper build/web || true
$ PYGBAG=1 pygbag main.py || echo "pygbag build completed"
```