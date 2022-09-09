# Binary Vehicle Classifier

The EDA, model development, and evaluation of a binary image classifier to detect emergency vehicles.

## Getting started

There are several notebooks that contain starter code for the model and also explains the dataset version that was used to train a binary emergency vehicle classifier. The dataset and weights reside on the EC2 instance called `Training_Big_Boy`. To ssh into this instance, you will need the justin_training_gpu.pem file, which can be found in an S3 bucket called `lokoai-it-security`.

There are several notebooks in this repo, but the two most important are listed below:
- `emergency_vehicle_eda.ipynb` contains EDA related to the emergency_vehicle dataset
- `emergency_vehicle_model_dev.ipynb` has starter code to building the model and loading data
- `yolo_plus_emergency_dev.ipynb` a PoC to see the results of linking a pre-trained yolo model to the emergency vehicle classifier. Results weren't satisfactory.

## Next Steps

A simple way to improve the models performance is to switch to a much more powerful SSD model, such as CLIP. Example code for using CLIP as a single shot detector is located in the `CLIP_dev.ipynb`

