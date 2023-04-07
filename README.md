# VirGO

Virtual Desktop Manager for Windows.

## Features

- Resource friendly, exe is lss 10kb on disk and uses lss 1mb memory while running.
- 9 virtual desktops (more if you change a constant and recompile the code).

## Install

[Download here].

[Download here]: https://github.com/kitty-panics/virgo/releases

## Usage

| Keyboard shortcuts       | Describe                                    |
|:-------------------------|:--------------------------------------------|
| `Alt + Ctrl  + 1…9`      | Changes to desktop 1…9                      |
| `Alt + Shift + 1…9`      | Moves active window to desktop 1…9          |
| `Alt + Ctrl + Shift + q` | Exits the program                           |
| `Alt + Ctrl + Shift + s` | Starts/Stops handling of other hotkeys      |
| `Alt + Ctrl + Shift + p` | Pin active window (makes it always visible) |

## Build

The nerds can build it with:

1. `git clone https://github.com/kitty-panics/virgo`
2. `cd virgo`
3. `make`

If you do not have [gcc]/[make] installed you can change that doing following:

1. Go to ***https://www.msys2.org/*** and install it according to the instructions there.
2. Open **MSYS2** shell and install `mingw-w64-i686-gcc` and `mingw-w64-i686-make` using **pacman**.
3. Duplicate ***msys32\mingw32\bin\mingw32-make.exe*** and name it ***make.exe***.
4. Open **MinGW32** shell and perform `make` operation.

[gcc]: https://www.gnu.org/software/gcc/
[make]: https://www.gnu.org/software/make/
