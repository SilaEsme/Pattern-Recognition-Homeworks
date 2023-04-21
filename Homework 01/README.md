# Homework 1

## About the Assignment

The main purpose of the homework is to obtain some basic information about the images.

Pre-Information
The originals of the pictures are in the homework file. Use the pictures given to you while doing your
homework. First read images and then plot .
bullet

1. Start by reading the pictures. While reading, you must give the file path with the pictures in the code. The image size is 224x224x3.
`img1 = plt.imread('cat1.jpg')`
2. If you want to see the pictures on the screen, use the `plt.imshow(img1); plt.show()` function.
3. These graphics should be drawn separately for each picture. You can use plot() function to
draw graphs and show() functions to show them.
4. The show() function in pyplot module of matplotlib library is used to plot something.
You can access a pixel values of a color image: `R,G,B = img[0,0,:]`

### Task1

- Read the image given in Fig. 2.
- You are expected to apply the following color transformation to each pixel coordinate.
- You can use for loops.
- Firstly, convert image from RGB2YIQ with for loops.
- Secondly, convert image from YIQ2RGB with for loops.

### Task2

You are expected to apply the following rotations to images.

- flips cat and dog images vertically
- flips cat and dog images horizontally
- rotates cat and dog images to left by 90 degree3
- rotates cat and dog images to right by 90 degree
- resizes cat and dog images to half by keeping aspect ratio
- finally, displays input and output images
