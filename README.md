# Code-for-On-Multiple-Image-Group-Cosegmentation

The code can be downloaded from 

https://www.researchgate.net/profile/Fanman_Meng/publication/316274004_Code_for_On_Multiple_Image_Group_Cosegmentation_papers_of_CVIU_2016_and_ACCV_2014/data/58f86b700f7e9bfcf93c1aeb/code-cosegmentation.rar

This is a simplified code to cosegment foregrounds from two set of images: simple image set and complicated image set. Simple image set contains images with simple backgrounds. Complicated image set contains images with complicated backgrounds.

The code is tested on 64-bits Windows system and matlab 2016.

If you use the code, please cite papers as follows:
1) Fanman Meng, Jianfei Cai, Hongliang Li, Cosegmentation of multiple image groups，Computer Vision and Image Understanding, vol. 146, 2016: 67~76
2) Fanman Meng, Jianfei Cai, Hongliang Li, On Multiple Image Group Cosegmentation, 2014 Asian Conference on Computer Vision, ACCV 2014, Singapore, 2014.11.1-2014.11.5

Please run main.m to segment foregrounds from images in “\img\simple\” and “\img\complex”.

Input: the simple image set and the complicated image set.
Output: the foregrounds of all images.

If you implement the code on new images, please 
1) Put JPEG images of simple image set in folder “\img\simple\”, 
2) Put JPEG images of complicated image set in folder “\img\complex”，
3) Run main.m

Note that the code assumes that the foregrounds share similar color. Other features are not considered here.
Please run '.\graph_cut\compile_gc.m' for re-compiling the .cpp files.
