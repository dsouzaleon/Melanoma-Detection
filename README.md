# Melanoma detection
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Business Understanding
- The objective is to build a CNN based model which can accurately detect melanoma and thus reduce the manual effort needed in diagnosis
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Adding in augmented images reduced the gap between the training and validation numbers while improving the accuracy across both.
    - The train accuracy was increased to 92.5% while the validation accuracy was increased to 80%.
    - Though we did rid of some of the overfitting but increasing the training data to 500 per class, we could probably add in more variations to the images in order to improve the validation accuracy.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- tensorflow
- matplotlib
- google.colab
- Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was created by Leon Richard D'souza as part of curriculum by IIIT-B ML & AI course


## Contact
Created by [@dsouzaleon] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->