---
date: 2021-01-05 02:20:00
title: GDSC
subtitle: ' Google Developers Korea'
image: /uploads/logo-4osui1m.webp
---
**![](/uploads/152697208-03dabce6-8076-46d1-b9e5-772f0130014a.png){: width="1440" height="810"}**

The team received the GDSC 2022 Hackathon Encouragement Award for their project which involved using Google Maps to provide the location of garbage cans around users and image classification through garbage image recognition using Tensorflow light. The team consisted of three people and the development period was from December 2021 to February 2022. As for my contribution, I supervised the Figma design and managed the frontend and Github, while also handling the Tensorflow image set data preprocessing and grouping.

GISTREE is a waste management app that provides users with the location and classification of nearby waste bins to facilitate proper waste disposal. The app also includes an image analysis algorithm for waste classification using TensorFlow Lite, which determines the type of waste and the corresponding waste bin location. Additionally, the app encourages proper waste disposal by providing rewards for using waste bins through a contract with local stores.

![](/uploads/152628073-71b0ae87-e0f3-40cc-b9dd-7d2b2437517b.png){: width="483" height="770"}

GISTREE is developed using Flutter, Android Studio, and VSCode. The app uses GCP Google Maps API and TensorFlow Lite as plugins. The machine learning model used is an Xception pre-trained model by ImageNet, followed by a dense layer with Adam optimizer with a learning rate of 0.001, categorical cross-entropy loss function, reduce LR on plateau by a factor of 0.2, and early stopping. The model was trained on 20k images from Kaggle datasets of nine classes of waste, including battery, biological, clothes, glass, metal, paper, plastic, trash, and vinyl.

The app aims to overcome the problem of waste management, which is a global issue that is increasing with the decline of waste bins on the streets. With the use of GISTREE, users can easily locate and dispose of their waste properly, thereby increasing the recycling rate and creating a natural civic awareness of waste management.

**👉 [발표 자료](https://docs.google.com/presentation/d/1BYM6dSDJ316SanmksXI4EOa_JRGtUbes/edit?usp=sharing&amp;ouid=113505121437939793776&amp;rtpof=true&amp;sd=true)**

**👉 [Trash Flash Figma](https://www.figma.com/file/IHAzxyMOTAWKCcmP7Oj4Cv/GDSC-%EC%93%B0%EB%A0%88%EA%B8%B0%ED%86%B5-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8?node-id=0%3A1)**