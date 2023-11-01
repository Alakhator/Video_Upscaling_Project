# Video_Upscaling_Project
This Repository contains files for Assignment 4 which contains the following task- 

The primary goal of this assignment is to showcase your proficiency in developing an
advanced AI model capable of enhancing the quality of a video by upscaling its
resolution and reducing noise. Your task entails harnessing the capabilities of any
suitable and available model to achieve significant improvements in video quality,
particularly by increasing its resolution and eliminating unwanted noise.

IMPLEMENTATION - Used a pretained model of video2x (https://github.com/k4yt3x/video2x)  to generate output which included upscaling upto 180x and noise reduction with threshold 3. Each step is explained in logical manner in ipynb file and is easily reproducible with minor changes in input and output path to drive. The preprocessing requires GPU so did on google colab which provides free session upto 12 hrs which is more than enough to produce output of files with limit of 30 mins per session.

INPUT - Three demo files which are provided in the link - https://gdrive.openinapp.co/3qr0x

OUTPUT - Output to corresponding test input are uploaded in repository as well in google drive with link - https://drive.google.com/drive/folders/1D6zoaME0UGOz8f3nx8l__LPaBuK4POu0?usp=sharing

PERFORMANCE - Performance metric screenshot of pre-trained model is provided as would require GPU resouces to calculate the metric so not done directly in this task as lack of resources to train the model. 

FUTURE WORK - The output produced is with best pretrained-model - "SMRD" for now. Trying on different model and training model by hand on GPU and calculating the performance metric is the future work.

I hope my work satifies the requirement of skills you are looking for as an intern of AL/ML. I would love your feedback on wether I understood the problem corretly and what I could have done more in time limit that was provided from your end. Thank You!
