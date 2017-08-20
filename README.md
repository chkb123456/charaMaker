# charaMaker
A simple character picture maker for KuroScripter, which convert a png file with transparent pixels to a bmp file, and fill transparent pixels with specialized color.

## Build
### On Windows
    g++ -o charaMaker.exe charaMaker.cpp
### On Linux
    g++ -o charaMaker charaMaker.cpp

## Usage
    charaMaker <-i PNGFile> [-o BMPFile] [-c TransparentColor]
    
