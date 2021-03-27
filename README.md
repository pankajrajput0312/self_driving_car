# self_driving_car
The problem seems to be quite complex, and that is truth as well. This project shows solution just to a part of this problem. We will be feeding sequences of images from dashcam and this model will predict the steering angle in degrees.

## Model insight
1. The steering angle was in degrees and it was converted into radians first.
2. The model was designed with basic CNN, Flatten, Dense and Dropout Layers.
3. The activation used in inner layers was relu
4. The activation used in output layer was tanh. (I tried for Linear Activation as well but tanh produced someway better results)
5. Dropout layers were added for regularization and to prevent overfitting.
6. The model predicted the value of steering angle in radians so later it was converted back to degrees.

## Loss function

## Sample Video
 ![alt text][gif]
 
 [gif]: https://github.com/pankajrajput0312/self_driving_car/blob/master/demo_gif.gif "GIF"


*The visualization is strictly on Test Data
 
