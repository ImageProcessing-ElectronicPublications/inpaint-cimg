# inpaint

## Description

This is a M2 project. The goal was to implement an efficient inpainting algorithm.

## Documentations

See [documentations of M2 project](https://github.com/ImageProcessing-ElectronicPublications/inpaint-cimg-doc):
* Implemented from: doc/Bornemann.pdf
* Baseline: doc/Telea.pdf
* Report (in french): doc/rapport.pdf

## Build

Install `CImg` on your system and type:
```sh
make
```

## Usage

```sh
./inpaint you.png R G B
```

## Example

```sh
./inpaint img/masked_text.png 252 2 4
./inpaint img/masked_lena.png 255 0 0
```

See [exammple images of M2 project](https://github.com/ImageProcessing-ElectronicPublications/inpaint-cimg-doc).  
![masked_text.png](https://raw.githubusercontent.com/ImageProcessing-ElectronicPublications/inpaint-cimg-doc/main/img/masked_text.png)

----

https://github.com/vdel/Inpainting
