# HUSE-Hierarchical-Universal-Semantic-Embedding

## Table of Content
- Introduction
- Architecture
- Dataset
- Installation
- Library Used

### Introduction:
There is a recent surge of interest in cross-modal representation learning corresponding to images and text. The main challenge lies in mapping images and text to a shared latent
space where the embeddings corresponding to a similar semantic concept lie closer to each other than the embeddings corresponding to different semantic concepts, irrespective of
the modality. This paper proposes a novel method, HUSE, to learn crossmodal representation with semantic information. HUSE learns a shared latent space where the distance between any two universal embeddings is similar to the distance between their corresponding class embeddings in the semantic embedding space. For more details refer the pdf research file giving in the repository.

**An example universal embedding space. Cat, dog, bridge and tower classes are represented with red, green, yellow and blue colors respectively. Circles represent image embeddings and plus represent text embeddings.**

![Image+Text Embedding](https://user-images.githubusercontent.com/62636740/108584947-48806100-736b-11eb-9e79-21b169ca9fc7.PNG)


### Architecture:

The general architecture for the **VGG 16** model just to extract and train the image data 

![The-architecture-of-VGG-16-model](https://user-images.githubusercontent.com/62636740/108585041-0146a000-736c-11eb-9dec-7ef32fb3ed12.png)

The **tokenizer** we used to exatrct the text from the given data set

![Tokenizer](https://user-images.githubusercontent.com/62636740/108586513-0fe58500-7375-11eb-980b-2051a1138649.png)

After that both model can be connect to an **IMAGE TOWER** as shown in the research paper.

![Image Tower](https://user-images.githubusercontent.com/62636740/108586577-605ce280-7375-11eb-890f-83935b05de84.png)


### Dataset:-
The text data given in repository but for the image data the link will be [here](https://drive.google.com/drive/folders/1fAO0ueyAPdo09vcjP-hk2kH_bY4fpV6e?usp=sharing)

### Installation:-

These code written in [Google Colab](https://www.google.com/search?q=google+colab&oq=google+colab&aqs=chrome..69i57j35i39j0j69i60l5.5070j0j7&sourceid=chrome&ie=UTF-8)
 
 ### Library Used:-
 
![scikit-learn-logo-small](https://user-images.githubusercontent.com/62636740/91655376-bab76d80-eacd-11ea-8cb1-20ebfd11e7f3.png)

![tensorflow](https://user-images.githubusercontent.com/62636740/91655414-f7836480-eacd-11ea-9b8f-f9eada989d87.jpg)

![keras](https://user-images.githubusercontent.com/62636740/91655424-036f2680-eace-11ea-9aee-d52ddbad3af1.png)


 
