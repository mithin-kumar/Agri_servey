# Agri_servey

Agriculture servey is a computer vision projects which is aimed to know the crop area, number of greenhouses in a locality from the images taken from satilette.

Problem Statemet : Given a statlite image of the area. we need to use computer vision technology to identify the crop area,number of  greenhouses, cattle burn, buildings etc.

Our Approach : Firtly we tried with image processing techniques to identify the boundaries but it coulded worked well because of many color varients in single type class. Then we used 
Deep learning technologies, where our task is to develop an image segamentation model  using UNet.

We have used 70:20:10 as our train test val ratio on our images.We have used Label studio for genertating annotated masks for the images.And trained our model in Google Colab
