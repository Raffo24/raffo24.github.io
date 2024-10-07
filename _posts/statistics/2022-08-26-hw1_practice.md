---
title: Homework 1 - Practice
classes: wide
date: 2024-10-06 01:27:00 +0200
header:
  teaser: /assets/images/blog/statistics/hw1.png
ribbon: MidnightBlue
layout: hw1_practice
categories:
  - Statistics
toc: true
---

## Core Function

This is the core function of the program, which executes the following steps:
1. **Input Validation**: The function performs validation on the input to prevent potential errors and bugs.
2. **Array Population**: It populates the `servers` and `hackers` arrays with sequential numbers.
3. **Dataset Generation**: Using the `getDataset` function (which will be discussed later), it generates the dataset.
4. **Maximum Breach Calculation**: It extracts the highest number of breaches performed by a single hacker from the dataset.
5. **Interval Selection**: Based on a series of conditions, it determines the number of intervals to divide the breaches into.
6. **Interval Window Calculation**: It calculates the window size for each interval based on the total number of breaches and the selected number of intervals.
7. **Dataset Division**: The dataset is then divided into the relevant intervals for histogram plotting and distribution calculation.
8. **Empty Space Removal**: Any leading empty spaces in the histogram are removed to ensure accurate visualization.
9. **Plotting**: Finally, the program generates both the Flat Line Graph and the histogram for visual analysis.

## Dataset Generation