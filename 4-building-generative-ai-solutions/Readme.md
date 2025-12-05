# Personalized Real Estate Agent - Udacity Project 

Project Introduction:
Imagine you're a talented developer at "Future Homes Realty", a forward-thinking real estate company. In an industry where personalization is key to customer satisfaction, your company wants to revolutionize how clients interact with real estate listings. The goal is to create a personalized experience for each buyer, making the property search process more engaging and tailored to individual preferences.

## Core Components of "HomeMatch"

### Understanding Buyer Preferences

- Buyers will input their requirements and preferences, such as location, property type, budget, amenities, and lifestyle choices.
- The application uses LLMs to interpret these inputs in natural language, understanding nuanced requests beyond basic filters.

### Integrating with a Vector Database

- Connect "HomeMatch" with a vector database, where all available property listings are stored.
- Utilize vector embeddings to match properties with buyer preferences, focusing on aspects like neighborhood vibes, architectural styles, and proximity to specific amenities.

### Personalized Listing Description Generation

- For each matched listing, use an LLM to rewrite the description in a way that highlights aspects most relevant to the buyer’s preferences.
- Ensure personalization emphasizes characteristics appealing to the buyer without altering factual information about the property.

### Listing Presentation

- Output the personalized listing(s) as a text description of the listing.

## How to execute

1 - Install the requirements

```bash
pip install -r requirements.txt
```

2 - Run the [notebook](./HomeMatch.ipynb) file.

**Important**: You need to use your own OpenAI key in the cell to run the notebook.

```python
# Environment variables
OPENAI_API_KEY = 'YOUR API KEY'
```