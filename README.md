# PClub-CV-Submission
Dataset Zip File: https://drive.google.com/file/d/1MlsVVpVVmpsunIp1JtAje4O2jPoWY9mq/view?usp=sharing
Found the dataset online through the youtube video: https://youtube.com/watch?v=ofSbYUIfjEw
Approach was to convert the images into array and fit using knn unsupervised learning model

First roadblock - how to convert image to array - countered with np.asarray() function
Second roadbloack - resizing the images because all images were of different size - tried np.resize() but no success
Then rethought the about the above roadblocks and countered them with cv2.imread() and cv2.resize() functions respectively then flattened all the arrays and appended to a master ImageList
Then since the data was not labelled, therefore had to use unsupervised learning and the easiest one was knn and thus implemented it via the sklearn library. The RAM on google collab is limited therefore could not fit much data points into the knn model and thus fitted only 100 data points. 

## For running the code
1. download the zip file from drive
2. create a "Mask Pics" folder in the google colab
3. extract the zip file and upload all the pics to Mask Pics folder
4. Run all the cells and follow along for any inputs required. Can check for different inputs for running the cell again and again.
![image](https://github.com/Bhavnoor-Coders-1010/PClub-CV-Submission/assets/73211684/3d7d0795-1024-405b-ae06-b3c582a5700b)
![image](https://github.com/Bhavnoor-Coders-1010/PClub-CV-Submission/assets/73211684/67c1d613-92c5-4c82-b3ce-c9b9f02e7b78)

link to google collab: https://colab.research.google.com/drive/13uus7mpwP6KSH9te9w8qVDDTFJATrzVA?usp=sharing (it is suggested to use the google collab link for seeing outputs)
