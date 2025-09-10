# Food-Recognition-Engine-Deployed-with-Streamlit

## What will I end up with?

If you go through the below, you should end up with a [Streamlit](http://streamlit.io/)-powered web application (Food Vision) for classifying images of food (deployed on Google Cloud if you want).

Our app running locally making a prediction on an image of ice cream (using a machine learning model deployed on Google Cloud):
![food vision demo](https://github.com/mrdbourke/cs329s-ml-deployment-tutorial/raw/main/images/food-vision-demo-cropped.gif)

## Okay, I'm in, how can I use it?

We're going to tackle this in 3 parts:
1. Getting the app running (running Streamlit on our local machines)
2. Deploying a machine learning model to AI Platform (getting Google Cloud to host one of our models)
3. Deploying our app to App Engine (getting our app on the internet)

### 1. Getting the app running

1. Clone this repo
```
git clone https://github.com/mrdbourke/cs329s-ml-deployment-tutorial
```

2. Change into the `food-vision` directory
```
cd food-vision
```

3. Create and activate a virtual environment (call it what you want, I called mine "env")
```
pip install virtualenv
virtualenv <ENV-NAME>
source <ENV-NAME>/bin/activate
```
4. Install the required dependencies (Streamlit, TensorFlow, etc)
```
pip install -r requirements.txt
```
5. Activate Streamlit and run `app.py`
```
streamlit run app.py
``` 

This is Food Vision 🍔👁 the app we're making.

6. Try an upload an image (e.g. one of the ones in [`food-images/`] such as [`ice_cream.jpeg`]( and it should load.

7. Notice a "Predict" button appears when you upload an image to the app, click it and see what happens.




