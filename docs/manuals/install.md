# Installation Guide

## Prerequisites
- Python 3.8 or higher (includes tkinter)

## Steps

### 1. Clone the repository
```bash
git clone <repository-url>
cd futurdata-thesis
```

### 2. Run the application
```bash
python run_app.py
```

No additional dependencies needed!

## Verify Python has tkinter
```bash
python -c "import tkinter; print('OK')"
```

## Troubleshooting

### "No module named 'tkinter'"

**Ubuntu/Debian:**
```bash
sudo apt install python3-tk
```

**Windows:**
Reinstall Python from python.org (tkinter is included by default)

**macOS:**
```bash
brew install python-tk
```
