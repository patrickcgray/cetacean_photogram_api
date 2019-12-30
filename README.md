# Cetacean Photogrammetry API

This API allows a user to upload aerial images of whales and they will be automatically identified by species and photogrammetrically measured. Currently the model is trained on humpback, blue, and minke whales. If you have imagery of additional species we would be thrilled to add these species to this model.

This API implements the model from the Methods in Ecology and Evolution manuscript "Drones and Convolutional Neural Networks Facilitate Automated and Accurate Cetacean Species Identification and Photogrammetry", available at https://doi.org/10.1111/2041-210X.13246

All data necessary to reproduce this work is available at http://doi.org/10.5061/dryad.7482v2n and the code is available at https://github.com/patrickcgray/cetacean_photogram.

This work is supported by Microsoft AI for Earth (https://www.microsoft.com/en-us/ai/ai-for-earth) and is running in Azure Container Instances (https://azure.microsoft.com/en-us/services/container-instances/). 

![Humpbacks identified and measured](https://github.com/patrickcgray/cetacean_photogram_api/blob/master/data/humpbacks_measured_from_drone.jpg?raw=true)

