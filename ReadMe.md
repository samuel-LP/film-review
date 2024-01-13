# Film Review Application 🎬

## Introduction


Welcome to Film Review, your personal movie rating application! This Streamlit-based web app provides key information for each film, including:

- **IMDB-based Rating**: An overall rating calculated using a sentiment analysis model based on IMDB reviews.
- **Percentage of Positive Reviews**: The percentage of positive reviews.
- **Trailer Link**: A link to the movie trailer.

Furthermore, you can explore the best and worst user comments based on the sentiment analysis model used in the application.

## How to run

1. "Make sure you have the required libraries installed. You can install them by running:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the application:

    ```bash
    streamlit run ./scripts/app.py  
    ```

3. Access the application in your web browser using the provided URL

## Usage
- Upon launching the application, you will see a grid of movie poster images.
- Click on "More Information" to view additional details about a specific film.
- Explore the overall movie rating, the percentage of positive reviews, and the trailer link.
- Read the best and worst user comments based on sentiment analysis.


## Remarks
- The application uses web scraping to gather information about movies from IMDB and may be subject to changes in the website structure.
- Ensure you have a stable internet connection for accurate data retrieval.

Enjoy exploring and discovering movies with Film Review! 🎬🍿
