# Handwritten Character Recognition

Recognition of handwritten characters is crucial for enhancing human-computer interaction. 
Due to the vagueness and unevenness of each person's writing styles and strokes, the task could be difficult. 
Additionally, the potential for a poor source image quality makes the work more difficult.

***Objective*** <br>
To interpret the scanned or uploaded images of handwritten texts.

***Abstract*** <br>
We have proposed a CNN architecture that uses keras as an interface for tensorflow library. 
The model has been validated for english as well as devanagari scripts. 
Dataset put-to-use for english is ‘EMNIST_ByClass’ [1] and for devanagari is ‘devanagari handwritten character dataset - DHCD’ [2]. 
The model achieved 87.20% accuracy for EMNIST_ByClass and 98.19% accuracy for DHCD dataset.

***Dataset*** <br>
[1] Hindi Devnagari <br>
Train Dataset: https://drive.google.com/file/d/1CF_yZE9eymS0smvs0zU0XPq1chQoCUcf/view?usp=share_link <br>
Test Dataset: https://drive.google.com/file/d/1TdjvPsPXvELJx70y16j2_6dnOGSthbtS/view?usp=share_link <br>
[2] EMNIST Byclass <br>
Train Dataset: https://drive.google.com/file/d/1lG7r9hGCecHS0lzb-k9j8m1MwwnBnAHo/view?usp=share_link <br>
Test Dataset: https://drive.google.com/file/d/1kYAHb25BD9QDEYVDymrBGLwOTL1Z4PQZ/view?usp=share_link <br>

***References*** <br>
[1] G. Cohen, S. Afshar, J. Tapson and A. van Schaik, "EMNIST: Extending MNIST to handwritten letters," 2017 International Joint Conference on Neural Networks (IJCNN), 2017, pp. 2921-2926, doi: 10.1109/IJCNN.2017.7966217. <br>
[2] Acharya, Shailesh et al. “Deep learning based large scale handwritten Devanagari character recognition.” 2015 9th International Conference on Software, Knowledge, Information Management and Applications (SKIMA) (2015): 1-6.
