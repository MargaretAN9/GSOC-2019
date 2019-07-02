Image Sequencer 
User Manual Version 0.2 
July 2, 2019
======================
1. [Introduction](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#introduction)
2. [Specifications](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#specifications)
 -3. [Input Image Format Option](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#input-image-format-option)
  4. [Output Options](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#output-options)
  5. [Color Scheme - RGBA](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#color-scheme--rgba)
6. [Image Coordinates](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#image-coordinates)
7. [Processing Environment](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#processing-environment)
8. [Image Modules](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#image-modules)
  9. [Add QR Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#add-qr-module)
  10. [Average Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#average-module)
  11. [Blend Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#blend-module)
  12. [Blur Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#blur-module)
  13. [Brightness Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#brightness-module)
  14. [Channel Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#channel-module)
  15. [Color Temperature](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#color-temperature)
  16. [Color Bar Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#color-bar-module)
  17. [Colormap Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#colormap-module)
  18. [Contrast Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#contrast-module)
  19. [Convolution Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#convolution-module)
  20. [Crop Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#crop-module)
  21. [Decode QR Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#decodeqr-module)
  22. [Detect Edges](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#detect-edges)
  23. [Dither Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#dither-module)
  24. [Draw Rectangle Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#draw-rectangle-module)
  25. [Dynamic Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#dynamic-module)
  26. [Exposure](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#exposure)
  27. [Fisheye Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#fisheyegl-module)
  28. [Flip Image Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#flipimage-module)
  29. [Gamma Correction Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#gamma-correction-module)
  30. [Gradient Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#gradient-module)
  31. [Grid Overlay](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#grid-overlay)
  32. [Histrogram Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#histogram-module)
  33. [Import Image Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#import-image-module)
  34. [Invert Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#invert-module)
  35. [NDVI Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#ndvi-module)
  36. [NDVI Colormap Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#ndvi-colormap-module)
  37. [Overlay Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#overlay-module)
  38. [Paint Bucket Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#paint-bucket-module)
  39. [Resize Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#resize-module)
  40. [Replace Color Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#replacecolor-module)
  41. [Rotate Module](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#rotate-module)
  42. [Text Overlay](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#text-overlay)
  43. [Threshold](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#threshold)
  44. [Tint](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#tint)
  45. [White Balance](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#white-balance)
46. [Applications](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#applications)
  47. [NDVI (NIR and Red) with Color Bar](https://github.com/MargaretAN9/GSOC-2019/blob/master/ImageSequencerUserManual.md#ndvi-nir-and-red-with-color-bar)

## Introduction:
This manual provides instruction for the web browser applications of Image Sequencer.  The user manual consists of specifications, a description of the modules and an applications section which describes how the modules, when combined, can be used for different types of image analysis.   
## Specifications:
### Input Image Format options:
Jpg *(freezes and locks up )*
Jpeg
png
Gif
canvas
*Max Image Size: 1Mb? (processing time vs file size)*
Bit depth?
Color and black/white
*Maximum  length and width size?*
### Output Options:
PNG
GIF of sequences 
### Color Scheme – RGBA:
Color is represented as as ‘tuple’ in (R,G,B) format. Each color channel has a value between 0 and 255.
black is: (0,0,0),
white is (255,255,255).. 
red is (255,0,0). 
blue is (0,0,255). 
*‘A’ represents transparency with values 0 to 255.*
### Image coordinates:
Coordinates in (X,Y), which is (0,0) is located at the top left of the image ![grid1](https://lh3.googleusercontent.com/C8cnaZVwO2HFeHLyCBGJXa5s0im9a3BjwT79JmQsC1l_CgR3jP0mTcG3iYst9JMx8pisZkzY0ELd ) ![grid2](https://lh3.googleusercontent.com/PhCYTVuc4ebhYOFPCf1Brwy7ZfrDh9qFRHRR0LKJnMluAgcHiuOhdjyJrxNghKqrHkqxICvyRNI4)

<![endif]-->

## Processing Environment:
*(What is the processing environment ???)*
*(processing time vs file size)*
## Image Modules:

Image Sequencer uses modules that perform a variety of step-by-step image processing tasks.  Figure 3 describes the general workflow.

This section describes each module and a general implementation example  Most examples used Figure 4 as the input reference image.
![workflow](https://lh3.googleusercontent.com/XE_twkHy8uxZ6jycIddQlMxJF91AbU29pJPILcRcolwiiaNJAUPrJhU_PAJYmVGGoHcJ7aOSTNFR)
Figure 4 Reference Image:
![Figure 4 Reference Image](https://lh3.googleusercontent.com/A98oLhF19A1li9ugUa9lvyOJXzKang6nwAn61E_Zwf6NZ3Tqw3OsuuHqUbbb2MnWD_eTL140rRJj )
Additional information on the modules and other operating modes can be found at the Image Sequencer GitHub site. 

 - [https://github.com/publiclab/image-sequencer/tree/main/docs](https://github.com/publiclab/image-sequencer/tree/main/docs)
 - [https://github.com/publiclab/image-sequencer/blob/main/README.md](https://github.com/publiclab/image-sequencer/blob/main/README.md)
### Add-qr-module:
This module adds a QR code to the image that corresponding to an input string.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('add-qr',options)
    .run()
Where options is an object with the following properties:
 - size: size of QR code in pixels (default 200)
 - qrCodeString: input string to generate QR code
![qr](https://lh3.googleusercontent.com/o99UIUmc8jbs7sn7InSG0NfizUbm3UhOe5q96dPPEGo4ptqHs0lULdkEoFdEEMOLC17dqxFn89wy)
### Average-module:
This module is used for averaging all the pixels of the image.
Usage:

    sequencer.loadImage('PATH')
    .addSteps('average',options)
    .run()
![average](https://lh3.googleusercontent.com/RYHPXdfMDroNKSaKESqJxR30bhSp15fNtK1RozQZgZUfeo19ISwPwmUsM82CvmPTElJ9D60QTdm4)
### Blend-module:
This module is used for blending two images . _Blend two chosen image steps with the given function. Defaults to using the red channel from image 1 and the green and blue and alpha channels of image 2._

Usage:

    sequencer.loadImage('PATH')
    addSteps('blend',options)
    .run()
Where options is an object with the following properties:

-   offset: step of image with which current image is to be blended (Two steps back is -2, three steps back is -3 etc; default -2)
-   func: function used to blend two images (default: function(r1, g1, b1, a1, r2, g2, b2, a2) { return [ r1, g2, b2, a2 ]})

For this example it is necessary to import a second image.
![blend](https://lh3.googleusercontent.com/XNuFGACTSQ0yDthkG6KSopK4-zDSJITsgT4XwhTUFn1byaB7IuF5YqvwQXuzaTvpQwRuKNSbMa2V)
### Blur-module:

This module is used for applying a Gaussian blur effect.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('blur',options)
    .run()


Where options is an object with the following property:
-   blur : Intensity of Gaussian blur (0 to 5; default 2)
![blur](https://lh3.googleusercontent.com/0gqLTZyaTssk5H9qloxBs_9L53LZbikFr9DIWuu2CS_Z3Eg8byytJT-fJgrLaMoyq3N5-EAjwi6R)


### Brightness-module:

This module is used for changing the brightness of the image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('brightness',options)
    .run()


Where options is an object with the following property:
-   brightness : brightness of the image in percentage (0 to 100; default 100)

*note: sliders goes to 200? Not 100*

![brightness](https://lh3.googleusercontent.com/jWt1o-ReLUXhAgRKF0Kvwtj2-v5CmQKsx4EngN_jhEkkn07TQ0iT9IZEkCxE6sipntH0wGge0jov)

### Channel-module:

This module is used for forming a grayscale image by applying one of the three primary colors.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('channel',options)
    .run()
Where options is an object with the following property:

-   channel : color of the channel (red, green, blue; default green)

![blue](https://lh3.googleusercontent.com/zZk1cCU0sgHMHBNmL_NMC-dZcmyykuDZUt_dde2bcfrX4ioA3xDh1u4pGHXjbTBLlBkULHjM7W74)

![green](https://lh3.googleusercontent.com/eipiq-dIw4_3x6S1s64DktO6gnAR91I-6T-K35SaTkM-9r1xk9ietLBJmFjeU4L4H32Y1n2QnU7L)
![red](https://lh3.googleusercontent.com/JADUlR2G21jfxWBXBZr1r4fHfxhvbdlDAsSBTVE2ncBjI5tswWk8ES3NyIsvxXV2qaauApZDlSJ8)

### Color Temperature:

This changes the color temperature of the image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('color-temperature',options)
    .run()

Where options is an object with the following property:

-   temperature : temperature between 0 - 40,000 kelvin (default 6000)

Color temperature AT 100, 1000, 10,000, and 30000:
![100](https://lh3.googleusercontent.com/B1GiDQ6iHvBM0nZ3eUxD_Mt8Om7kMKLyI-TSep-Mplchds7snjIbBhUEV2B0x6JgBmK-eUcGYKxi)
![1000](https://lh3.googleusercontent.com/KLkMrUB0Y3gtsGoDNkf5ZGdrLzMtBxhMh3ipcFn5m1ERxcrzwWTBZqf7ctXRwFJhNCDqQgJ55PaV)
![10000](https://lh3.googleusercontent.com/hdGOEDsm9y7emleDeJS7TW3OOMUSKLGRObhvJuZMXYK3Q8nC0way7AlOM_YpH_t3EI5daFlJhF-D)
![100000](https://lh3.googleusercontent.com/_67T5U1AMUUed9E1Z_aIVO4LIUU9wT8JEMfRZIb3MyUIuq9euMPsQ2gGpNbbPGM6d6fNjixN523v)
### Color-bar-module:

This module is used for displaying an image with a color bar.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('colorbar',options)
    .run()
Where options is an object with the following properties:

-   colormap: Name of the Colormap(default, greyscale, stretched, fastie, brntogrn, blutoredjet, colors16; default: default)
-   x: X-position of the image on which the new image is overlayed (default 0)
-   y: Y-position of the image on which the new image is overlayed (default 0)
-   h: height of resulting cropped image (default : 50% of input image width )

*Could not get color bar to work*
![colorbar](https://lh3.googleusercontent.com/eyctaS-TsE_8QC9cuDn8qjAcM1n11XiMFpbW6mO1nEkngaE50gAyCWv10Pq4SlDJ_8hXQKTAsiQc)

### Colormap-module:

This module is used for mapping brightness values (average of red, green & blue) to a given color lookup table, made up of a set of one more color gradients.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('colormap',options)
    .run()
Where options is an object with the following property:

-   colormap: Name of the Colormap ( greyscale, stretched, fastie, brntogrn, blutoredjet, colors16)
![colormap](https://lh3.googleusercontent.com/8BSfWTEKOQPYlIzE419K4BL1qrDhLm8ZvM26vEKZbu5G0HSybzKELbvBAi5shqIb31mJ2D2sf8fY)
![fastie](https://lh3.googleusercontent.com/fD2kQMVTbdxZaMMe63tnND4PbBzp7BhQK2M5ygF1bwnUfMmdS-kSqWGzsAt5G8kxMXTPSUd_pD9q)
### Contrast-module:
This module is used for changing the contrast of the image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('contrast',options)
    .run()
Where options is an object with the following property:
-   contrast : contrast for the given image (-100 to 100; default : 70)
![contrast](https://lh3.googleusercontent.com/-IsvrKxPphqMdx3pvyIprj9iVLt2B6UbuTe_9V2dXgi-JMCPNqbsj6cbRw0Y2sSkCjHk6vt22Xqx)
### Convolution-module:

This module is used for performing image-convolution.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('convolution',options)
    .run()
Where options is an object with the following properties:

-   constantFactor: a constant factor, multiplies all the kernel values by that factor (default : 1/9)
-   kernelValues: nine space separated numbers representing the kernel values in left to right and top to bottom format(default: 1 1 1 1 1 1 1 1 1)
![convulotion](https://lh3.googleusercontent.com/W57SJSUSgqigJ-tLBCUQ1VxcstoVFjIVyJluOY43_AmxsMFNFQ_BMY_V0pNCGSZTDfi3UVu7KAJH)

### Crop-module:

This module is used to crop an image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('crop',options)
    .run()
Where options is an object having the properties x, y, w, h. This diagram defines these properties:
![crop](https://lh3.googleusercontent.com/D6_RHxxBiQ7597CNOLaEksZOn5LE-vEthRfq4qNuAGX8VobXzpWAQUi8WFcBrNfq7mCeP2zhKLXh)

Defaults:
-   options.x: 0
-   options.y: 0
-   options.w: half of image width
-   options.h: half of image height
![crop2](https://lh3.googleusercontent.com/Ng1NG7QL3lIMyvIdwIW8TuEvwgNeZOZPZuBjVgDHVoAtwK69TLK7E_qMDfjhU2vin28mkZuyZONu)

### DecodeQr-module:

This module is used for decoding a QR in image (if present).

Usage:

    sequencer.loadImage('PATH')
    .addSteps('decode-qr',options)
    .run()
 ### Detect Edges:
This module detects edges using the Canny method, which first Gaussian blurs the image to reduce noise (amount of blur configurable in settings as `options.blur`), then applies a number of steps to highlight edges, resulting in a greyscale image where the brighter the pixel, the stronger the detected edge

This module is used for detecting images.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('edge-detect',options)
    .run()
Where options is an object with the following properties:

-   blur: Intensity of Gaussian blur (0 to 5; default 2)
-   highThresholdRatio: Upper Threshold Ratio ( default: 0.2)
-   lowThresholdratio: Lower Threshold Ratio ( default: 0.2)
![edges](https://lh3.googleusercontent.com/5zrQL8KHtd76UCV7wcU6x-BZqp5Me6ZoDfS_QIHRkp6OUrnw3nNL_oUoFM0EaLYht7I8ZLnVzi_p)
### Dither-module:
This module approximates a color from a mixture of other colors when the required color is not available, creating illusions of the color that is not present actually. (Not sure what this means)

Usage:

    sequencer.loadImage('PATH')
    .addSteps('dither',options)
    .run()
Where options is an object with the following property:

-   dither: Can select the name of the Dithering Algorithm (default: none)
![none](https://lh3.googleusercontent.com/jaxbqrEozB8uv6x497xTzUbtyaS47TeaNajoJ_kCsDe6svIkvLGILfGC0DnG-GTW0ySIBeYYOhjl)
![bayer](https://lh3.googleusercontent.com/jOd8BBujIN8O9iKqyXopHdDWE0zw7fqFZXLjr0ZfRFCo-z2zb2wYMzzEIfEc_lYyeTh3T1SYYlnh)
![alkison](https://lh3.googleusercontent.com/eQXezh6XXjdyvAdoeQVhJc1ABus4BTBNvAWh1J3Yxd6n0TgxwFeAba-tmjzBC8Vf_BfkgX7y3QnM)
![roy](https://lh3.googleusercontent.com/1_8zAfzV4_NkPinJjVRjeHHOpGFRhqLhvBEEMii_AoIv_QOM1tuwEf2le5Cj0iWn2Qu6QynRuR33)
### Draw-rectangle-module:

This module helps to draw a rectangle on the image with a starting and ending corner with the specified thickness and color of the border.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('draw-rectangle',options)
    .run()
Where options is an object with the following properties:

-   startingX: starting x position of the rectangle (default 0)
-   startingY: starting y position of the rectangle (default 0)
-   endX: last x position of the rectangle (default "width")
-   endY: last y position of the rectangle (default "height")
-   thickness: thickness of the border (default 1)
-   color: RGBA values separated by a space (default "0 0 0 255")
![rect](https://lh3.googleusercontent.com/sXICJ0JatL8_V7TPQCCw6BGWHONxgNeH6q3Q4zdw2GRhMbGMR7hb4jm272FcEFssAbq36GJ9cAYq)
### Dynamic-module:

This module is used for producing each color channel based on the original image's color.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('dynamic',options)
    .run()
Where options is an object with the following properties:
-   red: expression for red channel (R, G, B and A as inputs; default r)
-   green: expression for green channel (R, G, B and A as inputs; default g)
-   blue: expression for blue channel (R, G, B and A as inputs; default b)
-   monochrome: fallback for other channels if none provided (default: r+g+b/3)
![dynamic](https://lh3.googleusercontent.com/1HVPawYwO7F00L8xNkCvODddc4i4gbvprSaHoZGE1s2zU_zk48UwT4y0dgp802MZahY4BUmi806y)
*Is it r+g+b or r+g+b/3)?*
### Exposure:
![exposure](https://lh3.googleusercontent.com/wqsLEq_UWar3s-aCbnf238mxGPd2BJbxrDyvw5QFc6DxQgNoC_ib5DxB6spte2IcduUOpWjK2Nn5)
### FisheyeGl-module:

This module is used for correcting Fisheye or Lens Distortion

Usage:

    sequencer.loadImage('PATH')
    .addSteps('fisheye-gl',options)
    .run()

Where options is an object with the following properties:
-   a: a correction (0 to 4; default 1)
-   b: b correction (0 to 4; default 1)
-   Fx: x correction (0 to 4; default 1)
-   Fy: y correction (0 to 4; default 1)
-   scale: The ratio to which the original image is to be scaled (0 to 20; default 1.5)
-   x: Field of View x (0 to 2; default 1)
-   y: Field of View y (0 to 2; default 1)
![fisheye](https://lh3.googleusercontent.com/9Z8UTfkSJM-yy0cIe5dO_4bxjssf7pqbGGzIn_MSOzx4LB_SuDexD75N_n1h4nIYxZMkWYOs0r1K )
### Flipimage-module:

This module is used for flipping the image on the selected axis.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('flip-image',options)
    .run()
Where options is an object with the following properties:
 - Axis: select the required axis (default: vertical)
![flip](https://lh3.googleusercontent.com/ML3N9rOY4l4QuCFeiEzFGHD1L2J8P83o8DEj1Pdj8dJjGOvYz4FWGDCjzhG8l36i20vYqRk9dNac)
![flipped](https://lh3.googleusercontent.com/6ShR5rDrxxwQCrZkQcH4IOmSxm5mYbyKJkD_y9LGWj8f3nC-jUaRwIkmOogFQ4geeX5pyNAsYA5Z)
### Gamma-correction-module:

This module is used for applying gamma correction.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('gamma-correction',options)
    .run()
Where options is an object with the following property:

-   adjustment: Inverse of actual gamma factor (default 0.2)

*(slider does not work)*
### Gradient-module:
This module is used for finding gradient of the image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('gradient',options)
    .run()
![grid](https://lh3.googleusercontent.com/wtOsiWayqrq4W6GuvQv2beIPKEDrQy8sdVnTSKx-ulJmIDsfE_sYOpP0P_bfpaqf1l3Rt9SH3ToF)
### Grid Overlay:
This adds the grid over an image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('grid-overlay',options)
    .run()
Where options is an object with the following property:

-   options.x: The value at which the grid line should start in x-axis.
-   options.y: The value at which the grid line should start in y-axis.
-   color: Color for the grid on the image.

*(only works once)*
![grid](https://lh3.googleusercontent.com/YZp6Ja3U9-wJxlpDpxiVlAHr5gsGKXKaZ-ezDB5yRrQPfphpQnTl1SD5GmrJEiRgTwXPy79ARqDr)
### Histogram-module:
This module is used for calculating histogram of the image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('histogram',options)
    .run()
Where options is an object with the following property:

-   gradient: Boolean value used to toggle gradient along x-axis. (true or false; default true)
![histo](https://lh3.googleusercontent.com/U7LWC53SqBCAAg2XtDeq3qH3QcUj1iZdfGukrpNdgNYwpg8TcI_So_JktKvczDO0VJAbKECkZajn)
### Import-image-module:

This module is used for importing a new image and replacing the original with it.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('import-image',options)
    .run()
Where options is an object with the following property:

-   url: url of the new image (local image url or data url;default: "./images/monarch.png")

### Invert-module:

This module is used for inverting the image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('invert',options)
    .run()
![invert](https://lh3.googleusercontent.com/8XIECi58eAKN2xKMesaEtjCTaUdu_qfhO9dOx308Tu-XVmoHPexhcJkzur884i4xKq_zweESY6WZ)
### NDVI-module:

This module is used for applying ndvi technique to the image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('ndvi',options)
    .run()
Where options is an object with the following property:

-   filter: filter for NDVI (blue or red; default red)

### NDVI-colormap-module:

This module is used for demonstrating ndvi and colormap properties consecutively.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('ndvi-colormap',options)
    .run()
![ndvi1](https://lh3.googleusercontent.com/5SQpUQczZSXqxUnkkDIxu8nLWjMgxL3_f4zryxjxOsZVT9zYWHMeN3D5WXjfdugrrzsOj2u3WMeV)
![ndvi2](https://lh3.googleusercontent.com/4dyid6O69AeeMfw6CCLlmuElLHvvx_xU19AgiTEp4UXkCc02QkIGGsqvtcawJhBMIWwLDdEn6uEG)
### Overlay-module:
This module is used for overlaying an Image over another .

Usage:

    sequencer.loadImage('PATH')
    .addSteps('overlay',options)
    .run()
Where options is an object with the following properties:

-   x: X-position of the image on which the new image is overlayed (default 0)
-   y: Y-position of the image on which the new image is overlayed (default 0)
-   offset: offset to the step on which the output of the last step is overlayed (default -2)
![overlay](https://lh3.googleusercontent.com/vLfS8aIfwec-yyPfotBx05Bhsty1lM3_XmIDX8AEr-jLqnGMg0VJIGAWm1o-iBwg--OoOdNr58da)
### Paint-bucket-module:
This module fills any polygonal shape with the specified color in pixels.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('paint-bucket',options)
    .run()
Where options is an object with the following property:

-   startingX: it is the value of the starting x-cordinate (default 10)
-   startingY: it is the value of the starting y-cordinate (default 10)
-   fillColor: they are four spaced seperated numbers representing the RGBA values of fill-color (default "100 100 100 255")
-   tolerance: it is the % tolerance (default 10)

*(does this work, all images seem the same)*
### Resize-module:
This module is used for resizing an image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('resize',options)
    .run()

Where options is an object with the following property:

-   resize: Percentage value of resize (default 125%)

![resize](https://lh3.googleusercontent.com/mP8-lKFTCuHRH0JA5wLdLP3jB3_nTNWqec5WlvJCpcq6-TaL6mGPLegzFr-mK0q7aIjMsG7HZZlA)
*(is this off by 100?)*
Resize-canvas:
![resize](https://lh3.googleusercontent.com/L0BHuRJlGFq30teGNx_alnSs-qHar56Sl13mcT5cHmSKCiuETMskklhqOjDRmlVLIorYozmZSNYy)
### ReplaceColor-module:
This module is used in replacing the color with grey or any desired color.

Usage

    sequencer.loadImage('PATH')
    .addSteps('replace-color',options)
    .run()
Where options is an object with the following properties:
-   replaceMethod: replaces with the desired color (default greyscale)
-   replaceColor: three space separated numbers representing the RGB values of color to be filled (default "0 0 255")
-   color: three space separated numbers representing the RGB values of color to be replaced (default "228 86 81")
-   tolerance: it is the % tolerance (default 50)
![replacec](https://lh3.googleusercontent.com/wGzhtzvP4mUgnh3P1NDNGW32gEyBEZDhikJRVViWtY7lgoDa7QNF3oBaLwPihNqSXb0wf_jVaytU)
### Rotate-module:
This module is used for rotating an image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('rotate',options)
    .run()
Where options is an object with the following property:
-   rotate: angular value for rotation in degrees (between 0 and 360; default 0)
![rotate](https://lh3.googleusercontent.com/cF2yIQzbKl5sQ-6hQXEPIqC2emjNIxJiGG2zWIbvQubz_jOzHtposT94miMC0gb_yLmgcbJnQhjY)
This module is used for changing the saturation of the image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('saturation',options)
    .run()
Where options is an object with the following property:

-   Saturation: Saturation for the new image (between 0 and 2; default 0).
![satur](https://lh3.googleusercontent.com/IDJa8F1hE9SlhNO9smcXAHzM9iq-2vTmxPhAfMNin2My28s9N4DKGf9nhVkHi4hZziWx3eOGeaeY)
### Text-overlay:
![text](https://lh3.googleusercontent.com/3U2Qo9DP3a9-_57MBpYubxpwwy3jjCaK7EBITxB3FjoZwiovNKVfT8mDYPuwbQW6c8MJ4ED2jI58)
### Threshold:
Thresholding is used to create binary images.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('threshold',options)
    .run()
Where options is an object with the following property:
-   threshold: it allows to select the types of thresholding (default "manual thresholding")
-   input: it allows to select the range of thresholding value (default 120)
![threash](https://lh3.googleusercontent.com/pG65GyAYLktF--riUv6PJoe7ogDGHx7WlxVXQWUCt3qFgQ2CJJ7908wbSG3YGSOBz943Sci_dPOS)
### Tint:
It adds color tint to an image.

Usage:

    sequencer.loadImage('PATH')
    .addSteps('tint',options)
    .run()

   Where options is an object with the following property:
-   color: RGB values separated by a space (default "0 0 255")
-   factor: amount of tint (default 0.5)
![tint](https://lh3.googleusercontent.com/UkjU82j-zFgCGdlp5I5mICHGvBvME3QLQPJIlBSPxlu0617gKPs-eSIzX2aOGNQXvJu4kmrObQvP)
### White Balance:
![white](https://lh3.googleusercontent.com/1HqpzxNX3FdGzS52f3mbTodzA8HnKv6TuSdii-aHgdiQ-YUT677g9Q-Nr71OGYZVwNfs0KzeML6l)
## Applications:
This section demonstrates how Image Sequencer modules can be applied for different applications.
### NDVI (NIR and Red) with Color Bar:
![ndviapp](https://lh3.googleusercontent.com/vSPttpkGXDBja4qcU5Y_mmZujhuItbTP_1hoqxbNuqXn5dG2cX7j4RiOrdQJSFDlcxFOswOgh3jI)






