# Movie Recommendation System

## Overview

This repository contains a Movie Recommendation System that suggests movies based on content similarity or collaborative filtering, utilizing publicly available datasets.

## Features

- **Content-Based Recommendations**: Utilizes metadata like genre, cast, and keywords to recommend movies.
- **Efficient Data Processing**: Employs pandas and NumPy for handling large datasets.

## Dataset

- **Movies Dataset**: Contains metadata about movies (e.g., title, genres, overview).
- **Credits Dataset**: Includes information about the cast and crew.

### Data Preprocessing

- Merged datasets on the `title` column.
- Parsed and transformed key fields for similarity calculations.

## Tools and Libraries

- **Python**: pandas, NumPy, scikit-learn, ast.

## Methodology

1. **Data Preprocessing**: Cleaning, parsing, and feature engineering.
2. **Content-Based Filtering**:
   - Vectorization with `CountVectorizer`.
   - Cosine similarity for generating recommendations.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-recommendation-system
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Place the datasets (`tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`) in the project directory.
5. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Movie Recommendation System.ipynb"
   ```

## Example Usage

Input a movie title (e.g., "The Dark Knight") to get recommendations:

```
Recommended Movies:
1. The Dark Knight Rises
2. Inception
...
```

### Screenshot of Working Output

Below is a screenshot of the recommendation system in action:

![Working Output](output.png)

## Future Enhancements

- Implement collaborative filtering.
- Integrate with a web framework (e.g., Flask or Django).
- Utilize deep learning models for improved recommendations.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

