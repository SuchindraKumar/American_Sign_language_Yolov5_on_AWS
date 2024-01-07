# YOLO web app


# ASL_to_English

Reads your hand signs and translates them to English words using Tensorflow object detection API
The model is built using transfer learning from pretrained model ssd_mobilenet model
The dataset is made manually by running the Image Collection python file that collects images from your webcam for all the mentioned below signs in the American Sign Language :

* Hello ✋
* I Love You 💙
* Thank you 😺
* Please 🥺
* Yes ✔️
* No ❎

### Created an  environment
```
conda create -p venv python=3.8 -y

```

### Activate the Created environment

```
conda activate venv/
```
### Install all necessary libraries
```
pip install -r requirements.txt
```
