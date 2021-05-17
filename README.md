#### Facial-Expression-Recognition-based-on-Facial-Landmarks

# Introduction and Brief Overview
In the present project, an algorithm that classifies facial expression from raw images and videos will be developed. The dataset used to train the algorithm is the CK+ dataset containing the following emotions:
"anger", "contempt", "disgust", "fear", "happiness", "sadness", "surprise", and is cited at the bottom of this cell. The process involves four steps.
1. Importing required libraries.
2. Detection of facial landmarks and extraction of feature vectors for the CK+ dataset.
3. Application of k - Nearest Neighbors (using Minkowski instead of Euclidean distance as metric) and linear Support Vector Machines and evaluation of classification quality.
4. Test on an image and a video of myself showing different emotions.
References
[1] P. Lucey, J. F. Cohn, T. Kanade, J. Saragih, Z. Ambadar and I. Matthews, "The Extended Cohn-Kanade Dataset (CK+): A complete dataset for action unit and emotion-specified expression," 2010 IEEE
Computer Society Conference on Computer Vision and Pattern Recognition - Workshops, San Francisco, CA, USA, 2010, pp. 94-101, doi: 10.1109/CVPRW.2010.5543262.
[2] Van Gent, P. (2016). Emotion Recognition Using Facial Landmarks, Python, DLib and OpenCV. A tech blog about fun things with Python and embedded electronics. Retrieved from:
http://www.paulvangent.com/2016/08/05/emotion-recognition-using-facial-landmarks/
