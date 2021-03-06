# Covid Prediction using Xray Image

> A pretty and customizable web app to deploy your DL model with ease

------------------

## Getting started in 10 minutes

- Clone this repo 
- Install requirements
- Run the script
- Check http://localhost:5000
- Done! :tada:

:point_down:Screenshot:


<p align="center">
  <img src="ProjectPage.jpg" width="600" title="hover text">
 
</p>

------------------

## Local Installation

### Clone the repo
```shell
$ git clone https://github.com/nursnaaz/DataScience-Webinar-Inceptez-28-06-2020.git
```

### Install requirements

```shell
$ pip install -r requirements.txt
```

Make sure you have the following installed:
- Flask
- h5py
- Keras
- Keras-Applications
- Keras-Preprocessing
- numpy
- scikit-learn
- scipy
- tensorflow
- opencv-python

### Run with Python

Python 3.7+ are supported and tested.

```shell
$ python app.py
```

### Play

Open http://localhost:5000 and have fun. :smiley:


------------------

## Customization

### Use your own model

Place your trained `.h5` file saved by `model.save()` under models directory.

## Deployment

heroku

### Run the app

Run the script and hide it in background with `tmux` or `screen`.
```
$ python app.py
```

You can also use gunicorn instead of gevent
```
$ gunicorn --workers=50 --threads=20 --bind 0.0.0.0:8000 app:app
```

More deployment options, check [here](http://flask.pocoo.org/docs/0.12/deploying/wsgi-standalone/)


## More resources

Check my blog https://devskrol.com/ for more interesting topics.

Check my medium page https://aasha01.medium.com/ 



