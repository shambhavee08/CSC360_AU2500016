# Class Reflection – 03-11-2026

## Topics Covered

- Introduction to Digital Images and Image Formation
- Pixels, Resolution and Image Dimensions
- Raster and Vector Images
- Image Formats: JPEG, PNG, GIF, BMP, TIFF and SVG
- Lossy and Lossless Compression
- RGB Colour Model, Alpha Channel and Transparency
- Colour Depth, Bit Depth and Binary Representation
- Bits, Bytes, Big Endian and Little Endian
- Image Storage and Memory Representation
- Grayscale Images and Intensity Levels
- Image Histograms and Their Interpretation
- Brightness, Contrast and Dynamic Range
- Histogram Equalization and Contrast Stretching
- Image Thresholding and Segmentation
- Image Filters, Convolution and Noise Reduction
- Applications of Digital Image Processing
- Introduction to ImageJ and Its Tools
- Histogram Analysis, Measurements and Plugins in ImageJ
- Image Processing Using JavaFX
- Image Transmission, Binary Data and Wi-Fi

## Notes

### 1. Introduction to Digital Images

We started by understanding what a digital image actually is and how a computer represents it. Earlier, I mostly thought of an image as a picture that could be captured, saved or edited. However, I learned that a digital image is essentially a collection of numerical values that represent visual information.

An image is made up of small elements called pixels. Each pixel stores information about its colour or intensity, and when these pixels are arranged together, they form the complete image that we see on a screen.

I also understood that this basic concept is used in several fields, including photography, medical imaging, satellite imaging, security systems and computer vision.

### 2. Image Formation and Representation

We explored how a real-world image is converted into a digital image. When light reflects from an object, it enters a camera or imaging device. The sensor captures the light and converts it into electrical signals, which are then processed to produce a digital image.

Two important processes involved in this conversion are:

- **Sampling:** Dividing the image into a grid of pixels. This determines its spatial resolution.
- **Quantization:** Assigning numerical values to the sampled pixels to represent their intensity or colour.

This helped me understand that computers cannot directly process visual information in the same way humans see it. The information first needs to be converted into a digital form that the computer can store and work with.

### 3. Pixels, Resolution and Image Dimensions

A pixel is the smallest individual element of a raster image. Every pixel contributes to the overall appearance and detail of the image.

We also discussed resolution and image dimensions. For example, an image with dimensions of 1920 × 1080 contains 2,073,600 pixels. Image dimensions tell us the number of pixels along the width and height, whereas resolution can also refer to pixel density, such as Pixels Per Inch (PPI).

I learned that a higher pixel count can allow an image to contain more detail, but image quality does not depend on pixel count alone. Factors such as focus, sensor quality and compression also matter.

### 4. Raster and Vector Images

Another important distinction was between raster and vector images.

- **Raster images:** These are made up of a fixed grid of pixels. Photographs and scanned documents are common examples. When enlarged beyond their original dimensions, they can become pixelated.
- **Vector images:** These use mathematical descriptions of shapes, lines and curves. They can be resized without losing their sharpness.

This helped me understand why photographs are usually stored as raster images, while logos, icons and illustrations are often created using vector graphics.

### 5. Different Image Formats

We explored different image formats and how each one is designed for particular purposes.

- **JPEG:** Commonly used for photographs. It uses lossy compression, which reduces file size by removing some image information.
- **PNG:** Uses lossless compression and supports transparency, making it useful for logos, icons and screenshots.
- **GIF:** Supports a limited colour palette and can store multiple frames to create simple animations.
- **BMP:** A bitmap format that stores image data in a relatively straightforward way. It can result in large files, particularly when uncompressed.
- **TIFF:** Often used in professional photography, scanning, publishing and scientific imaging because it supports high-quality image storage.
- **SVG:** A vector format that represents graphics using mathematical shapes and paths rather than a fixed grid of pixels.

I realised that there is no single image format that is best for every situation. The choice depends on whether we need smaller file sizes, transparency, animation, scalability or high-quality image storage.

### 6. Lossy and Lossless Compression

Image compression is used to reduce the amount of storage space required by an image.

We discussed two main types:

- **Lossy compression:** Some image information is permanently removed to reduce the file size. JPEG is a common example. Repeatedly saving an image using lossy compression can gradually reduce its quality.
- **Lossless compression:** The image can be compressed without permanently losing its original information. PNG is a common example.

This helped me understand why compression is important when uploading images to websites, sharing photographs or storing large collections of images. Smaller files generally require less storage and less data to transfer.

### 7. RGB Colour Model

We studied the RGB colour model, which stands for Red, Green and Blue. These three colour channels are combined through additive colour mixing to produce different colours on digital displays.

