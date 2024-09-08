# Coupon Recommendation System

This project is aimed at building a **Coupon Recommendation System** that predicts whether a user will accept a coupon based on various features like user demographics, preferences, and past behavior. The dataset used is enriched with information about user activity and context.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
In the world of digital marketing, personalized coupon recommendations are critical to increase user engagement and sales. This system predicts whether users will accept a coupon based on factors such as:
- User information (age, gender, etc.)
- Context (time of day, weather, etc.)
- Preferences (frequency of visiting coffee houses, restaurants, etc.)

The system is built to handle user data efficiently and can help businesses increase their coupon conversion rates.

## Technologies Used
The following libraries and technologies are used in this project:
- **Python 3.12.1**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Scikit-learn** for model building and evaluation
- **Matplotlib** and **Seaborn** for data visualization
- **Jupyter Notebook** for interactive development
- **Git** for version control

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/paulasanjuan/Coupon-Recommendation-System.git
cd Coupon-Recommendation-System
```

### 2. Create and activate a virtual environment:

```
# Create virtual environment
python -m venv venv

# Activate the virtual environment (Windows)
venv\Scripts\activate

# Activate the virtual environment (macOS/Linux)
source venv/bin/activate
```

### 3. Install the required dependencies

```
pip install -r requirements.txt
```

## Dataset

The dataset used in this project contains various features related to user demographics, behavior, and contextual data that help in predicting whether a user will accept a coupon.

*Main features include:*
- destination: The destination the user was going to.
- passanger: Number of passengers.
- time: Time of day.
- coupon: The type of coupon.
- gender, age, maritalStatus, education, occupation: User demographic details.
- Bar, CoffeeHouse, CarryAway, RestaurantLessThan20, Restaurant20To50: Frequency of visiting these places.
- Y: Target variable (whether the coupon was accepted).

## Usage

1. After installing the necessary dependencies, open the Jupyter notebook.

2. Load the dataset and execute the cells in the notebook to preprocess the data, train the model, and evaluate the results.

## Modeling and Evaluation

The notebook includes:

- Data Preprocessing: Handling missing values, encoding categorical features, and scaling.
- Exploratory Data Analysis (EDA): Visualizations to understand the relationship between features and the target variable.
- Modeling: Machine learning models like Logistic Regression, Decision Trees, and Random Forest.
- Evaluation: Performance metrics such as accuracy, precision, recall, and F1-score to evaluate the models.