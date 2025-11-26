# Open 100 Terminal Windows -- Python Script

This repository contains a simple Python script that opens **100 Command
Prompt windows** on Windows machines.\
It is mainly for **testing**, **fun experiments**, or **educational
purposes**.

## 🚀 Usage

### 1. Download the script

File: `open_100_terminals.py`

### 2. Run it

Open Command Prompt and run:

``` bash
python open_100_terminals.py
```

This will open **100 CMD windows**, each launched with a short delay to
avoid freezing the system.

## ⚠️ Warning

Running this script will open *a lot* of terminal windows at once.\
It may:

-   Slow down your computer\
-   Use high CPU\
-   Make the system lag temporarily

Use responsibly.

## 🧩 Code

``` python
import os
import time

for i in range(100):
    os.system("start cmd")
    time.sleep(0.05)
```

## 📁 Files Included

  ----------------------------------------------------------------------------
  File                        Description
  --------------------------- ------------------------------------------------
  **open_100_terminals.py**   Python script that opens 100 terminal windows

  **README.md**               Documentation
  ----------------------------------------------------------------------------

## 📜 License

This project is free to use and modify.
