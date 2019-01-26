# NAAMI First Nepal Winter School in AI

## Excercises from lab session.

### Day 1:
    - Essential matrix using 8 points method.
    
### Day 2:
    - Python basics (numpy and matplotlib)
    
    Run this code to upload your CSV file to colab:
    ```
    from google.colab import files
    uploaded = files.upload()
    ```
    
### Day 3:
    - Linear Regression
    - Logistic Regression
    - Image Segmentation using k-means
    
    Instead of cv2.imshow() please use the following 3 lines of code:
    ```
    cv2.imwrite(‘1.jpg’,img)
    from google.colab import files
    files.download(‘1.jpg’)
    ```
    
### Day 4:
    - Principle component analysis (PCA)
    - 3D reconstruction from 2D images