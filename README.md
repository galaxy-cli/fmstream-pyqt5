# fmstream-pyqt5
A minimal web browser application using PyQt5 and PyQtWebEngine that loads the streaming site [http://nossl.fmstream.org/index.php?c=FT](https://nossl.fmstream.org/index.org/index.php?c=FT).

---

## Features

- Lightweight desktop browser window
- Loads predefined radio streaming URL
- Automatically checks for required Python packages and installs them if missing

---

## Requirements

- Python 3.x
- The script requires the following Python packages:
  - ```PyQt5```
  - ```PyQtWebEngine```

The script automatically checks for these dependencies on startup and installs them if they are not already present.

---

## Installation

No manual installation of dependencies is required if running the script directly, as it self-installs missing packages.

Alternatively, to install dependencies manually:

```
pip install PyQt5 PyQtWebEngine
```

---

## Usage

Run the script with Python:

```
python fmstream-pyqt5.py
```

This will open a window titled "FMSTREAM" loading the streaming radio site.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Author & Contact

**galaxy-cli**

GitHub: [https://github.com/galaxy-cli/fmstream-pyqt5](https://github.com/galaxy-cli/fmstream-pyqt5)
