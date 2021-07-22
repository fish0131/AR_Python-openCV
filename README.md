# AR_Python-openCV
To add a 3D model aligned (orientation and translation) to a predefined flat surface.

Basic Structure：
1. Prepare Data
2. Read Data
3. Recognize Data
4. Homography
   
   ![螢幕擷取畫面 2021-07-22 221514](https://user-images.githubusercontent.com/68525727/126654640-f0e56c81-5940-4531-853a-19a27f4a5041.png)
   
   A homography is a 3×3 matrix we can write it as
   
   ![image](https://user-images.githubusercontent.com/68525727/126655385-3b00ca35-5650-4366-a0b2-741debc586df.png)

   Let us consider the first set of corresponding points — (x_1,y_1) in the first image and (x_2,y_2)} in the second image. Then, the Homography H maps them in the following way
   
   ![image](https://user-images.githubusercontent.com/68525727/126655580-e33fa933-d826-442e-9eac-41eca3a02f4e.png)

   
6. Pose Estimation
7. Display

Reference：
1. https://www.twblogs.net/a/5efeb915e53eaf40aa87305b
2. https://towardsdatascience.com/estimating-a-homography-matrix-522c70ec4b2c
