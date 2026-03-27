# 🎮 Text Based Game Player — Builds

This repository contains **only the finished public builds** of **Text Based Game Player**.

The source code is kept in a **separate private repository**.

---

## 🚀 What is this?

**Text Based Game Player** is a desktop app for running **text-based games locally**, with no terminal needed during play.

It is designed to:

* run supported game files offline
* display game output inside the app
* let you type responses directly into the app
* make text-based games easier to open and play

---

## ✨ Features

### 🎮 Game Support

* Open and run supported text-based games
* In-app output display
* In-app input box for player commands
* Offline play

### 📂 File & Folder Handling

* Open a game file
* Import a game folder
* Support for a dedicated games folder

### 🎨 Appearance & Accessibility

* Adjustable background colour
* Adjustable text colour
* Colour overlay with tint and opacity
* Adjustable text size
* Optional auto-resize text with window size

### 🖥️ App Experience

* Clean desktop UI
* Resizable window
* No terminal needed for normal use
* Offline-first design

---

## ⚙️ Installation Guide

## 🍎 macOS

### Step 1 — Move the app

Drag **Text Based Game Player.app** into your **Applications** folder.

### Step 2 — Open the app

Try opening it normally first.

### If macOS blocks the app

Right-click the app and choose **Open**, then click **Open** again.

### If macOS says the app is damaged or still will not open

Open **Terminal** and run:

```bash
xattr -cr "/Applications/Text Based Game Player.app"
```

Then try opening the app again.

### Python check on macOS

If a game needs Python and it is not found, check with:

```bash
python3 --version
```

If needed, install Python with Homebrew:

```bash
brew install python
```

---

## 🪟 Windows

### Install and open

Download the Windows build and open the `.exe` or `.msi`.

### If Windows blocks the app

1. Open the app
2. Click **More info**
3. Click **Run anyway**

### If the file is blocked after download

1. Right-click the downloaded file
2. Click **Properties**
3. Tick **Unblock** if shown
4. Click **Apply**

---

## 🐧 Linux

### AppImage

Make the file executable:

```bash
chmod +x TextBasedGamePlayer.AppImage
```

Then run:

```bash
./TextBasedGamePlayer.AppImage
```

---

## ▶️ How to Use

1. Download the correct build for your system
2. Install or open the application
3. Launch **Text Based Game Player**
4. Choose **Open Game** or **Import Game Folder**
5. Select your game file or game folder
6. Play inside the app window

The game’s output appears in the app, and you can type your input directly into the app interface.

---

## 📝 Notes

* This repository is for **finished builds only**
* The source code is **not included here**
* The app is designed for **offline use**
* Some games may require **Python** to be installed on the computer
* Downloaded apps may trigger OS security warnings on first launch
* macOS users may need the `xattr` command shown above

---

## 🔧 Python Support

At the moment, some games may depend on a local Python installation.

### Planned improvement

The app is intended to **auto-detect Python** so users can run supported `.py` games more easily.

That means future versions may:

* detect whether Python is installed
* show Python status inside the app
* reduce setup steps for users

---

## 🛠️ Planned Improvements

Future improvements may include:

* better Python auto-detection
* smoother first-run setup
* a more guided installer experience
* reduced need for manual OS security workarounds
* improved game folder management
* additional file type support

---

## 🔒 Source Code

This public repository is used only to distribute build files.

The working project files and source code are stored separately in a **private repository**.

---

## 👤 Author

Created and maintained by **Garrick Hilton**
