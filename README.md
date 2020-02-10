# light-field-raindrop-dataset

Light field raindrop dataset was collected with the first generation Lytro camera.
The dataset contains 90 light field raindrop images that cover different camera angles and scenes.
For each image, we provide the light field source file, reference image, and reference depth map given by the Lytro software.
The light field source file can be easily decoded by the light field toolbox (https://github.com/doda42/LFToolbox).

An example is shown as follows:

<div align=center><img src="https://github.com/cavayangtao/light-field-raindrop-dataset/blob/master/example.png" width="300" height="100"/></div>

We collected raindrop images with glass plate, window of train, and window of car.
The camera is placed 10 to 15 cm in front of the glass plate and windows.

The first 40 images (part1) in our dataset cover different situations evenly.

The last 50 images (part2) are was collected with the UTBM robocar. The Lytro camera was held in the car by the author, and the corresponding GPS information was also recorded. As shown on the right side in the figure below, the route of data collection is the same as the 
EU long-term dataset (https://epan-utbm.github.io/utbm_robocar_dataset/).

<div align=center><img src="https://github.com/cavayangtao/light-field-raindrop-dataset/blob/master/fig13.jpg" width="500" height="200"/></div>

A summary of our dataset is given as follows:

<div align=center><img src="https://github.com/cavayangtao/light-field-raindrop-dataset/blob/master/overview.png" width="300" height="100"/></div>

The white images of our Lytro camera, which are used for decoding, can be download by the link:

https://drive.google.com/open?id=1qawMlA9HXgS1rpyre60szcjY6SgEt5ct

Part 1 of light field raindrop images：

https://drive.google.com/open?id=1713MB_a7YkbmDgLQ0jw8sQBG5SmZYlkn

Part 2 of light field raindrop images：

https://drive.google.com/open?id=1-HZKDogCwTOXa7ZaMJ8KVG3cH_ohaFrp

## Citation
If you publish work based on, or using, this dataset, we would appreciate citations to the following:

    @misc{lia_corrales_2015_15991,
        author       = {Tao Yang, Xiaofei Chang, Hang Su, Nathan Crombez, Yassine Ruichek, Tomas Krajnik, and Zhi Yan}},
        title        = {{Raindrop Removal with Light Field Image Using Image Inpainting}},
        year         = 2020,
        }


