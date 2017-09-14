# **Finding Lane Lines on the Road** 

[image1]: ./test_images_output/solidWhiteCurve.jpg "Lane Lines"

For Finding Lane Lines on the Road, I used OpenCV and Python

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Pipeline used the following techniques
1. Color Conversion
2. Canny Edge Detection
3. Blurring Images
4. Region of Interest Detection
5. Hough Transformation for Line Detection

Using the pipeline we can find the lane lines on both individual images and video clip.

[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I .... 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text][image1]


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
