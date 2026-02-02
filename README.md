Movie Recommendation System

(Collaborative Filtering Based)
Overview

The Movie Recommendation System is a machine learning–based application that provides personalized movie recommendations to users based on their past viewing behavior.
The system uses collaborative filtering to identify users with similar preferences and recommends movies that similar users have liked but the target user has not yet watched.

Problem Statement

With the growing number of movies available across platforms, users often struggle to discover content that matches their taste.
This project aims to:
personalize movie suggestions
reduce content overload
demonstrate how real-world recommendation engines work

Solution Approach

The system is built using user-based collaborative filtering:
Construct a user–item interaction matrix from ratings data
Compute user similarity using cosine similarity
Identify users with similar taste
Recommend movies highly rated by similar users
Return recommendations via a REST API
