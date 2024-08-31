# Images

In EWC all images are defined using images files, which can be in any format
supported by web browsers.

The ImageList object has a property "Files", which contains a list of the
file names that define the ImageList. It is not possible to populate an
ImageList by creating child icons and bitmap objects, as in `⎕WC`.

The location of your images must be declared by setting the variable EWC.RESOURCES
before calling EWC.Init, fo example:

`EWC.RESOURCES←1 2⍴'images' '/tmp/myapp/images'`

This creates a virtual folder `/images/` that can be referred to when creating
ImageLists and other objects created from image files.

See the [Configuration] for more details.