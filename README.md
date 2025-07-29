# momoisay
*A CLI program written in C featuring talking Saiba Momoi from Blue Archive!!!*

[![License](https://img.shields.io/badge/license-GPL--3.0-blue)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.1.1-green)]()

---

## Preview

Example of animated usage

![Demo](preview.gif)

## Features
- Talking ASCII art of Momoi
- Animated ASCII art of Momoi
- Freestyle changing animation of Momoi

## Installation

#### disclaimer
Sometimes the precompiled binaries are not the latest version as the release. If you want to make sure that you got the latest version, you can built it from source. You can check the versions of the compiled binaries in the `/bin` folders.

### Linux
```bash
git clone https://github.com/jimmy-linux/Momoisay.git
cd Momoisay
sudo sh ./install/linux.sh
```
### MacOS
```bash
git clone https://github.com/jimmy-linux/Momoisay.git
cd Momoisay
sudo sh ./install/mac.sh
```
### Build from source (Latest Version)
```bash
git clone https://github.com/jimmy-linux/Momoisay.git
cd Momoisay
make
```

## Usage
```bash
momoisay --help         # Show help
momoisay <text>         # Simple Usage
momoisay -a             # Animated Momoi with no text bubble (default version 1)
momoisay -a <version>   # Animated Momoi with no text bubble (default version 1)
momoisay -f             # Freestyle animations (This is pretty cool for ricing)
momoisay -a -k 0.2      # Set frame change delay multiplier to 0.2 (run 5 times
                        # faster)
```

## File Structure
```
repo/
├── bin/ 
│    ├── linux/
│    │   ├── version.txt
│    │   └── momoisay
│    └── mac/
│        ├── version.txt 
│        └── momoisay
├── install/
│    ├── mac.sh
│    └── linux.sh
├── src/
│    ├── art/
│    │   ├── art.c
│    │   └── art.h
│    └── momoisay.c
├── Makefile
├── LICENSE
├── preview.gif
└── README.md
```
