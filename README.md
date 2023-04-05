# Article Analysis with GPT-3.5-turbo

This Python script allows you to interact with a GPT-3.5-turbo model by OpenAI to analyze and summarize articles from URLs. You can ask questions about the article, and the model will answer based on the content. The script uses the `newspaper3k` library to extract the article content and the OpenAI API to communicate with the GPT-3.5-turbo model.

## Features

- Extracts article content from a given URL
- Splits the article into smaller parts if needed
- Summarizes the article upon request
- Allows the user to ask questions about the article
- Interacts with the GPT-3.5-turbo model via the OpenAI API

## Installation

1. Clone the repository:


# Article Analysis with GPT-3.5-turbo

This Python script allows you to interact with a GPT-3.5-turbo model by OpenAI to analyze and summarize articles from URLs. You can ask questions about the article, and the model will answer based on the content. The script uses the `newspaper3k` library to extract the article content and the OpenAI API to communicate with the GPT-3.5-turbo model.

## Features

- Extracts article content from a given URL
- Splits the article into smaller parts if needed
- Summarizes the article upon request
- Allows the user to ask questions about the article
- Interacts with the GPT-3.5-turbo model via the OpenAI API

## Installation

1. Clone the repository:

git clone https://github.com/maximedotair/article_analysis_gpt.git

2. Change to the project directory:

cd article-analysis-gpt

3. Create a virtual environment and activate it:

python3 -m venv myenv
source myenv/bin/activate

4. Install the required packages:

`    $ pip install -r requirements.txt`

5. Add your OpenAI API key to the script:

Replace `your_api_key_here` with your actual API key in the line:

```python
api_key = "your_api_key_here"
```

# Usage
Run the script:

`    $ python article_analysis.py`

Enter the URL of the article to summarize: https://example.com/article-url

Choose to summarize the article or ask your own question:

Do you want to summarize the article? (yes/no): yes

Ask questions about the article:

Ask a question (previous questions and answers are not saved) or type 'exit' to quit: What is the main point of the article?

Type 'exit' to quit the script:

Ask a question (previous questions and answers are not saved) or type 'exit' to quit: exit

# Dependencies
 OpenAI - Python library for the OpenAI API
 newspaper3k - Python library for extracting and parsing newspaper articles

# License
    This project is licensed under the MIT License.
