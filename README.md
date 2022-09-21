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
`Extract it as File` in any folder you want to put it.
Inside the folder run the `bat` file named `downloadModel.bat` as administrator, this will download the model needed for manga-ocr which is upto 400MB.










## How to Run

+ First Download app from releases [v0.1.0](https://github.com/jp319/Yae-Reader/releases/tag/v0.1.0)
+ To run app in offline go to folder `classes/model`   
    * In there open a Terminal or CMD in the `model` folder Directory and run command lines:
```commandline
git lfs install
git clone https://huggingface.co/kha-white/manga-ocr-base
```
+ Simply run `Yae Reader.exe` then go to system tray right click icon then select `snip screen`.
+ It will extract text from captured image and will open up a browser to translate the text using [DeepL Translator](https://www.deepl.com/translator).
    * Do understand that extracting text from images might take a few more seconds but not very long.

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
