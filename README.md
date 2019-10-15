# Weed Detection in Soybean crops

This repository demonstrates the use of a 2 layer neural network that is able to classify and detect weeds in soybean crops. 

No libraries except ```numpy``` have been used. 

## Dataset

From the set of images captured by the UAV, all those with occurrence of weeds were selected resulting a total of 400 images. Through the Pynovisão software, using the SLIC algorithm, these images were segmented and the segments annotated manually with their respective class. These segments were used in the construction of the image dataset.

[Link](https://www.kaggle.com/fpeccia/weed-detection-in-soybean-crops) to the dataset.

This image dataset has 15336 segments, being 3249 of soil, 7376 of soybean, 3520 grass and 1191 of broadleaf weeds.

## Contributors
I made this repository as no github repository exists for this code, however most of the code is from [this](https://www.kaggle.com/datduyn/2-layer-net-on-weeds-discriminant) kaggle notebook.

## License
[MIT](https://choosealicense.com/licenses/mit/)