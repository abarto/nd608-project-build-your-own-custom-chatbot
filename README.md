## nd608 - Project: Build Your Own Custom Chatbot

### Introduction

This is repo contains my implementation for Udacity's Generative AI Nanodregree "Project: Build Your Own Custom Chatbot" project. For this project I've chosen [Return to Monkey Island's Wikipedia page](https://en.wikipedia.org/wiki/Return_to_Monkey_Island). I've used the `gpt-3.5-turbo-instruct` OpenAI model, as shown during the lessons.

The code deviates slightly from the lessons examples, as those were written with a Python OpenAI API version prior to v1. I had to adapt the code the newest available version as of this writing (1.14.3).

The code uses [`python-dotenv`](https://pypi.org/project/python-dotenv/) to load an `.env` file (not provided) from the same directory to set the `OPENAI_API_KEY` value environment variable. If this library is not available within Udacity's workspace, the client's `api_key` parameter will have to be set manually.

### Contents

| File/Folder | Description |
|-------------|-------------|
| [`project-template.ipynb`](projecttemplate.ipynb) | Jupyter Notebook template, provided by Udacity. |
| [`project.ipynb`](project.ipynb) | Jupyter Notebook with the project submission. |
| [`project.html`](project.html) | HTML export of the Jupyter Notebook with the project submission. |
| [`data_df.pickle`](data_df.pickle) | `pickle` dump of a `DataFrame` containing the project's context source. |