# AppleStore
This Project reflects the work of "Using Apple Store Dataset to Predict User Rating of Mobile Applications"
https://www.researchgate.net/publication/335383461_Using_Apple_Store_Dataset_to_Predict_User_Rating_of_Mobile_Applications 
by Kevin Daimi and Noha Hazzazi

Evaluation:
The model get the same performance mentioned in the work of Kevin Daimi and Dr. Hazzazi. There may notice slightly difference in coefficient correlation values and in Errors calculation due to use different framework. In that paper, the scholars implemented the work using Weka and I used python programming using Jupiter Notbook.

Here I basically showed if one more feature, sup_devices.num can be removed from train data then there will no significant change occurs in performance. Even performance will increased by 0.6% but runtime decreased as the model need not to train an extra feature.

Open Apple.ipynb file to view code and evaluations
