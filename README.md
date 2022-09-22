# Yae Reader

A simple Java application that translates raw manga using manga-ocr.

# Installation
---
### - Java & Python

Make sure you have Python and Java on your computer. Try installing them from their official sites.
- [Java](https://www.oracle.com/java/technologies/downloads/)
- [Python](https://www.python.org/downloads)
- Install PIP for Python by following this [guide](https://www.geeksforgeeks.org/how-to-install-pip-on-windows/).
- Also install Git by following this [guide](https://github.com/git-guides/install-git).
### - Manga OCR

The app uses manga-ocr for extracting Japanese texts in images. See [manga-ocr](https://www.python.org/downloads) for further details

To install Manga OCR, Run in the command line:

```commandline
pip3 install manga-ocr
```
### - Running the app

Once all the other requirements are installed, you may download the rar file in [Releases](https://github.com/jp319/Yae-Reader/releases).
- Make sure to extract it in one folder in any folder you want to put it.
- Inside the folder, run the `bat` file named `downloadModel.bat` as administrator; this will download the model needed for manga-ocr, which is the file size is up to 400MB.
- And that's it. You can now run `Yae Reader.exe.`
---

### File Tree
```commandline
+---Yae Reader
    |   Yae Reader.exe
    |
    \---classes
        |   captured.png
        |
        +---manga-ocr
        |       mangaOCR2.py
        |       mangaOCR2testing.py
        |       test.png
        |
        +---model
        |
        |       (Download Model Here)
        |
        \---settings
                settings.xml
```
---
