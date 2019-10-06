# Valgrind Exercise
[![Build Status](https://travis-ci.org/cunninghamr/cpp-boilerplate.svg?branch=master)](https://travis-ci.org/cunninghamr/cpp-boilerplate)
[![Coverage Status](https://coveralls.io/repos/github/cunninghamr/cpp-boilerplate/badge.svg?branch=master)](https://coveralls.io/github/cunninghamr/cpp-boilerplate?branch=master)
---

## Overview

Using C++ Boilerplate code with some bugs to demonstrate the use of valgrind.

## Install
```
git clone --recursive https://github.com/cunninghamr/cpp-boilerplate
cd <path to repository>
mkdir build
cd build
cmake ..
make
Run tests: ./test/cpp-test
Run program: ./app/shell-app
```
## Valgrind
```
valgrind --leak-check=full ./app/shell-app
```
