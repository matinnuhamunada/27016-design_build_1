# 27016-design_build_1
Helper script for teaching DTU Course 27016 - Design Build 1

# Usage
Clone this repository

## Installing Spyder in WSL
- Install Spyder in windows: https://github.com/spyder-ide/spyder/releases/latest/download/Spyder_64bit_full.exe
- Go to WSL, [install miniconda and create spyder environment](https://docs.spyder-ide.org/current/faq.html?highlight=run%20cell)
```bash
mamba env create -f env.yml
```
- Start spyder kernel
```bash
python -m spyder_kernels.console --matplotlib="inline" --ip=127.0.0.1 -f=~/remotemachine.json &
```

## Getting started with ESP32
```bash
wget https://micropython.org/resources/firmware/esp32-20220618-v1.19.1.bin
```