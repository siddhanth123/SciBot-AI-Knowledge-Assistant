# SciBot: AI Knowledge Assistant

SciBot is an advanced AI-driven research companion designed to assist users with English language queries, specifically focused on scientific studies such as those associated with the Llama-2 project. Powered by cutting-edge technologies like GPT-3.5 and OpenAI Embeddings, SciBot delivers insightful responses drawn from an extensive collection of scientific literature sourced from Arxiv. Elevate your research endeavors with SciBot today!

## Features

- **Advanced AI Integration**: Seamlessly integrates with GPT-3.5 to provide accurate and informative responses to user queries.
  
- **Contextual Understanding**: Utilizes OpenAI Embeddings to comprehend and analyze input queries, ensuring contextually relevant responses.

- **Arxiv Database**: Accesses a comprehensive database of scientific studies related to the Llama-2 project sourced from Arxiv, enabling well-informed answers to a wide range of questions.

## Usage

1. **Environment Setup**: Create a conda environment using the provided `requirements.txt` file to install all dependencies.
   
   `conda create -n scibot-env python=3.9`

   `conda activate scibot-env`

   Install dependencies:

   `pip install -r requirements.txt`
   

3. **Customize Queries**: Open the `app.py` script and customize the `Question` variable to specify the query you want SciBot to answer.

   `Question = "Give the summary of a specific paper"`

3. **Running the Script**: Execute the `app.py` script using Python to launch the SciBot application.

   `python app.py`

4. **Handling Multiple Papers**: Utilize the `paper.py` script to manage multiple papers stored in files. The `paper.txt` file contains summaries of all the papers.

## Requirements

- Python 3.9 or above
- MiniConda
- GPT-3.5 API Key (if applicable)

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

The development of SciBot is inspired by advancements in AI and natural language processing, particularly the capabilities of GPT-3.5 and OpenAI Embeddings.
   
