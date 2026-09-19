# AI Recommendation System

## DecodeLabs Artificial Intelligence Training – Project 3

### Project Overview

This project implements a simple AI Recommendation System based on user preferences and similarity matching.

The system takes user interests as input, compares them with the attributes of available items, calculates similarity scores, ranks the items, and displays the most relevant recommendations.

## Objective

The main objectives of this project are:

* Take user preferences as input
* Match user preferences with item attributes
* Calculate a similarity score
* Rank items based on similarity
* Display personalized recommendations

## How It Works

The recommendation system follows this process:

User Preferences
↓
Preference Matching
↓
Similarity Score Calculation
↓
Ranking
↓
Top Recommendations

## Recommendation Logic

The system compares the user's selected preferences with the genres/attributes of each available item.

The similarity score is calculated based on the number of matching preferences.

Items with higher similarity scores are ranked higher and presented as recommendations.

## Technologies Used

* Python
* Google Colab
* Jupyter Notebook
* Basic similarity matching
* Set intersection
* Sorting and ranking

## Example

### User Input

```text
Sci-Fi, Adventure
```

### Example Output

```text
Top Recommended Movies:

1. Interstellar - Match Score: 100%
2. Avengers - Match Score: 100%
3. Inception - Match Score: 50%
```

## Project Files

```text
AI-Recommendation-System/
│
├── AI_Recommendation_System_Project_3.ipynb
├── README.md
└── screenshots/
```

## How to Run

1. Open the `.ipynb` notebook.
2. Open it in Google Colab.
3. Run the cells from top to bottom.
4. Enter your preferred genres when requested.
5. View the recommended items and similarity scores.

## Project

**Program:** Artificial Intelligence Training
**Organization:** DecodeLabs
**Project:** Project 3 – AI Recommendation Logic
**Batch:** 2026

