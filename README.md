# travel_recommendation_engine
An intelligent recommendation engine that helps travelers discover attractions, restaurants, and destinations tailored to their preferences.
# Travel Attraction Recommendation System

A machine learning-based travel recommendation system that suggests tourist attractions according to user preferences such as continent, attraction type, and cuisine. The project uses **Content-Based Filtering**, **Cosine Similarity**, and **Fuzzy String Matching** to generate personalized travel recommendations.

---

## Features

* Personalized attraction recommendations
* Content-based filtering approach
* Cosine similarity recommendation engine
* Fuzzy matching for spelling correction
* Attraction details with ratings and location
* Nearby restaurant recommendations
* Attraction image support
* Easy-to-use command-line interface

---

## Technologies Used

* Python
* Pandas
* Scikit-Learn
* FuzzyWuzzy
* Python-Levenshtein
* NumPy

---

## Project Structure

```text
Travel-Recommendation-System/
│
├── dataset_csv_file.csv
├── recommendation_system.py
├── README.md
├── requirements.txt
├── screenshots/
│   ├── output1.png
│   └── output2.png
└── report/
    └── Project_Report.pdf
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/travel-attraction-recommendation-system.git

cd travel-attraction-recommendation-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Requirements

```bash
pandas
numpy
scikit-learn
fuzzywuzzy
python-Levenshtein
```

---

## Running the Project

```bash
python recommendation_system.py
```

The system will ask for:

1. Preferred Continent
2. Attraction Type
3. Preferred Cuisine

Example:

```text
Asia, Historical Site, Pakistani
```

---

## Methodology

### Data Preprocessing

* Handle missing values
* Convert numerical features
* Label Encoding for categorical features

### Recommendation Engine

Features used:

* Continent
* Attraction Type
* Popularity Ratings
* Best Time to Visit
* Preferred Cuisine

Cosine Similarity is applied to generate recommendations based on attraction similarity.

### User Input Handling

FuzzyWuzzy is used to:

* Correct spelling mistakes
* Match approximate user inputs
* Improve recommendation accuracy

---

## Sample Output

```text
Attraction Based on Your Preferences

Badshahi Mosque (Lahore, Pakistan)

Rating: 4.8
Best Time to Visit: Winter

Nearby Restaurant: Haveli Restaurant

Top Recommendations:
1. Faisal Mosque
2. Lahore Fort
3. Shalimar Gardens
```

---

## Future Improvements

* Web Application Deployment
* Streamlit Interface
* Deep Learning Recommender
* Hybrid Recommendation System
* Location-Based Recommendations
* Integration with Google Maps API

---

## Author

Kashaf Noureen                   
Email: noureenkashaf@gmail.com                                                               
