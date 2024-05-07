# Gym Congestion Analysis Project

## Introduction
This project aims to analyze gym congestion based on survey responses and swipe data. We'll explore various factors such as gender distribution, preferred gym zones, and perceived congestion.

## Setup
This project is implemented in a Jupyter Notebook using Python 3. Required libraries include pandas, numpy, matplotlib, seaborn, and datetime.

## Data Import
We import data from the following sources:
- Survey responses from "Fitness & Rec Survey 2024!!! (Responses) - Form Responses.csv"
- Swipe data from two Excel files for fall and spring semesters.

## Data Cleaning
- Remove student identifiers and irrelevant columns.
- Filter out rows where gender is not Male or Female.
- Exclude specific dates representing breaks.

## Data Merging
We merge the swipe data from fall and spring semesters to predict total year congestion.

## Analysis
### Affiliation
We analyze the distribution of survey respondents by affiliation.

### Average Male vs Female Weekly Swipe Frequency
We compare the average swipe frequency of males and females throughout the week using swipe data.

### Male vs Female Average Daily Swipe Time
We compare the average daily swipe time of males and females throughout the week using swipe data.

### Male vs Female Gym Zone Usage
We analyze gym zone usage based on survey responses, comparing male and female preferences.

### Students Who Believe Gym is Congested
We visualize survey responses regarding students' perception of gym congestion.

### Overlay Model: Time of Day vs Gym Congestion
We aim to chart congestion levels of different gym zones throughout the day, overlaying swipe data with survey responses.
