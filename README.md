# Godseye Social Distancing Monitor
An AI tool to prevent spreading of coronavirus (COVID-19) by using computer vision on video surveillance. A social distancing analyzer AI tool to regulate social distancing protocol using video surveillance of CCTV cameras and drones. Social Distancing Analyser to prevent COVID19
Optimized for running in CPU and weaker processors


## Instructions to Run
Install dependencies  
```	pip install -r requirements.txt ```  

Edit the [config file](https://github.com/HacKP-CyberDome/godseye-social-distancing/blob/7461ce2e04ffc1ec4d82c70abf9bb53369ffce80/social-distance-detector/detect/social_distancing_config.py) with the model details and [model path](https://github.com/HacKP-CyberDome/godseye-social-distancing/blob/7461ce2e04ffc1ec4d82c70abf9bb53369ffce80/social-distance-detector/detect/social_distancing_config.py#L2)

To use in python program, simply import the *social_distance_detector.py*](https://github.com/HacKP-CyberDome/godseye-social-distancing/blob/master/social-distance-detector/social_distance_detector.py) file, and use the function *social_distancing* for prediction.

![socialdistancing gif](https://github.com/vishnuexe/Social-Distancing-AI/blob/master/socialdistancing.gif)

 

