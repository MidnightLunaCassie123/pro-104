-Computer Vision helps the computer to identify or understand the content of the digitally captured information. The study of computer vision began around the 1960s to mimic the human visual system. Since then the field has expanded immensely in various areas of human life. Let’s understand through a few of the examples of computer vision tasks: ● Image & Video Pre-Processing: High and complex images can be processed to train machines better in identifying objects. Example: Medical image scanning uses high level image processing techniques to get accurate results. ● Recognition: This task of computer vision that helps to identify if an image contains specific objects or features of an object. Example: Face recognition to unlock smartphones. ● Scene Segmentation: This task splits the scene into multiple segments. Example: Road scene segmentation can be used in self-driving cars. ● 3D Scene Reconstruction: Constructing realistic 3D images by taking multiple 2D images.

-Types of Digital Images: There are three types of digital images: ● Binary Images ● Grayscale Images ● Colored Images Binary Images: Binary images are black and white images. Each pixel value is represented by a single value, out of 2 values, either 0(black) or 1(white). In binary images there is no gray level. Only two colors that are black and white are present in it.

-Gray-scale Images: Gray-scale images are called monochrome, that is one-colored images. That one, as the name suggests gray. Each pixel will be represented by a single value ranging between 0-255 values. In gray-scale images there are 256 gray levels representing 256 shades of one gray color with 0(black), and 255(white).


-Colored Images: Colored images have three-band monochrome data. The band is also called channels. Red band: Values range 0-255 Green band: Values range 0-255
06:10pm

-Blue band:Values range 0-255 Each pixel value is represented by 3 values as the combined value of three bands(channels), (R,G,B).

-The waitKey() will keep the image open for: ● Infinite time: 0 milliseconds, the image window will be infinitely open until we close it manually. ● Definite time: Greater than 0 milliseconds, the image window will only be open for the given time.
