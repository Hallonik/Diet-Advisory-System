# Customized Diet Recommendation System

Welcome to the **Customized Diet Recommendation System**, a web application designed to provide personalized food recommendations based on user-defined nutritional preferences and dietary restrictions. This project leverages a content-based recommendation approach using **Scikit-Learn**, **FastAPI**, and **Streamlit**.

## Features

- **Custom Nutritional Inputs**: Users can specify their desired nutritional values (e.g., calories, fat, protein, etc.) using interactive sliders.
- **Ingredient Inclusion/Exclusion**: Users can include or exclude specific ingredients in the recommendations.
- **Allergy Management**: Recipes containing specified allergens are automatically excluded.
- **Dynamic Recommendations**: Generate a list of recipes tailored to user preferences.
- **Recipe Overview**: View detailed nutritional values, ingredients, and preparation instructions for each recipe.
- **Interactive Visualizations**: Pie charts and other visualizations for recipe nutritional breakdowns.

## Technologies Used

- **Streamlit**: For building the frontend interface.
- **Scikit-Learn**: For implementing the recommendation engine.
- **FastAPI**: For backend API services.
- **Pandas**: For data manipulation and analysis.
- **ECharts**: For interactive data visualizations.

## Project Structure
New_Customized_Diet_Recommendation/ │ ├── Streamlit_Frontend/ │ ├── pages/ │ │ ├── Custom_Food_Recommendation.py # Main Streamlit app for custom recommendations │ │ └── Hello.py # Welcome page for the app │ └── ... ├── food-recommendation-system.ipynb # Jupyter Notebook for recommendation system development └── ...


### Key Files

- **`Streamlit_Frontend/pages/Custom_Food_Recommendation.py`**: Contains the main logic for the Streamlit app, including user input forms, recommendation generation, and result display.
- **`food-recommendation-system.ipynb`**: Notebook for developing and testing the recommendation engine.

## How to Run

### Prerequisites

- Python 3.9 or higher
- Required Python libraries (install via `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/zakaria-narjis/Diet-Recommendation-System.git
   cd Diet-Recommendation-System

2. Install dependencies
   pip install -r requirements.txt

Running the Application

1.Navigate to the Streamlit_Frontend directory:
cd Streamlit_Frontend

2.Run the Streamlit app:
streamlit run pages/Custom_Food_Recommendation.py

3.Open the app in your browser at http://localhost:8501

Usage

Welcome Page: Start by navigating to the welcome page (Hello.py) for an introduction to the app.

Custom Recommendations:
Adjust nutritional values using sliders.
Specify ingredients to include or exclude.
Set the number of recommendations to generate.

View Results:
Explore recommended recipes with detailed nutritional breakdowns.
View preparation instructions and cooking times.

Example
Input
Calories: 500
Protein: 20g
Exclude Ingredients: Peanuts, Shrimp
Output
A list of recipes matching the criteria, with detailed nutritional values and preparation instructions.

Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.