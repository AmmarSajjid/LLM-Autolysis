# LLM-Powered Story Visualizer

## Overview

This project is a Python-based tool that leverages a Large Language Model (LLM) to analyze, visualize, and narrate stories from datasets. By integrating the capabilities of LLMs, data analysis, and visualization libraries, this tool transforms raw data into insightful narratives and compelling visualizations.

## Features

* Automated Data Analysis: Extracts key insights and patterns from structured datasets.

* Story Visualization: Generates intuitive visualizations (e.g., charts, graphs) to complement the story.

* Narrative Generation: Produces coherent and human-readable narratives to explain data trends and findings.

## Installation

### Clone the Repository
```bash
git clone https://github.com/AmmarSajjid/LLM-Autolysis.git
```

### Set Up the Environment

#### Install the required Python environment and configure the OpenAI API key.

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

```bash
pip install uvicorn
```
#### Set Up OpenAI API Key
```bash
export AI_TOKEN='your_openai_api_key_here'
```
## Usage

Prepare Your Dataset: Ensure the dataset is in a supported format (.csv).

### Run the Script:
```bash
python autolysis.py your_dataset.csv
```
## View the Output: 
The tool generates visualizations and a narrative summary, which are saved in the root directory.

## License

This project is licensed under the MIT License. See the LICENSE file for details.





