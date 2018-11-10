# HF4
This is the repository for the 4th homework.
I flattened the output of a pretrained xception network and connected it to a dense layer containing 2 neurons. First I trained only the last layer and freezed the feature extractor. Then I unfreezed some of the last layers of the base model and fine tuned it.
The network is trained for classifying cat and horse pictures.
I recommend running the scripts on Google Colab.
