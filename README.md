# Object_Recognition

Object_Recognition
 
This is a Object_Recognition appilication with Matlab. 



## Methods


I used Point Feature Matching methods for my Object recognition.

I detect a specific object based on finding point correspondences between the reference and the target image. It can detect objects despite a scale change or in-plane rotation. 

This method of object detection works best for objects that exhibit non-repeating texture patterns, which give rise to unique feature matches. This technique is not good at detect uniformly-colored objects, or for objects containing repeating patterns.This algorithm is aim to detect a specific object.

It find strongest feature points of training image and testing image to see whether two image are similar with each other or not. It depend on the number of matching pair of feature points. 

The weakness of this method is how to tell the training object is the testing object. and the number of matching pair of feature points is always changing in different image. what is the  boundary number of matching pair. This program always cost a lot of time to detect and recognize the object.

Use estimateGeometricTransform matlab toolbox to locate the object in the image, Get the bounding polygon of the testing image.

I detect the testing object with training image of different object one by one. Each object have many training image. find out the maximum matching point pair of each object. and once the pair number is bigger than boundary, it could be considered that training object is in the testing image. and so on. Finally calculate the object number and display the location of object with line.  


This program also referred to the example of matlab official website 
Ref:  https://www.mathworks.com/help/vision/examples/object-detection-in-a-cluttered-scene-using-point-feature-matching.html

## Comparisons

Object comparisons: compare with different object. I found that the bigger object would be easy to detect. In this project. book and bottle are easy to detect. sugar and clip is diffcult to detect. 
stapler is a unique and speicial scale. so staper is easy to detect.

if the object is behind the keyboard. it would be hard to detect because the background make the program confuse a lot. 

method comparisons: compare to the other method. Point Feature Matching is not too good but it can be used in some simple object detection.  
this method contains : object detection ; object recognization; object  orientation； multi-object dection;

## Discussion

Some testing image are hard to detect. For example, some object is hide from other object. It is really hard to detect evan I (human vision) can not tell what is it immediately. 
The program is still need to improve.  I did not leave too much comment in the source code because I did it in two days, so it would be a liitle bit hard to understand my program.



Author: key




-----

## Screenshots

![scr01](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr01.png)
![scr02](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr02.png)
![scr03](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr03.png)
![scr04](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr04.png)
![scr05](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr05.png)
![scr06](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr06.png)
![scr07](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr07.png)
![scr08](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr08.png)
![scr09](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr09.png)
![scr10](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr10.png)
![scr11](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/scr11.png)



**If you like this, please leave a star.**

-----

## Sponsorship
Feel free to support me for no reasons via Wechat Pay or Alipay with QR code below



![wechat pay](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/wechatpay.png)
![alipay](https://github.com/tavik000/Object_Recognition/raw/master/Screenshots/alipay.jpg)




## Contact



Email:  tavik002@gmail.com

-----

**All Copyright Reserved**


