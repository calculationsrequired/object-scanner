# neutralbot version.alpha
This bot will take a face image as input, classify it as one of eight emotions; neutral, anger, contempt, disgust, fear, happy, sad and surpise. 
The bot will then attempt to stop the displayed emotions with either pictures, videos, or textual informations. 
### Problems
There were issues training the network to have a decent validation and test accuracy. The best I got with this network is about 75%. For the real-world images, the bot is actually quite terrible at classifying the emotions. Much work will have to be done for sure.
### Data Set Details
Cohn-Kanade Extended (CK+) Facial Expression dataset. Dataset contains posed and unposed stills of people's faces going through an emotion. 
### Architecture of Model
Three Convolutional layer with three dense layer. 
### Software
Tensorflow, Keras, PIL, cv2 
### Collaboration
This will be a one-person project. 
## References
ImageNet Classification with Deep Convolutional Neural Networks by Alex Krizhevsky
DeXpression: Deep Convolutional Neural Network for Expression Recognition by Peter Burkert et al.
Automated Face Analysis by Feature Tracking and Expression Recognition by Zeming Li

- Kanade, T., Cohn, J. F., & Tian, Y. (2000). Comprehensive database for facial expression analysis. Proceedings of the Fourth IEEE International Conference on Automatic Face and Gesture Recognition (FG'00), Grenoble, France, 46-53.
- Lucey, P., Cohn, J. F., Kanade, T., Saragih, J., Ambadar, Z., & Matthews, I. (2010). The Extended Cohn-Kanade Dataset (CK+): A complete expression dataset for action unit and emotion-specified expression. Proceedings of the Third International Workshop on CVPR for Human Communicative Behavior Analysis (CVPR4HB 2010), San Francisco, USA, 94-101.
