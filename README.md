# Finding Lanes

## Canny edge detection

![canny](https://miro.medium.com/max/469/0*z3xwM8n6hNzf3QTX.png)

## Hough Transform

![hough](https://miro.medium.com/max/656/0*Do2hBBRZ2QbKzKQm.png)

![polar](https://docs.opencv.org/2.4/_images/Hough_Lines_Tutorial_Theory_0.jpg)
![sinusoidal](https://docs.opencv.org/2.4/_images/Hough_Lines_Tutorial_Theory_2.jpg)

Line in polar co-ordinates and sinusoidal that represent point , intersection point represent line.

More on Hough line transform in [OpenCV doc](https://docs.opencv.org/2.4/doc/tutorials/imgproc/imgtrans/hough_lines/hough_lines.html)

## Mask

![mask](https://miro.medium.com/max/469/0*ry_cLrSFwJz-H0z9.png)

## Result
**Without Area Selection(unMasked)**
![unmasked](https://miro.medium.com/max/469/0*Uzsmhv9BFErbew5u.png)

**Suitable Area Selection(Masked)**
![masked](https://miro.medium.com/max/469/0*C4yj-8OD02StLSqn.png)


## Resources

* https://github.com/naokishibuya/car-finding-lane-lines
* https://github.com/liamondrop/finding-lane-lines
* https://github.com/PooyaAlamirpour/FindingLaneLines
* https://medium.com/swlh/self-driving-car-finding-lane-lines-4d9f405df368
* https://towardsdatascience.com/finding-lane-lines-simple-pipeline-for-lane-detection-d02b62e7572b
