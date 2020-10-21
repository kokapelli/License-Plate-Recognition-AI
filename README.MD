# Road Rage
This project is an experimental project created in 2018 that uses image recognition to detect license plate numbers of cars, crop them plates, run Optical Character Recognition (OCR) and finally looks up the detected license plate number on the Swedish web page [https://biluppgifter.se/](biluppgifter.se). This project is completely for experimentation purposes and does not provide anyone with any pleasure apart from having an automatic way of finding out who the asshole in front actually is. The project is not complete, the object detection from [Tensorflow](https://github.com/tensorflow/models/tree/master/research/object_detection) is currently required when performing training. 

The project is divided up into the various parts of creating and training an image recognition model. Ranging from the web scraper used to retrieve training data, pre-trained models for the image recognition, OCR and and the web page lookup itself using [Selenium](https://selenium-python.readthedocs.io/). 

**Warning**! This project is extremely convoluted and is primarily meant for my own usage and reference. 