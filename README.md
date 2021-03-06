# strava-analytics
This is a personal project to improve training for cyclists using historical training data. The end goal is to provide a strava app and graphical interface for users to harness the power of their data and make decisions on their training.

The users will be provided with different data visualizations to help with their workout planning as well as predictive ML models to optimize certain aspects of their training to achieve their goals.

Below are a few features that will be implemented.

- [x] Strava OAuth login And Data Retrieval
- [ ] Historical Activity Analysis
- [ ] Ride Type Classification
- [ ] Rider Type Classification
- [ ] Cumulative Time Spent In Zone
- [ ] Fatigue Analysis
- [ ] Training Progression
- [ ] Training Load Analysis
- [ ] Individual Activity Analysis
- [ ] ML Workout Prediction For Race Preparation
- [ ] ML Personalized Workouts Based On Rider Type
- [ ] ML Personalized Workouts Based On Race Objectives

# Strava OAuth Login And Data Retrieval
Having accepted the App terms, the user accepts to share his data for analysis. The user's data is retrieved through the Strava API. Data extraction is done fully the first time to limit API calls. Then only the most recent data is retrieved in subsequent usage.

# Analytics Features

## Historical Activity Analysis
Activities for a selected timeframe are analyzed to determine different rider factors and how the rider has been training.

## Ride Type Classification
Every ride is analyzed and training impact is determined to assess rider strengths and weaknesses.

## Rider Type Classification
Based on the Ride Type Classification, a rider type profile is determined that most suits the rider.

## Cumulative Time Spent In Zone
Detailed analysis is performed to assess the physiological impact of training on the rider.

<p align="center">
  <img width="350" height="200" src="https://github.com/K-Schubert/strava-analytics/blob/main/media/cum_time_in_zone.png">
  <img width="350" height="200" src="https://github.com/K-Schubert/strava-analytics/blob/main/media/ride_time_in_zone.png">
</p>
<p align="center">
  <img width="350" height="200" src="https://github.com/K-Schubert/strava-analytics/blob/main/media/cum_time_in_zone_line.png">
</p>

## Fatigue Analysis
Fatigue is assessed through volume, power and heartrate analysis among other metrics.

## Training Progression
Different performance markers are analysed to determine whether statistically significant rider progression through key performance indicators is achieved through training.

# Training Load Analysis
Training Load is assessed through volume, power and heartrate analysis.

## Individual Activity Analysis
Analysis of every activity is performed to derive in depth insights about the rider's training. \
*HR/PWR drift*

# ML Workout Prediction For Race Preparation
Based on user input, optimal workout recommendations are generated with Machine Learning to prepare races and target specific energy systems and physiological adaptations.

## ML Personalized Workouts Based On Rider Type
Workout recommendation are generated with Machine Learning based on the rider type assessment. \
*Say the rider is classified as a rouleur, recommendations will focus on improving rider qualities or weaknesses.*

## ML Personalized Workouts Based On Race Objectives
Workout recommendations are generated with Machine Learning based on race characteristics, profiles, durations, importance, etc. \
*Say the rider has a 200km race, recommendations will perhaps focus on improving the rider's endurance and aerobic capacity while adding workouts to improve his explosiveness at the end of a long race.*

