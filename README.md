# Repository for Generating and Reading DIC images using qr codes.

## Required Libraries:

[opencv](https://github.com/opencv/opencv)

[zbar](https://github.com/ZBar/ZBar)

[qrcodegen](https://www.nayuki.io/page/qr-code-generator-library)


## To build executable:
```
mkdir build
cd build
cmake ..
make
```

## Generating qr image

Command line input:
```
./genqr <image base name> <code stride length> <polynomial function input>
```

Output QR format:
```
"<image base name> <row> | <column>"
```
