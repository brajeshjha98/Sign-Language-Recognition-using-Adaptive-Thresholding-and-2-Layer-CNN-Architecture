
# Sign Language Recognition using Adaptive Thresholding and 2-Layer CNN Architecture
This project two layers of CNN model classifier and predicts the meaning of sign gestures of 26 English alphabets with 95.7% accuracy. However, we can add more sign gestures to it and enhance its capability.

## Aim of the Project
The main aim of our project is to help the those type of people in the society who are speech impaired and hearing impaired (People who can’t listen).


This project tends to decrease the dependency on the translator and can act as bridge to decrease the communication gap between the normal person and hear or speech impaired person.


The project only requires readily available resources for its implementation, therefore no any matter of cost. For our project we have used our PC camera as hardware to capture images.

## Project Break-Up and Workflow
This project is divided into 4 parts:
![image](https://user-images.githubusercontent.com/48770985/180646977-045157af-befa-4701-ada7-c1c8908a7222.png)

1. Input Data Creation: Since there is no any dataset available on different dataset repositories (e.g. UCI ML Repository, Kaggle, etc.), we decided to develop our own dataset. This can be done using input.py file.

2. Pre-processing: After the creation of the dataset, there are lot of features in our images e.g. color of the image, background, these are not required for the further processing. Moving forward with all these features can decrease the efficiency and accuracy of the model drastically. This can be done using preprocessing.py file.

3. Model Training: Once the data is ready, the next important task is to train the model. We have decided to for Covolutional Neural Network (CNN) as it is known for its image classification capabilities. We have used 2-layer CNN architecture in order to improve the accuracy of the model. This can be done using models file.

![image](https://user-images.githubusercontent.com/48770985/180647049-3ddbba0c-3f2b-4ef5-87e5-338ccb675c4b.png)


4. UI and Project Output: Finally user interface is developed using tkinter library of python and model predicted the expected output.

## Project Ouput

https://user-images.githubusercontent.com/48770985/180647430-3cf37a8f-17f4-48f7-a953-86c528c66e32.mp4

## Publication
The paper on this project had been selected in MHRD funded International Conference on Emergent Converging Technologies and Biomedical Systems (ETBS-2021). The conference paper had been published by popular publisher Springer Nature in its popular book series Lecture Notes in Electrical Engineering (ISSN NO: 1876-1100) which is indexed in international databases Scopus and ESCI.

![image](https://user-images.githubusercontent.com/48770985/180647142-b04edf82-8921-4cef-a75c-8b27ca607978.png)


Link to the publication: https://link.springer.com/chapter/10.1007/978-981-16-8774-7_29
