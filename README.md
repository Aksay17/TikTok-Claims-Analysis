# TikTok Data Analysis

This repository contains data analysis and exploration of TikTok data, aimed at gaining clear insights to prepare for a claims classification model. The analysis is focused on understanding the characteristics of TikTok posts, user behavior, and trends in order to inform the development of an effective claims classification system.

## Table of Contents

- [Introduction](#introduction)
- [Data Source](#data-source)
- [Insights](#insights)
- [Next Steps](#next-steps)
- [Contributing](#contributing)

## Introduction

TikTok has become a popular social media platform where users share short videos. With the increasing amount of content on TikTok, there is a need to analyze the data to gain insights and improve the user experience. This repository aims to perform data analysis on TikTok data with a specific focus on preparing for a claims classification model.

## Data Source

The data used for this analysis is sourced from Google's certification Getting Started with Python. It consists of a large collection of TikTok posts, including metadata such as video descriptions, hashtags, user information, engagement metrics, and more.

## Insights

Based on the data analysis, several insights can be derived, including:

We know that videos by banned authors and those under review tend to get far more views,
likes, and shares than videos by non-banned authors. However, when a video does get viewed, its
engagement rate is less related to author ban status and more related to its claim status.

Also, we know that claim videos have a higher view rate than opinion videos, but this tells us that
claim videos also have a higher rate of likes on average, so they are more favorably received as well.

Furthermore, they receive more engagement via comments and shares than opinion videos.

Note that for claim videos, banned authors have slightly higher likes/view and shares/view rates
than active authors or those under review. However, for opinion videos, active authors and those
under review both get higher engagement rates than banned authors in all categories.

Returning to the purpose of this analysis, at this point in the investigation it seems that engagement level is
strongly correlated with claim status, and this should be a focus of further inquiry.
These insights will help in understanding the TikTok ecosystem and provide a foundation for building a claims classification model.

## Next Steps

The analysis performed in this repository serves as a starting point for preparing a claims classification model. The next steps may include:

- Feature engineering to extract relevant features for claims classification.
- Building and training a claims classification model using machine learning techniques.
- Evaluating and fine-tuning the model's performance.
- Deploying the claims classification model for real-time analysis.

## Contributing

Contributions to this repository are welcome. If you have any suggestions, improvements, or would like to add additional analyses, please feel free to submit a pull request.
