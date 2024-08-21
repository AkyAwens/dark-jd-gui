# Dark JD-GUI

[![GitHub stars](https://img.shields.io/github/stars/AkyAwens/dark-jd-gui)](https://github.com/AkyAwens/dark-jd-gui/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/AkyAwens/dark-jd-gui)](https://github.com/AkyAwens/dark-jd-gui/network)

## Overview

Dark JD-GUI is a patch of the original JD-GUI to add a dark theme using flatlaf.

## Preview

![JD-GUI Dark Theme Preview](https://i.ibb.co.com/0C7bnBF/image.png)

## Installation

### Step 1: Downloading jar

Download in the [releases](https://github.com/AkyAwens/dark-jd-gui/releases/tag/Release) latest jar with patched jd-gui.

### Step 2: Launching

Double click on the jar OR use `java -jar jd-gui-1.6.6-dark.jar`
Enjoy.

# OR Manual Installation

btw you can follow my [yt tutorial](https://youtu.be/XNkNXcx0RWo)

### Step 1: Download archive with files

Download the archive by pressing the green Code and [Download ZIP](https://github.com/AkyAwens/dark-jd-gui/archive/refs/heads/main.zip) button

### Step 2: Patching

1. Extract the downloaded `.zip` file.
2. Extract the eclipse.xml file to the original jd-gui under the path rsyntaxtextarea/themes
3. Open flatlaf-3.5.1 and flatlaf-intellij-themes-3.5.1 as an archive and extract the com folder in both archives to jd-gui.
4. Open [Recaf V4 with launcher](https://github.com/Col-E/Recaf-Launcher) and open jd-gui.jar in workspace, open org.jd.gui.App.class and choose Vineflower as decompiler.
5. Import Flatlaf class: import com.formdev.flatlaf.intellijthemes.FlatOneDarkIJTheme;
6. Initiliaze: public static FlatOneDarkIJTheme onedark = new FlatOneDarkIJTheme();
7. And replace line UIManager.setLookAndFeel(configuration.getLookAndFeel()); to UIManager.setLookAndFeel(onedark);
8. Press CTRL + S and save JAR.

### Step 3: Enjoy!

Launch ur patched jd-gui and enjoy.

---

*Happy look decompiled code in jar's with JD-GUI in the dark!* 🌙
