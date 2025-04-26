# smallagents

Tool calling using Hugging Face smallagents.

## Overview

This repository provides examples of using the Hugging Face `small_agents` framework to create simple tool-using agents.  
The agents can call external tools and perform tasks based on instructions, using lightweight and efficient models.

## Contents

- `code_agents.ipynb` — A Jupyter Notebook demonstrating how to build and run small agents.
- `helper.py` — Helper functions for managing tools and agents.
- `requirements.txt` — List of Python dependencies required to run the code.


## Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/bhushan1729/smallagents.git
cd smallagents
pip install -r requirements.txt
```

## Usage

### Running the Notebook

Run the notebook to see examples:

```bash
jupyter notebook code_agents.ipynb
```

Install dependencies using:

```bash
pip install -r requirements.txt

```

## Notes
helper.py and requirements.txt are taken from the course on Deeplearning.ai for a small agent library on Hugging Face. Code in code_agents.ipynb contains same examples from the link below with some extra examples.
Link for the video: https://learn.deeplearning.ai/courses/building-code-agents-with-hugging-face-smolagents/lesson/tv10w/introduction-to-code-agents

This project is experimental.

It is recommended that API tokens and secret keys be handled securely using environment variables or a .env file.
