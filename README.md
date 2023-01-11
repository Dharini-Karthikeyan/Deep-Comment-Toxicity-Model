# Deep-Comment-Toxicity-Model
Deep Comment Toxicity Model helps detect different elements of tocixity within a sentence like	toxic,	severe_toxic,	obscene,	threat,	insult,	identity_hate i.e., if a comment is classified as containing some or all of the above gradients of toxicity it will return 1(True) for those particular gradients else it will return 0(False).

# Dataset
jigsaw-toxic-comment-classification.<br>
This dataset contains 159574 comments with multiple binary outputs (comment_text,	toxic,	severe_toxic,	obscene,	threat,	insult,	identity_hate).

# Requirements
```
Pandas: 1.3.5
Numpy: 1.21.6
Tensorflow: 2.9.2
Gradio: 3.16.1
```
# Model
Saved in .h5 format.
https://drive.google.com/file/d/1Ly6G-dpH_2_JtoG3Qy7sdbyIzsHIcoRG/view?usp=share_link

# Loss Curve - Training and validation
![image](https://user-images.githubusercontent.com/84025317/211824567-bc0fe805-a59f-4cc9-b4b2-7adee2deff91.png)

# Output
Model is deployed as a web application using gradio.
![image](https://user-images.githubusercontent.com/84025317/211826299-75382469-e704-4ede-bd6f-a9f94e5ff728.png)
![image](https://user-images.githubusercontent.com/84025317/211826517-503355c6-ce1b-44dd-8b6c-7be5c89cdb41.png)
![image](https://user-images.githubusercontent.com/84025317/211826635-6a6c8920-7fb0-4a61-b6b3-bdb36f573a88.png)
![image](https://user-images.githubusercontent.com/84025317/211826739-f5eba1f2-2aaf-4b16-8a77-59a44f827a47.png)
