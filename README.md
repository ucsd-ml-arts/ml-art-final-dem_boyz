# Final Project

Mikhail Kardash, mkardash@ucsd.edu

Sean Liu, sel118@ucsd.edu

## Abstract Proposal

Does music make the video, or is the visual medium not influenced much by a musical one? In other words, can we treat music as a latent space for a music video? Our final project attempts to answer these questions by converting music videos downloaded from Youtube and taking spectrograms of 5 seconds of audio to generate video frames based on those spectrogram input images.  The final goal of this project is to create a music video with the images created.  

## Project Report

Upload your project report (4 pages) as a pdf with your repository, following this template: [google docs](https://docs.google.com/document/d/133H59WZBmH6MlAgFSskFLMQITeIC5d9b2iuzsOfa4E8/edit?usp=sharing).

File: Music_Video_Generation_using_Pix_to_Pix.pdf

## Model/Data

video_list_final.txt: list of music videos trained
pix2pix-tensorflow: folder to train network

## Code

Your code for generating your project:
- Jupyter notebooks: ECE_188_Test_Code.ipynb

## Results

  Movie.mp4, Movie200.mp4 represent produced music video results (see paper); gifs of images generated from previous all number of epochs trained are also included

## Technical Notes
Running the Jupyter notebook should install everything necessary to run; some variables and video downloading software will require the user to change the youtube video link (in video_list_final.txt) or the number (0-10 for oof)

## Reference
[1] Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros “Image-to-Image Translation with Conditional Adversarial Networks” 26 Nov 2018
