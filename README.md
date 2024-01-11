# Social Media Misogyny Comparison

## Overview

This project investigates the differences in misogyny and sexism in comments from Facebook and Reddit News. It aims to understand how varying levels of anonymity on these platforms influence such behavior.

## Dataset

The analysis utilizes two datasets:
1. Facebook news comments from 2017.
2. Reddit comments from r/UpliftingNews from 2017.
Both datasets were randomly sampled to evaluate 5000 comments each for misogyny and sexism.

## Dependencies

- Python with libraries for data analysis and machine learning (e.g., Pandas, NumPy, scikit-learn).
- Pre-trained machine learning models from Hugging Face, used for misogyny and sexism detection.

## Structure

The notebook is structured as follows:
1. Data loading and preprocessing.
2. Application of misogyny and sexism detection models.
3. Analysis and comparison of results between Facebook and Reddit.

## Results

The key findings include:
- Facebook comments showed higher rates of misogynistic comments (7%) compared to Reddit (4.7%).
- Both platforms had less than 1% sexist comments, with Facebook slightly higher.
- Overall, Facebook tends to be more misogynistic and sexist than Reddit.
- However, both platforms have content moderation, so these numbers only contain messages that have not been removed by moderators. This will have an unknown impact on the percentages of misogynistic and sexist comments. 
