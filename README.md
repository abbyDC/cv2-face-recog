# Facial Recognition with OpenCV
This repository contains the scripts used to create a facial recognition demo app.

Referenced from [Facial Recognition OpenCV (Github)](https://github.com/ageitgey/face_recognition)

This example was used for the demo in my talk, Google Women Techmakers Manila 2021:  "Behind the Scenes: The AI Life Cycle"

Accompanying slides can be found here: [Google Slides Link](https://drive.google.com/drive/folders/1eOMa453oEpT-ee883zlriBrHvsiRK5HI?usp=sharing)

## I. Project Setup

1. Creating python virtual env

```bash
$ python3 -m venv ~/venvs/[name_of_env]

e.g.
$ python3 -m venv ~/venvs/fr
```
2. Activating python virtual env

```bash
$ source ~/venvs/[name_of_env]/bin/activate

e.g.
$ source ~/venvs/fr/bin/activate
```

3. Install the project's requirements

```bash
$ pip3 install -r requirements.txt
```


### II. Video Inference

1. Upload your video in the `vids` folder

2. Change the path/filename in `facerec_from_video_file.py` for the input video and output

3. Make sure to change the number of frames and resolution before running the script

4. Run the script

```
python3 facerec_from_video_file.py
```

5. Your video output should be inside the `outputs` folder
