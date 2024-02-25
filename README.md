# Digital Image Processing 
## Semester Project
## JPEG Compression and Decompression

### :man: Participants:
Hammad Rashid   19L-1007    CS-6A

Salman Arshad   19L-2386    CS-6A

### :wrench: Language
<b>Python</b>

### Libraries used:

```python
import numpy as np
import cv2              # dct to cv2
import math             # math functions such as sin, cos, tan, abs
import heapq
import struct           # struct class to import the properties of struct
import tkinter as tk
from tkinter import filedialog, messagebox
from PIL import Image
```

### Functions
```python
def jpeg_compress(image, quality)
def jpeg_decompress(packed_bytes, quant_matrix)
def psnr(image1, image2)
def compression_image_handler()
def decompression_image_handler()
def psnr_image_handler()
```

### Challenges
1. The first challenge was to see how to read the image
2. The second challenge was to select the appropriate method for compression. We chose Huffman Coding
3. The third challenge was the psnr value
4. The forth challenge was the decompression method. Although it was the reverse of compression, yet still it was a big challenge
5. The fifth challenge included a way to show all the input on the gui

### Solution
1. For reading the file, we took help from Google and got to learn about OpenCV library
2. We chose Huffman coding since it was easier to implement and we had done it previously
3. psnr value was calculated using formulas
