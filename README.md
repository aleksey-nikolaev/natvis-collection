# natvis-collection
MSVS debug visualization
Put all `*.natvis` files to the `%USERPROFILE%\My Documents\Visual Studio 2017\Visualizers\`

_Note. After I install MSVS 2019, there is no `Visual Studio 2019\Visualizers\` - I found `Visual Studio 2019` folder  in my documents with only one subfolder `Code Snippets` in there. So, I created `Visualizers` subfolder manually and it works._

### QImage
I tried to extract image information for the "Image Watch" directly from QImage, but "Image Watch" ignores it.

So, for now, I've found only one way to show an image of type QImage: show QImageData. In the Autos/Locals/Watch window, select the `image` item of the QImage object to display it with "Image Watch"
