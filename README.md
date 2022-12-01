
Template to include seastar in your c++ project.


# Prerequisite

```
# we use lld to linker

sudo pacman -Sy lld


# these are dependencies of seastar

sudo pacman -Sy lksctp-tools
sudo pacman -Ss yaml-cpp
sudo pacman -Sy ragel
sudo pacman -Sy valgrind

```


# Build

```
mkdir build && cd build

cmake ..
make

./sample

=> print cpu cores number. mine is '8'

```
