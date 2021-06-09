# Facial_key_point_recognition
Facial Key Point recognition model will able to detect some key features from images likes Eyebrow , Lips ,Eye

#### Table of content 
1. Introduction
2. Model structures
3. Results

### Introduction :
Detecing facial keypoints is a very challenging problem.  Facial features vary greatly from one individual to another, and even for a single individual,<br>
there is a large amount of variation due to 3D pose, size, position, viewing angle, and illumination conditions. Computer vision research has come a long way<br>
in addressing these difficulties, but there remain many opportunities for improvement<br>

<p><strong><u>The objective of this task is to predict keypoint positions on face images. This can be used as a building block in several applications, such as:</u></strong><p>
<ul>
<li>tracking faces in images and video</li>
<li>analysing facial expressions</li>
<li>detecting dysmorphic facial signs for medical diagnosis</li>
<li>biometrics or face recognition</li>
</ul>The data set for this problem was graciously provided by Dr. Yoshua Bengio of the University of Montreal. James Petterson.
<br>
<h4>Data Description :</h4>
<p>Each predicted keypoint is specified by an (x,y) real-valued pair in the space of pixel indices. There are 15 keypoints, which represent the following elements of the face:

left_eye_center, right_eye_center, left_eye_inner_corner, left_eye_outer_corner, right_eye_inner_corner, right_eye_outer_corner, left_eyebrow_inner_end, left_eyebrow_outer_end, right_eyebrow_inner_end, right_eyebrow_outer_end, nose_tip, mouth_left_corner, mouth_right_corner, mouth_center_top_lip, mouth_center_bottom_lip

Left and right here refers to the point of view of the subject.

In some examples, some of the target keypoint positions are misssing (encoded as missing entries in the csv, i.e., with nothing between two commas).

The input image is given in the last field of the data files, and consists of a list of pixels (ordered by row), as integers in (0,255). The images are 96x96 pixels.</p>

<p style='color:blue;'> you can download data from (https://www.kaggle.com/c/facial-keypoints-detection/data).</p>
<h3> Model structures:</h3>
<p> I am trying different combination (CNN + DNN ) architectures , The most well performed model is in my IPYNB Notebook You can Check this out for model building <br>
 Here is the link (https://github.com/Nirajsah17/Facial_key_point_recognition/blob/main/Facial_key_point_recognition_model.ipynb).
</p>
<h3>Results</h3>
<p><strong>Training Imaes with key points</strong></p>
<img src='https://github.com/Nirajsah17/Facial_key_point_recognition/blob/main/images/trainpoints.jpeg'width='1000'height='300'/>
<br>
<p><strong>Test  Imaes with key points</strong></p>
<img src='https://github.com/Nirajsah17/Facial_key_point_recognition/blob/main/images/testImg.jpeg'width='1000'height='300'/>
