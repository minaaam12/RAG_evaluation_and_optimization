# Evaluation and Optimization of a Retrieval-Augmented Generation System on a Subset of Wikipedia Texts

This repository contains the code for the implementation and evaluation of a Retrieval-Augmented Generation (RAG) system built on a board game-themed subset of Wikipedia articles.

## Project Structure

* `data_md/` - Folder containing the source Wikipedia documents in Markdown format.
* `results/` - Folder containing the experimental outputs and evaluation metrics.
* `gold_ds_final.csv` - The manually refined "ground truth" test dataset.
* `pipeline.ipynb` - Jupyter Notebook containing the RAG pipeline code and evaluation workflow.
* `requirements.txt` - File containing all the Python dependencies required to run the project.

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
`pip install -r requirements.txt`

## Usage

1. Create a `.env` file in the root directory of the project and add your OpenAI API key:
`OPENAI_API_KEY=your_api_key_here`
2. Open and run `pipeline.ipynb` via Jupyter Notebook or VS Code to execute the RAG pipeline and view the evaluation workflows. 

> **Note:** The pipeline is set up to use `gpt-4o-mini` as a default model inside RAG chain, but you can easily switch to `gpt-4o` by following the comments inside the notebook.
