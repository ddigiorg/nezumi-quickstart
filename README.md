# Nezumi Quickstart

A template for quickly making a game using [Nezumi](https://github.com/<you>/nezumi).

## Instructions

Requires a C++20 compiler, Git and CMake 3.25+. See the [Nezumi Getting Started](https://github.com/ddigiorg/nezumi/blob/main/docs/getting-started.md) guide for more details.

```sh
git clone git@github.com:ddigiorg/nezumi-quickstart.git
cd nezumi-quickstart
cmake --preset debug
cmake --build --preset debug
./.build/debug/my-game
```

The Nezumi Engine and all of its dependencies are downloaded and built during the first configure.