In a common 8-bit representation, each channel can have a value between 0 and 255.

For example:

- RGB (255, 0, 0) represents red.
- RGB (0, 255, 0) represents green.
- RGB (0, 0, 255) represents blue.
- RGB (0, 0, 0) represents black.
- RGB (255, 255, 255) represents white.

By combining different values of these channels, a display can produce millions of possible colours.

We also discussed the difference between RGB and CMYK. RGB is mainly used for digital displays, while CMYK is commonly used in colour printing.

### 8. Alpha Channel and Transparency

Apart from RGB, we explored the alpha channel, which is used to represent the opacity of a pixel.

RGBA stands for Red, Green, Blue and Alpha. In an 8-bit alpha channel:

- 0 represents completely transparent.
- 255 represents completely opaque.
- Values in between represent different levels of transparency.

A practical example is a PNG logo with a transparent background. It can be placed over different backgrounds without showing an unwanted rectangular area around it.

I found this concept useful because transparency is commonly used in graphic design, application interfaces, games and web development.

### 9. Colour Depth and Bit Depth

Bit depth refers to the number of bits used to represent pixel information or an individual colour channel.

For example, an 8-bit grayscale image can represent 256 intensity levels, ranging from 0 to 255.

A standard 24-bit RGB image uses 8 bits for each of its three channels:

8 bits (Red) + 8 bits (Green) + 8 bits (Blue) = 24 bits.

This allows approximately 16.7 million possible colour combinations.

I also learned that scientific images may use 16-bit or even 32-bit representations to preserve a wider range of intensity information. This is particularly useful when small differences in intensity are important for analysis.

### 10. Binary Representation of Image Data

Since computers work with binary data, images are also represented using combinations of 0s and 1s.

The colour or intensity information of every pixel is ultimately stored as digital data. For example, an 8-bit grayscale pixel can have a value between 0 and 255, and each possible value can be represented using eight binary digits.

This helped me connect the concept of image representation with the way computers store and process information internally.

### 11. Bits Within a Byte

We also discussed how bits are arranged within a byte. One byte contains 8 bits, and each bit can have a value of either 0 or 1.

In conventional binary notation, the rightmost bit is called the Least Significant Bit (LSB), while the leftmost bit is the Most Significant Bit (MSB). Each position contributes a different value to the overall number.

I understood that bits are the basic building blocks of digital information and are important not only in image storage but also in networking and general data processing.

### 12. Big Endian and Little Endian

Another topic was byte ordering, which explains how computers arrange the bytes of multi-byte values in memory.

There are two common approaches:

- **Big Endian:** The most significant byte is stored first.
- **Little Endian:** The least significant byte is stored first.

For example, consider the hexadecimal number `0x12345678`.

- Big Endian: `12 34 56 78`
- Little Endian: `78 56 34 12`

This concept is important when working with binary files, file formats and communication between different computer systems.

I also understood that byte ordering and the order of bits within an individual byte are two separate concepts.

### 13. Image Storage and Memory Representation

We explored how much memory an image requires depending on its dimensions, number of colour channels and bit depth.

For example, a 100 × 100 pixel image using 24-bit RGB representation requires:

100 × 100 × 3 = 30,000 bytes of raw pixel data.

This calculation does not include file headers, metadata or other storage overhead.

It helped me understand why high-resolution images require more memory and why compression is useful when storing or transferring images.

### 14. Grayscale Images and Intensity Levels

A grayscale image contains different shades of grey instead of separate red, green and blue colour channels. Each pixel represents an intensity value.

In an 8-bit grayscale image:

- 0 represents black.
- 255 represents white.
- Values between them represent different shades of grey.

We also explored how a colour image can be converted into grayscale. One commonly used method calculates the intensity using weighted contributions from the RGB channels:

\[
Gray = 0.299R + 0.587G + 0.114B
\]

This gives different weights to the three channels, with green contributing the most. Grayscale images are particularly useful in medical imaging, document scanning and scientific research.

### 15. Image Histograms

One of the most interesting concepts for me was the image histogram.

A histogram is a graphical representation of how pixel intensity values are distributed throughout an image. For an 8-bit grayscale image, it generally contains 256 intensity levels, ranging from 0 to 255.

The horizontal axis represents the intensity values, while the vertical axis represents the number of pixels with each intensity.

A histogram can give us an idea of the overall appearance of an image:

- A histogram concentrated towards the left indicates a larger number of dark pixels.
- A histogram concentrated towards the right indicates a larger number of bright pixels.
- A histogram spread across a wider range generally indicates a wider distribution of intensity values.

