# Evaluating GPT-3.5-Turbo’s Accuracy in Summarizing News Articles
## Overview
This repository contains the code from my project within the [Inspirit 1:1 AI Research Program](https://www.inspiritai.com/ai-research-program). I sincerely thank my mentors, the administrative team behind the program, and my parents for providing me with the resources to complete this project.

## Abstract 
Thousands of news articles are published every day, yet many people are still unable to stay up to date with world events due to a lack of time. An accurate and precise method of summarization would help condense the vast amount of information into more bite-sized chunks, lowering barriers between individuals and a knowledge of current events.

Making good decisions in an ever changing world requires an understanding of current events. Lowering the barriers that exist between individuals and an understanding of the current global landscape would help them make better choices and be better citizens of the world.

The research detailed in this paper aims to analyze the ability of gpt-3.5-turbo to summarize news articles by comparing generated articles to human-written summaries via the ROUGE metric. Three different summary pipelines were used and evaluated for accuracy to the original article: one zero-shot pipeline, and two few-shot pipelines. On average, all three pipelines wrote poor summaries when evaluated using the ROUGE-1 and ROUGE-2 metrics. This could be for many reasons, including limitations of gpt-3.5-turbo’s ability to summarize, limitations of the specific prompts in this report, and limitations of the ROUGE metric in its ability to analyze summary accuracy.
