# Yae Reader

A simple Java application that translates raw manga using manga-ocr.
## Manga OCR
See [manga-ocr](https://github.com/kha-white/manga-ocr) for further details.

## Installation Manga OCR
You need Python 3.6, 3.7, 3.8 or 3.9. Unfortunately, PyTorch does not support Python 3.10 yet.

Some users have reported problems with Python installed from Microsoft Store. If you see an error:
`ImportError: DLL load failed while importing fugashi: The specified module could not be found.`,
try installing Python from the [official site](https://www.python.org/downloads).

If you want to run with GPU, install PyTorch as described [here](https://pytorch.org/get-started/locally/#start-locally),
otherwise this step can be skipped.

If you want to run with GPU, install PyTorch as described here, otherwise this step can be skipped.

Run in command line:

```commandline
pip3 install manga-ocr
```
---
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