Colour images can also have separate histograms for their red, green and blue channels.

I found this interesting because it showed me that we can understand certain properties of an image by examining numerical information rather than relying only on how the image looks.

### 16. Brightness, Contrast and Dynamic Range

We connected histograms with three important image properties: brightness, contrast and dynamic range.

- **Brightness:** Describes how light or dark an image appears. Increasing brightness generally shifts pixel intensities towards higher values.
- **Contrast:** Describes the difference between lighter and darker regions. An image with low contrast may appear dull, while higher contrast makes these differences more noticeable.
- **Dynamic range:** Refers to the range between the darkest and brightest information an image can represent or capture.

A histogram can help identify whether an image uses only a small portion of its available intensity range.

These concepts are useful in photography, image enhancement, medical imaging and scientific analysis.

### 17. Histogram Equalization

Histogram equalization is an image enhancement technique used to improve contrast.

Sometimes an image has most of its pixel values concentrated within a small intensity range, making it appear dull or unclear. Histogram equalization redistributes intensity values to make better use of the available range.

It uses the cumulative distribution of pixel intensities to perform this transformation.

For example, a low-contrast photograph may become clearer after histogram equalization because differences between intensity levels become more noticeable.

I also learned that this technique is useful in areas such as medical imaging, satellite image processing and computer vision. However, it can sometimes make noise more visible, so it may not be suitable for every image.

### 18. Histogram Normalization and Contrast Stretching

We also explored histogram normalization and contrast stretching.

Contrast stretching expands the range of pixel intensities so that darker and brighter regions become easier to distinguish. For example, if an image uses intensity values mainly between 50 and 180, contrast stretching can map those values across a wider range.

I understood that histogram normalization and equalization are related but different techniques. Normalization generally rescales intensity values, whereas equalization uses the distribution of intensity values to redistribute them.

### 19. Image Thresholding and Segmentation

Thresholding is a technique used to separate objects from their backgrounds based on pixel intensity.

For example, if we choose an intensity threshold of 128, pixels below that value can be classified as black and pixels above it as white. This produces a binary image.

Thresholding is useful in document scanning, object detection, medical image analysis and cell counting.

We also discussed segmentation, which is a broader process of dividing an image into meaningful regions or objects. Thresholding is one method that can be used to perform segmentation.

### 20. Image Filters and Convolution

We explored how filters can be used to modify pixel values and change the appearance of an image.

Some common filters include:

- **Blur filter:** Reduces sharp details and makes an image appear smoother.
- **Sharpen filter:** Makes edges and details more noticeable.
- **Grayscale filter:** Converts a coloured image into different shades of grey.
- **Edge detection:** Identifies boundaries between different regions.
- **Median filter:** Helps remove certain types of noise while preserving edges better than simple averaging.

We also explored convolution, which is a mathematical operation commonly used in image processing. It uses a small matrix called a kernel that moves across an image and calculates new pixel values using neighbouring pixels.

Different kernels can produce different effects, such as blurring, sharpening and edge detection.

This helped me understand that image filters are not simply visual effects. They involve calculations performed on the pixel values of an image.

### 21. Image Noise and Noise Reduction

Image noise refers to unwanted variations in pixel values that affect image quality. It can occur due to low lighting, camera sensors, electronic interference or other limitations during image capture.

Two types of noise discussed were:

- Gaussian noise
- Salt-and-pepper noise

Different filters can help reduce noise. For example, a median filter is often useful for reducing salt-and-pepper noise, while Gaussian smoothing can reduce certain types of high-frequency noise.

This is particularly important in medical imaging and scientific photography, where unwanted variations can affect how an image is interpreted.

### 22. Image Processing and Its Applications

Image processing involves performing operations on digital images to improve their quality or extract useful information.

We explored how it is used in different fields:

- **Medical imaging:** Analysing X-rays, MRI scans and CT scans.
- **Satellite imaging:** Studying geographical areas, vegetation and environmental changes.
- **Security:** Processing images captured by surveillance systems.
- **Agriculture:** Identifying plant diseases and analysing crop conditions.
- **Photography:** Improving brightness, contrast, colours and sharpness.
- **Computer vision:** Helping computers identify objects, patterns and other visual information.

This showed me that image processing is not limited to editing photographs. It is also an important part of scientific research and automated systems.

### 23. Introduction to ImageJ

We were also introduced to ImageJ, an image-processing and analysis software commonly used in scientific research.

Unlike ordinary image-editing software, ImageJ is not only used to change the appearance of an image. It also allows users to extract numerical information and perform measurements.

Some of its features include:

