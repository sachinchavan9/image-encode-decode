#IMAGE TO _BASE64 STRING_

##Convert Image into base64 format.

###Supprted image format is:

* jpg
* png
* jpeg
* JPG
* JPEG
* TIF

clone the git repo with
```
git clone https://github.com/sachinchavan9/image-encode-decode.git
```

```
python img_to_base64.py -h # for help

'''
python img_to_base64.py -h
usage: img_to_base64.py [-h] [-i IMG]

Convert Image into base64 format, supported format is jpg and png.

optional arguments:
  -h, --help         show this help message and exit
  -i IMG, --img IMG  Input image or image path to convert into base64
'''
