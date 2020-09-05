# Repo to keep demo code of TensorFlow Extended (TFX) for TensorFlow India Summit

* Download on local system using ``` git clone https://github.com/tensorflow/tfx.git ```

* Prerequisites
  - Linux / MacOS
  - Virtualenv
  - Python 3.5+
  - Git

* What We are doing
  - We are learning how to create an ML pipeline using TFX
  - TFX pipelines are appropriate when you will be deploying a production ML application
  - TFX pipelines are appropriate when datasets are large
  - TFX pipelines are appropriate when training/serving consistency is important
  - TFX pipelines are appropriate when version management for inference is important
  - Google uses TFX pipelines for production ML
  
  
* You are following a typical ML development process

  - Ingesting, understanding, and cleaning our data
  - Feature engineering
  - Training
  - Analyze model performance
  - Lather, rinse, repeat
  - Ready for production

* We are using the Taxi Trips dataset released by the City of Chicago.

* Model Goal - Binary classification
  - Will the customer tip more or less than 20%?
  
* AirFlow is Pipeline Orchestrator
