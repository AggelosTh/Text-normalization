# Textual Data Normalization for Composition Writers

This project implements a solution for normalizing textual data, specifically focusing on composition writers' information in the music industry. The task is to handle raw and potentially redundant or missing data, propose a solution for normalizing it, and ensure that the solution is generalizable to unseen data.

## Problem Statement

In the music industry, textual data about composition writers often contains redundant information. This project aims to design and implement normalization techniques that:

- Identify and handle redundant or incomplete data
- Normalize textual information without losing valuable content

## Technologies Used

- Python 3.x
- Ollama API
- Llama3.1 model

## Project Overview

The dataset contains raw data about composition writers, as well as a normalized version of this data for comparison. The goal is to design a solution that can efficiently normalize the given raw data and handle redundancy.

The solution is built using the Llama3.1 model through the Ollama API, which is utilized to analyze and process the textual data.

## Features

- **Data Exploration:** Explore the dataset and find patterns and keywords that need to be removed.
- **Text Normalization:** Applies normalization techniques to standardize the data without losing important information.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AggelosTh/Text-normalization.git
    ```

2. Install and activate the conda environment:
    ```bash
    conda env create -f environment.yml
    conda activate text_normalization
    ```

3. Install the Ollama client:
   ```bash
   pip install ollama
   ```
       
4. Ensure you have access to the Ollama API and Llama3.1 model by following the API setup instructions [here](https://ollama.com).

5. Pull the Llama3.1 language model:
    ```bash
    ollama pull llama3.1
    ```
6. Move the csv files to the repo folder

## Dataset

The dataset consists of two parts:
- **Raw Data:** A collection of composition writers' information with potential redundancy or missing fields.
- **Normalized Data:** The expected output after applying normalization techniques.


## Run experiments:
- To reproduce the implementation, simply execute the code blocks as described in the notebook.
