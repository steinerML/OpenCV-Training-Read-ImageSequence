# OpenCV read image sequence.
Read, Display image sequence using OpenCV
## Contents:

Processing image frames from an image sequence is very similar to processing frames from a video stream. Just specify the image files which are being read. 

| Function     |Action                                     |
|-------------:|-------------------------------------------|
|videocapture()|   Creates videocapture object             |

## Test Images used: 
Below the image sequences I used to execute the aforementioned functions:

![Source Image Sequence](https://learnopencv.com/wp-content/uploads/2021/05/image.gif)


## Summary:

```python
vid_capture = cv2.VideoCapture('Resources/Image_sequence/Cars%04d.jpg')
```