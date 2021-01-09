# stanford_dogs_vision_classification
The project was the practice of the MDLI computer vision course, delivered by the the [**MDLI forum**](https://www.facebook.com/groups/MDLI1/) leaders. The purpose of the course was to learn the foundations of deep-learning, specifically computer vision, and is purely based on the [**Stanford CS231n course**](http://cs231n.stanford.edu/).

The project was done together with my course coleague [**Michael Mandelbaum**](https://github.com/githmm).

The dataset we used was the [**Stanford Dogs Dataset**](http://vision.stanford.edu/aditya86/ImageNetDogs/main.html), that includes 120 different classes (breeds), and also has labels for object-detection boxes. Initially we planned to do the project in two phases: first pure classification and then object-detection. However eventually the object-detection phase was not completed, but we do have the basics done.

Our aim was to experiment as many features as poosible, for example:
- Use an experimant management system (we used the [**nuptune.ai**](https://neptune.ai/) platform)
- Building different networks
- Pre-trained models
- Early stopping
- Trying out various hyperparameters
- Trying out various augmentaitons
- Use a trained model for predicting new images

The classifications folder contains the following selected notebooks:
1. **dogs_image_exploration_2020-04-13**: getting familiarized with the dataset
2. **dogs_IT_16.4.20_basic_classification_prediction**: one of the networks we built from scrach
3. **dogs_IT_16.4.20_basic_classification-EarlyStopping**: implementing an early-stopping mechanism
4. **dogs_IT_17.4.20_alexnet-AUGMENT**: we implemented the alexnet, and added some augmentations
5. **dogs_IT_02.05.20_RESNET-Copy1**: using a pre-trained RESNET net

The object_detection folder contains one notebook:
- **prepare_data_for_OD_IT_19.9.2020**: creating the daateset class and the rest of the features for a basic run
