# Implement-OpenCV
The Repository contains some useful code that implements with OpenCV and C++  

I refer to the [Authoritative Code](https://github.com/opencv/opencv),it helps me a lot,and it's also great if you are willing to help me

improve my code,There are more information about the OpenCV on my [CSDN BLOG](http://write.blog.csdn.net/postlist)

# INTRODUCTION

## 1.DftAndIdft.cpp
It's a application or `DFT` and `IDFT`. Firstly, I trnsfer the picture from time domain to frequency domain

by `DFT`, And In frequency domain, process all the pixels,lastly,tansfer the picture back to time domain

by `IDFE`. the original picture I use is the moive,[lalaland 's advertisement](https://github.com/LiangjunFeng/Implement-OpenCV/blob/master/Picture/DftAndIdft/lalaland_1.jpeg) 

the reslut, source image:

  
  ![](https://github.com/LiangjunFeng/Implement-OpenCV/blob/master/Picture/DftAndIdft/Source%20Image.png)
 


the reslut, Amplitude spectrum:

  
  ![](https://github.com/LiangjunFeng/Implement-OpenCV/blob/master/Picture/DftAndIdft/Amplitude%20spectrum.png) 
 


the reslut, reconstructed image:


  
  ![](https://github.com/LiangjunFeng/Implement-OpenCV/blob/master/Picture/DftAndIdft/reconstructed%20image.png) 


the result, Pro Amplitude spectrum:

  
  ![](https://github.com/LiangjunFeng/Implement-OpenCV/blob/master/Picture/DftAndIdft/Pro%20Amplitude%20spectrum.png) 
  
