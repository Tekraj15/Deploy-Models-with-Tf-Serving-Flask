# Deploy Models with TensorFlow Serving and Flask

# Project Overview 
This project deploys the TensorFlow models using TensorFlow Serving and Docker and then creates a web application with Flask which will serve as an interface to get predictions from the served TensorFlow model.

i.e.
-Serve a TensorFlow model with TensorFlow Serving and Docker.

-Create a web application with Flask to work as an interface to a served model.

# Prerequisites 
Python, TensorFlow, Flask, and HTML.


# Implementation Workflow

# 1. Introduction

# 2. Getting Started with the Flask App
 -We will create a basic, functional web app with Flask

# 3. Index Template
-We will add a template for the index page.
 We will add a base template which extends a Bootstrap base template

# 4. TensorFlow Serving
 -We will create a docker instance with TensorFlow Serving image.
 We will deploy and serve our binary classifier model in the docker instance

# 5. Getting Predictions
 -We will write a module which sends post request to the model server with input image tensor.
  The module will also post process the predictions obtained from the model server.

# 6. Connecting the Model Server to App
 - We will create functionality in our to be able to upload an image files.
 We will import the inference module created previously in the app, and get predicted class for the uploaded image.

# 7. Displaying the Results
  - Finally, we will create a show.html template, where we will display the uploaded image along with its predicted class.
