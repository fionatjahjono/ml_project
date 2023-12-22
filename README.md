# ml_project

# Event Matchmaker Project

## Overview

This project addresses the challenge of enhancing event discovery and user interaction through efficient matchmaking and personalized recommendations. Key focus areas include discovering events with specific themes, pre-event matchmaking, and facilitating effective communication and group formation.

## Algorithms Developed

### Sentiment Analysis

Utilizing a multi-faceted data approach, the Sentiment Analysis algorithm considers user ratings (ranging from 1-5) and text review sentiments (neutral, positive, negative). By maximizing the Net Promotor Score (NPS) and cumulative sentiment assessment, this algorithm ensures highly accurate and personalized event recommendations.

### K-means Clustering

This clustering algorithm filters and prioritizes events based on their proximity in terms of dates. Users receive recommendations for events closely aligned with their preferred timing, enhancing the relevance of suggestions.

### Content-Based Filtering

Recommendations in this algorithm are based on users' past events and category interests. By identifying similarities with previously liked items, the system delivers personalized recommendations aligned with users' preferences.

### Collaborative-Based Filtering

This algorithm generates recommendations solely based on how other users have rated items. The memory-based approach calculates similarity scores between items or users, enabling personalized suggestions.

## Data Source

The project utilizes the 'dataset' folder, consisting of three tables:

- 'User_id': 200 records
- 'Sentiment_analysis': 3,245 records
- 'Event_table': 148 records
- 'Category_table': 6 records

## Usage

To leverage the full potential of the Event Matchmaker project, explore the documentation and utilize the provided dataset in the 'dataset' folder.

Feel free to contribute, report issues, or provide feedback to enhance the project's effectiveness and user experience.