- Opening and displaying different image formats.
- Converting colour images into grayscale.
- Measuring image dimensions and pixel values.
- Viewing image histograms.
- Adjusting brightness and contrast.
- Applying filters and thresholding.
- Measuring areas, distances and intensity values.
- Analysing multiple images.
- Using plugins to extend its functionality.

I found ImageJ interesting because it connects many of the theoretical concepts discussed in class with an actual tool used for image analysis.

### 24. ImageJ: Histograms and Image Analysis

One of the useful features of ImageJ is its histogram analysis tool.

It allows users to examine how pixel intensity values are distributed throughout an image. For example, by opening a grayscale image and viewing its histogram, we can observe how many pixels have different intensity values.

This can help identify whether an image is too dark, too bright or has low contrast.

Another useful feature is the ability to select a Region of Interest (ROI) and analyse only that specific part of an image.

For example, while studying a microscopic image, a researcher might want to measure the intensity of a particular cell instead of analysing the entire image.

I understood that this makes image analysis more systematic because measurements can be taken from selected regions rather than relying only on visual observation.

### 25. ImageJ: Filters, Measurements and Plugins

We also explored some of the other tools available in ImageJ.

- **Filters:** These include smoothing, sharpening, edge detection and noise reduction.
- **Measurements:** ImageJ can measure properties such as area, mean intensity, standard deviation and minimum and maximum pixel values, depending on the selected settings.
- **Thresholding:** Users can select pixels within a particular intensity range to identify objects or regions.
- **Plugins:** These extend the software's capabilities and can be used for additional scientific measurements and automated image processing.

For example, in biological research, ImageJ can help count cells, measure microscopic structures and analyse fluorescence intensity.

This helped me understand how software tools can make image analysis more organised and measurable.

### 26. ImageJ and Scientific Applications

ImageJ has applications in several areas of scientific research.

In biology, it can be used to analyse microscopic images and measure cells and tissues. In medical research, it can help researchers examine image intensity and identify particular regions. It can also be used in neuroscience to analyse brain images and microscopy data.

In material science, ImageJ can help measure particles, pores and other structural features.

I found it interesting that a single software tool can be used across such different research areas, depending on the type of image and the information being studied.

### 27. Image Processing Using JavaFX

Through additional reading related to JavaFX, I explored how image processing can also be performed through programming.

JavaFX provides several classes for working with images:

- **Image:** Used to load an image from a file or another source.
- **ImageView:** Used to display an image in a JavaFX application.
- **PixelReader:** Used to read the colour values of individual pixels.
- **PixelWriter:** Used to modify pixel values.
- **WritableImage:** Used to create or modify an image programmatically.

For example, a programmer can use PixelReader to access the RGB values of a particular pixel and then modify those values to create an effect such as grayscale conversion.

This helped me connect the theoretical understanding of pixels and colour channels with actual programming concepts.

### 28. Image Transmission, Binary Data and Wi-Fi

We also connected binary data with networking and wireless communication.

When we share an image through Wi-Fi or the internet, it is represented as digital data. This data is organised into packets and transmitted through a communication system. Wireless communication uses radio signals to transfer information between devices.

I explored how networking involves concepts such as binary representation, encoding, transmission and error detection.

This helped me understand that the same binary information used to represent an image is also involved in transferring it between computers and mobile devices.

## Reflection

This topic helped me understand digital images from a perspective that I had not really considered before. Earlier, I mostly thought of an image as something we capture, save or edit. I had not thought much about the amount of numerical information involved in representing even a simple picture.

I found the topics related to pixels, RGB values, alpha channels and bit depth particularly useful because they helped me understand how computers actually represent colours and visual information. The discussion about binary data, bytes and memory representation also connected image processing with concepts from computing that we have been learning throughout the course.

The topic I found especially interesting was image histograms. I liked how a graph could tell us so much about an image without us having to examine every pixel individually. Understanding brightness, contrast, intensity distribution and histogram equalization helped me realise that image quality can be studied and improved through mathematical operations.

Exploring ImageJ was another useful part of the learning process. It showed me how concepts such as histograms, thresholding, filters and pixel measurements can be applied using an actual software tool. I also found the idea of selecting a particular region of an image for analysis interesting, especially because it has applications in areas such as biology and medical research.

The connection with JavaFX made the topic feel more relevant to programming. Learning about PixelReader and PixelWriter showed me that it is possible to access and modify individual pixels through code. It made me curious about how more complex image-processing operations could be developed using programming.

Overall, this topic helped me look beyond the visual appearance of images and understand the processes involved in forming, storing, processing, analysing and transmitting them. It also showed me how concepts that might initially seem very technical have practical applications in photography, medicine, agriculture, scientific research and computer vision.
