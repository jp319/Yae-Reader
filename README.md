# Yae Reader

A simple Java application that translates raw manga using manga-ocr.

# Installation
### Java & Python
---
Make sure you have Python and Java in your computer, try installing from their official sites.
- [Java](https://www.oracle.com/java/technologies/downloads/)
- [Python](https://www.python.org/downloads)
- Also install PIP for Python by following this [guide](https://www.geeksforgeeks.org/how-to-install-pip-on-windows/).
### Manga OCR
---
The app uses manga-ocr for extracting japanese texts in images, see [manga-ocr](https://www.python.org/downloads) for further details

To install Manga OCR Run in command line:

```commandline
pip3 install manga-ocr
```
### Running the app
---
Once all the other Requirements are installed you may download the rar file in [Releases](https://github.com/jp319/Yae-Reader/releases).
- Make sure to extract it in one folder in any folder you want to put it.
- Inside the folder run the `bat` file named `downloadModel.bat` as administrator, this will download the model needed for manga-ocr which is upto 400MB.
- And that's it you can now run `Yae Reader.exe`.

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
