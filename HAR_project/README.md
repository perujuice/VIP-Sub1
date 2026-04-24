# OVERVIEW
- This is just the initial repo for classifying low-level human activity recognition

# Transfer learning - Models and Research

- <a href="https://openaccess.thecvf.com/content_ICCV_2019/html/Feichtenhofer_SlowFast_Networks_for_Video_Recognition_ICCV_2019_paper.html">SlowFast Networks for Video Recognition</a>
    - Code: https://github.com/facebookresearch/SlowFast
- <a href="https://arxiv.org/pdf/1705.07750">I3D models trained on Kinetics</a>
    - Code: https://github.com/google-deepmind/kinetics-i3d

# Classes
- Walking
- Fast walking (Only if possilbe to find it)
- Running
- Standing

# venv init


# Datasets

<a href="https://www.kaggle.com/datasets/sharjeelmazhar/human-activity-recognition-video-dataset">HAR dataset made my some guy with 7 classes </a>

So far this is the decent data set that is relatively clean!


# Refined GOALS

- Find relevant reserach papers on HAR from video, preferably with atomic movements (walking, running, standing) in indoor environments and real time recognition
    - 2020-2025

Here is how almost every real-time indoor walking classifier works today:
- Detect person
- Estimate pose
- Track pose across frames
- Feed sequences of joints (x, y or x, y, z) into a temporal model
- Classify action (walking, standing, running)