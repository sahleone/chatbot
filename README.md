# Personalized Real Estate Agent

The Personalized Real Estate Agent is a project aimed at creating personalized real estate listings for each buyer, making the property search process more engaging and tailored to individual preferences.

## Overview

The project involves several components:

1. **Creating Real Estate Listings**: Generating real estate listings based on a template and various contextual factors such as price, bedrooms, bathrooms, house size, and neighborhood description.

2. **Creating Images**: Generating images corresponding to the real estate listings using a generative model (in this case, DALL-E).

3. **Creating Vector Store**: Storing vector representations of the real estate listings and their descriptions and images in a database for efficient retrieval and similarity search.

4. **Collecting User Preferences**: Gathering user preferences through a series of questions to personalize the recommendations.

5. **Chatbot**: Implementing a chatbot that interacts with users to understand their preferences and recommend suitable real estate listings based on the collected information.

6. **Image Search**: Implementing an image search functionality to retrieve real estate listings based on visual queries.

## Usage

### Dependencies

Ensure you have the following dependencies installed:

- Python 3.x
- Required Python packages (install via pip):
  - `dotenv`
  - `chromadb`
  - `langchain`
  - `openai`
  - `transformers`
  - `requests`
  - `PIL`
  - `matplotlib`


### Setup

1. Clone the repository to your local machine.
2. Set up a virtual environment (optional but recommended):

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required Python dependencies using `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables by creating a `.env` file and adding your OpenAI API key.

### Running the Code

1. Run the code provided in the Jupyter Notebook or Python script.
2. Follow the prompts and input necessary information when prompted.
3. Interact with the chatbot to receive personalized real estate recommendations based on your preferences.
4. Use the image search functionality to retrieve real estate listings based on visual queries.

### File Structure

- `README.md`: Overview, setup instructions, and usage guidelines.
- `personalized_real_estate_agent.ipynb` (or `.py`): Main code file containing the implementation.
- `listings.txt`: Text file containing generated real estate listings.
- `images/`: Directory containing generated images corresponding to real estate listings.
- `db/`: Directory containing database files for storing vector representations and metadata.

## Notes

- This project utilizes various AI models and APIs for natural language processing, image generation, and similarity search. Ensure proper authentication and access to these services.
- Modify the code as needed to fit specific use cases or environments.
- Refer to the official documentation of the libraries and APIs used for detailed information on usage and customization.

