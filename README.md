# RyzenMaster-zhTW-Translator
Ryzen Maser Traditional Chinese Translator

## Motivation ##
RM (Ryzen Maser)'s Chinese display is not very friendly and perfectly. His default font uses **mingliu.ttc**, but it does not support the Chinese translation version. Therefore, we intend to provide a translation ourselves.

## Preview ##
![RyzerMaster-zhTW-screenshot](https://github.com/allenk/RyzenMaster-zhTW-Translator/raw/master/Artwork/RyzerMaster-zhTW.png)

## How it works ##
Because RM uses QT to design the software. Therefore, we can use QT's resource editor to create and change the translated QM files for i18n.

## Steps ##
The default installation location for RM is **%ProgramFiles%\AMD\RyzenMaste**. We need to get **chinese_simplified.qm** from **RyzenMaster\bin\Languages**. This is a simplified Chinese version. We will use this version as a template and translate it to our target version.

## Tools ##
To modify QM files, we need to install **qt5-tools\linguist.exe**. You need to go to the [QT linguist web page](https://doc.qt.io/qt-5/qtlinguist-index.html) to download and install it. Then we can use linguist to open the compiled .qm file. And re-export the translated .qm file. For convenience, I saved the .qm file as a chinese_traditional.ts file so that we can edit it with a text editor.

## Installation ##
To use traditional Chinese, we need to provide a translation file called: chinese_traditional.qm. and place it in **RyzenMaster\bin\Languages** and **RyzenMaster\bin\translations**.

## Use my pre-translated file ##
Please use the translation file in **prebuilt** and copy to your RM folder (%ProgramFiles%\AMD\RyzenMaste).
