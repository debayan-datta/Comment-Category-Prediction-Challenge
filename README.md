# Comment Category Prediction Challenge

## Overview

This repository contains my solution for the Kaggle Comment Category Prediction Challenge.

The goal of this competition is to predict the final category assigned to user-generated comments using textual content, engagement signals, emoticon indicators, and platform-generated metadata.

The problem is formulated as a 4-class classification task, where each comment must be assigned to one of four possible labels.
________________________________________

## Dataset Description

The dataset contains comments submitted to an online discussion platform along with metadata and hidden platform-generated features.

Available Files
-	train.csv - Training data containing all features and target labels.
-	test.csv - Test data containing all features except the target label.
-	sample_submission.csv - Sample submission file in the required format.

## Feature Description

| Feature        | Description                               |
| -------------- | ----------------------------------------- |
| `comment`      | Raw text content of the comment           |
| `created_date` | Date and time when the comment was posted |
| `post_id`      | Unique identifier for the associated post |
| `emoticon_1`   | Presence indicator for emoticon group 1   |
| `emoticon_2`   | Presence indicator for emoticon group 2   |
| `emoticon_3`   | Presence indicator for emoticon group 3   |
| `upvote`       | Number of positive reactions              |
| `downvote`     | Number of negative reactions              |
| `if_1`         | Hidden platform feature 1                 |
| `if_2`         | Hidden platform feature 2                 |
| `race`         | Identity-related topic indicator          |
| `religion`     | Religion-related topic indicator          |
| `gender`       | Gender-related topic indicator            |
| `disability`   | Disability-related topic indicator        |
| `label`        | Target variable (0–3)                     |

________________________________________
Repository Structure
```
.
├── train/
│   ├── train_1.csv
│   ├── train_2.csv
│   ├── train_3.csv
│   ├── train_4.csv
│   ├── train_5.csv
│   └── train_6.csv
│
├── test/
│   ├── test_1.csv
│   ├── test_2.csv
│   └── test_3.csv
│
├── comment_kaggle_comp.ipynb
├── README.md
└── sample_submissiom.csv
```
