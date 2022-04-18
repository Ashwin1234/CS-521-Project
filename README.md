# Documentation

## Advanced Neural networks for Fake News detection

## Dataset

We're using Liar dataset, it has 12.8K short sentences collected from Politifact.com.
You can find the dataset in the below link with its preview and summary
https://huggingface.co/datasets/liar

The dataset contains six fine-grained labels to determine truthfulness pants-fire, false, barelytrue, half-true, mostly-true, and true.
The distribution of labels in the LIAR dataset is relatively well-balanced, the instances almost all labels range from 2063 to 2638.

### Main Feature:
  Statement
### Meta data:
  Subject
  Speaker
  Party Affiliation
### Target Feature:
  0 (False), 1(Half true), 2(Mostly True), 3(True), 4(Barely True), 5(Pants Fire)


In the code we load it from huggingface by using there "datasets" library.

## How to run

The code is published in Google collab, there are some installations to do in the beginning.
Running the first set of code modules will import all necessary libraries and install required dependencies.
Just follow along by running module by module.

We recommend switching to GPU since it will be faster and take less time for the model to train.

