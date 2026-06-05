# How to build:

sudo apt install g++-aarch64-linux-gnu
aarch64-linux-gnu-g++ -Wall -Wextra -std=c++17 -O2 main.cpp -o calculator
### Note that this builds for linux on arm64, made to run on a Raspberry Pi Zero 2 W

# How to run:

./calculator

place in /bin/ to be able to run system wide

# Features:

Addition
Subtraction
Multiplication
Division
Supports 2 numbers
Only supports integers for now, floating point support will come in a later update
