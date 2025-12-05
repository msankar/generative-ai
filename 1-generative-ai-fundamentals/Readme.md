# Custom Chatbot Project

## Overview
This project involves building a custom chatbot using OpenAI's language model and a dataset of your choice. The goal is to understand how chatbots work by manually coding the chatbot without using frameworks like LangChain.

## What Will You Build?
Upon completion, you will have a custom OpenAI chatbot that utilizes a dataset to provide relevant responses based on user queries.

## Data Sources
You can use the following data sources for this project:
- **Wikipedia API**: Use any article except for the specified ones.
- **CSV Data**: You can use the provided CSV files or source your own data. The dataset must have at least 20 rows of text data.

### Provided CSV Files:
- `2023_fashion_trends.csv`: Reports and quotes about fashion trends for 2023.
- `character_descriptions.csv`: Character descriptions from theater, television, and film.
- `nyc_food_scrap_drop_off_sites.csv`: Information about food scrap drop-off sites in New York City.

## Custom Scenario
You will explain why the chosen dataset is appropriate for the task and demonstrate the chatbot's performance before and after customization.

## Requirements
- Python
- Pandas
- OpenAI API

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   pip install pandas openai

## Usage
Load your dataset into a pandas dataframe.
Implement the logic to send queries to the OpenAI model.
Test the chatbot with various questions to see how it performs with the custom dataset.
License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
OpenAI for providing the language model.
Udacity for the course and resources.