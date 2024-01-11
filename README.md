This is the final project of 2023 fall SI100B course in Shanghaitech. Our mission is to take a photo, recoginize all the handwritten digits, and show the results with a 7-segment-display.
The whole system is based on Raspberry Pi 3 Model B+, camera Rev 1.3. We used the OpenCV library to do the image processing and training with the help of KNN algorithm. 
The model was trained based on the MNIST and stored in TrainingData. The image processing part, more precisely, the "split image" part was in my_function.py
Our final result varied from 80% accuracy to 95% accuracy. 
