# Requirements

- [Machine learning](#machine-learning)
  * [Must have](#must-have)
  * [We recommend you](#we-recommend-you)
  * [Nice to have](#nice-to-have)
    + [Workflow ready in google cloud (*Required for cloud training*)](#workflow-ready-in-google-cloud---required-for-cloud-training--)
  * [Workshop](#workshop)
- [IoT](#iot)
  * [Must have](#must-have-1)
  * [We recommend you](#we-recommend-you-1)
  * [Nice to have](#nice-to-have-1)
- [Fan Experience](#fan-experience)
  * [Must have](#must-have-2)
  * [Nice to have](#nice-to-have-2)
  * [Workshop](#workshop-1)


## Machine learning

You have all the pip requirements in the requirements.txt file.
```bash
$ pip3 install -r requirements.txt
```

### Must have

- [python 3.x](https://www.python.org/downloads/)
- pip3

### We recommend you
- [virtualenvwrapper](http://virtualenvwrapper.readthedocs.io/en/latest/install.html) *If you are using windows powershell it might not work unless you run it with CMD*
- [tensorflow](https://www.tensorflow.org/install/)*

**We recommend you to install it with pip3 (install tensorflow-gpu if you have cuda on your machine)*

**In the workshop you will be learning to work with Keras (running on top of TensorFlow, CNTK, or Theano). You need TensorFlow to run as backend or CNTK, or Theano.*

### Nice to have

- [gcloud](https://cloud.google.com/sdk/downloads?hl=en) *Required for cloud training*
- [gsutil](https://cloud.google.com/storage/docs/gsutil_install) *Required for cloud training*
- [floydhub-cli](https://github.com/floydhub/floyd-cli)
- [Keras](https://keras.io/#installation)
- [cuda 8](https://developer.nvidia.com/cuda-80-ga2-download-archive) *Only if your computer can manage it*
- [cudnn](https://developer.nvidia.com/cudnn) *Only if you managed to install cuda on your system*

#### Workflow ready in google cloud (*Required for cloud training*)

Set up your GCP project.

1. Select or create a Cloud Platform project. [GO TO THE MANAGE RESOURCES PAGE](https://console.cloud.google.com/cloud-resource-manager)

2. Enable the Cloud Machine Learning Engine and Compute Engine APIs. [ENABLE THE APIS](https://console.cloud.google.com/flows/enableapi?apiid=ml.googleapis.com,compute_component)

### Workshop

- [ ] Being smarter than AI (Friday after lunch)
- [ ] Train your models in the cloud (Friday after lunch)

## IoT

### Must have

- Electronics (basic level)
  - Some hardware will be provided. We'll give some workshops about some of them but definitely we won't teach you how to light a LED
- [Arduino](https://www.arduino.cc/)

*Note*: Desktop apps **may** be accepted in some cases. If this is your case talk with the captain of the challenge before any coding!

### We recommend you
- Mobile development. One of
  - [Android](https://developer.android.com) + [Android Studio](https://developer.android.com/studio/index.html?)
  - [iOS](https://developer.apple.com/) + [Xcode](https://developer.apple.com/xcode/)

### Nice to have

- You're free to bring your own hardware :)
- You may want to add some backend to your projects. In this case [Docker](https://www.docker.com/) will be much appreciated

## Fan Experience

### Must have

- Creativity :bulb:

### Nice to have

- As already mentioned, [Docker](https://docs.docker.com/install/) or [Docker-Toolbox](https://docs.docker.com/toolbox/) (for legacy systems) installed should be a must for a good deployment. More on that at the workshop

### Workshop
- Applications deployment & APIs management
