# Visual_Recognition_Instance_Category_Recognition
## Visual Recognition Assignment "Playing with the Panaroma of IIIT-Bangalore" ,"Horse vs Bike calssification" and extending this classification to CIFAR-10 Dataset.

# Play with Panorama (of IIITB/any landmark):
• Clue: RANSAC
• cv2.ﬁndHomography(src, dst, cv2.RANSAC, 5.0)
• cv2.warpPerspective(img1, H, (img2.shape[1]+img1.shape[1], img2.shape[0]))
• Explain how SURF is diﬀerent from SIFT (10 sentences)
• Brieﬂy explain the main principles of FLANN matching and RANSAC (5sentences)
# • Implement Bike vs Horse Classiﬁcation
• Dataset: available on LMS (notes folder)
# • Use Bag-of-visual words approach (SIFT/SURF + K-means + SVM/Logistic Regression/KNN)
• Explain the procedure and your approach and observations
• Reference paper: available on LMS (notes folder)
# • Extend to CIFAR 10, with 10 classes: [link](https://www.cs.toronto.edu/~kriz/cifar.html)
