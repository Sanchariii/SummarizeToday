# SummarizeToday: A Summarised News Portal

**SummarizeToday** is a Python script and Streamlit web application that allows users to fetch and display news articles from Google News. The script utilizes web scraping techniques to collect news articles, while the web application provides an interactive and user-friendly interface to access and summarize news content.

## Demo
* The UI :
<img width="960" alt="image" src="https://github.com/Sanchariii/SummarizeToday/assets/88083502/fb48b4af-b40a-4884-9cb0-1a27b661ddbf">

* The Summarized News :
  <img width="960" alt="image" src="https://github.com/Sanchariii/SummarizeToday/assets/88083502/876544f6-c668-4466-bc4d-1a3c6dfb684d">



## Features

- Choose from a variety of news categories.

- Explore the latest top news articles.

- Search for specific topics of interest.

- View summarized news articles.

- Get a glimpse of the news poster image.

## Prerequisites

Before running the application, ensure you have the following requirements installed:
- Python 3.x
- Python libraries: BeautifulSoup, Newspaper, NLTK, Streamlit
- Pillow (PIL) for image handling

You can install the necessary libraries using pip:

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Sanchariii/SummarizeToday.git
    ```

2. Install Python packages
    ```sh
    pip install -r requirements.txt
    ```

3. Deploy the Streamlit web application
    ```sh
    streamlit run App.py
    ```

## Structure

This repository contains the following files:

- <b>scrape_news.py</b>: Contains the Python script for web scraping and news retrieval.

- <b>App.py</b>: Includes the Streamlit web application logic for user interaction and news display.

- <b>requirements.txt</b>: Lists the Python libraries required to run the application.

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request.

## License
This project is licensed under the [Don't Be a Jerk License](./LICENSE.md) - see the LICENSE file for details.




