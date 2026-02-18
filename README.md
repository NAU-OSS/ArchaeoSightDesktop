# ArchaeoSightDesktop

ArchaeoSight is a cross-platform mobile application built to assist archaeologists in the field by integrating data from pXRF spectrometers, GPS, and image analysis. It leverages machine learning to predict potential anthropogenic hotspots and enables offline-first functionality to ensure usability in remote locations. Developed in Flutter, ArchaeoSight aims to modernize how field data is collected, analyzed, and visualized.

ArchaeoSightDesktop is meant to serve as a Python rewrite of the mobile app, allowing for direct integration with Python's rich supply of ML libraries, as well as Python's kriging libraries. Unlike the mobile app, the desktop version will allow users to train their own models and upload them to the central model hub, download other models, as well as use the built in kriging functionality. 

The two model formats supported initially are:

- **Gradient Boosted Decision Trees**
- **Autoencoders + HDBSCAN**

---

# Installation

## 1. Install Python

ArchaeoSightDesktop requires **Python 3.10+** (recommended: 3.10 or 3.11 for maximum compatibility with ML libraries).

---

## Windows

### Steps

1. Go to: https://www.python.org/downloads/
2. Click **Download Python (latest stable version)**.
3. Run the installer.
4. ✅ **IMPORTANT:** Check **“Add Python to PATH”**.
5. Click **Install Now**.
6. Verify installation:
   ```bash
   python --version

---

## Linux

### Ubuntu / Debian

```bash
sudo apt update
sudo apt install python3 python3-venv python3-pip
```

### Fedora

```bash
sudo dnf install python3 python3-pip
```

### Arch

```bash
sudo pacman -S python
```

Verify:

```bash
python3 --version
```

---

## macOS

### Option 1: Official Installer

1. Visit: [https://www.python.org/downloads/macos/](https://www.python.org/downloads/macos/)
2. Download the macOS installer.
3. Run the `.pkg` file.
4. Verify:

   ```bash
   python3 --version
   ```

### Option 2: Homebrew (Recommended for developers)

```bash
brew install python
```

---

# 2. Clone the Repository

```bash
git clone https://github.com/your-org/ArchaeoSightDesktop.git
cd ArchaeoSightDesktop
```

---

# 3. Create a Virtual Environment

Using a virtual environment keeps project dependencies isolated.

## Step 1 — Create venv

### Windows

```bash
python -m venv venv
```

### Linux / macOS

```bash
python3 -m venv venv
```

---

## Step 2 — Activate venv

### Windows (PowerShell)

```bash
venv\Scripts\Activate.ps1
```

### Windows (cmd)

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

You should now see `(venv)` in your terminal prompt.

---

# 4. Install Dependencies

Ensure `requirements.txt` exists in the root directory.

Then run:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

# 5. Run the Application

```bash
python main.py
```

---

# Usage

## Importing pXRF Data

*TODO*

---

## Training a Gradient Boosted Model

*TODO*

---

## Training Autoencoder + HDBSCAN Model

*TODO*

---

## Running Kriging Interpolation

*TODO*

---

## Uploading Model to Hub

*TODO*

---

## Downloading Model from Hub

*TODO*

---

# Model Format Specifications

*TODO*

---

# Contributing

*TODO*

---

# License

*TODO*

```
