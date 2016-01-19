
Here is a bash script that gets the tools needed

```bash
# Install Tesseract OCR
# info : https://github.com/tesseract-ocr
# info : https://code.google.com/p/tesseract-ocr/

sudo apt-get -y install tesseract-ocr

# Install Tesseract OCR language files

sudo apt-get -y install tesseract-ocr-eng
sudo apt-get -y install tesseract-ocr-kor

# Install ImageMagick
# info http://www.imagemagick.org/script/index.php

sudo apt-get -y install imagemagick php5-imagick

# Install Xpdf -A PDF Viewer for X
# info : 

sudo apt-get -y install xpdf

# Install PDFtk a tool for doing things with PDF documents
# info : https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/

sudo apt-get -y install pdftk

# Install poppler-utils - a PDF rendering library based on the xpdf-3.0 code base.
# info : http://poppler.freedesktop.org/

sudo apt-get -y install poppler-utils

# Run apropos command to shows all of the tools for manipulating PDF files.
# info : https://en.wikipedia.org/wiki/Apropos_(Unix)
# info : http://www.linfo.org/apropos.html

apropos pdf | less
```

Sources:
http://williamjturkel.net/2013/08/24/working-with-pdfs-using-command-line-tools-in-linux/
http://www.imagemagick.org/script/install-source.php
http://www.imagemagick.org/script/binary-releases.php
https://ubuntu.flowconsult.at/linux/ocr-tesseract-text-recognition-ubuntu-14-04/
http://askubuntu.com/questions/471045/14-04-doesnt-have-package-imagemagick
