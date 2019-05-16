# natvis-collection
MSVS debug visualisation
Put all `*.natvis` files to the `%USERPROFILE%\My Documents\Visual Studio 17\Visualizers\`

### QImage
I tried to extract image information for the "Image Watch" directly from QImage, but "Image Watch" ignores it.

So, for now, I've found only one way to show an image of type QImage: show QImageData. In the Autos/Locals/Watch window, select the `image` item of the QImage object to display it with "Image Watch"