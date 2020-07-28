# Deploy Models with TensorFlow Serving and Flask

# Project Overview 
In this project we deploy TensorFlow models using TensorFlow Serving and Docker, and will create a simple web application with Flask which will serve as an interface to get predictions from the served TensorFlow model.

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

# 6. Connecting to Model Server


# 7. Displaying the Results
