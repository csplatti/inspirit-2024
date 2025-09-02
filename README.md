# Evaluating GPT-3.5-Turbo’s Accuracy in Summarizing News Articles
## Overview
This repository contains the code from my research project within the [Inspirit 1:1 AI Research Program](https://www.inspiritai.com/ai-research-program). The paper is publically available on google drive at [this link](https://drive.google.com/file/d/1g5ychChpxJWunNnEtU-h19GULagP3vzj/view?usp=sharing). 

I sincerely thank my mentors, the administrative team behind the program, and my parents for providing me with the resources to complete this project.

## Abstract 
Thousands of news articles are published every day, yet many people are still unable to stay up to date with world events due to a lack of time. An accurate and precise method of summarization would help condense the vast amount of information into more bite-sized chunks, lowering barriers between individuals and a knowledge of current events.

Making good decisions in an ever changing world requires an understanding of current events. Lowering the barriers that exist between individuals and an understanding of the current global landscape would help them make better choices and be better citizens of the world.

The research detailed in this paper aims to analyze the ability of gpt-3.5-turbo to summarize news articles by comparing generated articles to human-written summaries via the ROUGE metric. Three different summary pipelines were used and evaluated for accuracy to the original article: one zero-shot pipeline, and two few-shot pipelines. On average, all three pipelines wrote poor summaries when evaluated using the ROUGE-1 and ROUGE-2 metrics. This could be for many reasons, including limitations of gpt-3.5-turbo’s ability to summarize, limitations of the specific prompts in this report, and limitations of the ROUGE metric in its ability to analyze summary accuracy.

## Notebook Installation
1. Fork this repository
2. Clone this repository
```bash
git clone https://github.com/{your-gh-username}}/inspirit-2024.git
```
3. Navigate to the local repository
```bash
    cd ./inspirit-2024
```

## Notebook Usage (VSCode)
1. Navigate to the repository on your local machine
2. Create a python virtual environment via ```python3 -m venv {your_env_name}```
3. Activate the environment via ```source ./{your_env_name}/bin/activate```
4. Install the required dependencies via ```pip install -r requirements.txt```
5. Open ```./.env copy``` and replace ```{your_openai_api_key_here}``` with an openai api key of your own
6. Rename ```./.env copy``` to ```./.env``` (i.e. run ```mv ".env copy" ".env"```)
7. Open ```./project_notebook.ipynb```
8. Click "Select Kernel" in the top right corner and select ```Python Environments -> env (Python 3.11.0)```
5. Run and use the cells in the notebook as you wish
6. When you are finished, deactivate the environment via the ```deactivate``` command
