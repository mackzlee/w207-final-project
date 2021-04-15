# w207-final-project
Final project for W207
April 2021

- The planet_api.ipynb notebook contains the code to download satellite images from the Planet API
- The 207_AIS_Query.ipynb notebooks contains the full code to preprocess the image data, train and optimize a model on the data to predict ship/no-ship, apply the model to the satellite imagery, compare model results to real-world vessel tracking data.
- The Relabeled_tiles folder contains the images from the [Kaggle ship dataset] (https://www.kaggle.com/rhammell/ships-in-satellite-imagery) that were relabelled to ship if there was even an incomplete ship shown.
- sfbay_1.png contains a scene image from the Kaggle dataset from which the smaller tiles used in the ship dataset are used
- planet.png contains a tiled image the Planet API satellite image.
- the elegant-weaver-287722-1c18abef2983.json file contains information used to connect the 207_AIS_Query.ipynb notebook to Google Cloud data. 

Mackenzie Lee, EJ Haselden, Yao Zhao