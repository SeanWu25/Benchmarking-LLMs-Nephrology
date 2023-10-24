# Benchmarking-LLMs-NEJM-AI
ArXiv paper: [Read the pre-print here](https://arxiv.org/pdf/2308.04709.pdf)

This repository contains the code for benchmarking Large Language Models (LLMs) in our paper titled "A Comparative Study of Open-Source Large Language Models, GPT-4, and Claude 2: Multiple-Choice Test Taking in Nephrology." Here, you will find instructions for running inference on open-sourced LLMs, including Falcon, Orca-Mini, Vicuna, Llama-70b, and Koala, using the Nephrology dataset.
## Instructions to Access Data:
We provide our data request at this link:  [Access the data here](https://drive.google.com/drive/folders/1q06Wjkl0ItUS7RYXmwtkIq-9WEH_RbQz?usp=drive_link)

Please request access and leave a message for the reason requesting the dataset. 

## Instructions to Run Open-Sourced Models:
1. Open the Jupyter notebook of the corresponding open-sourced model.
2. Replace the JSON path with the one downloaded from the requested link. 
3. Run the code to perform inference with the LLM.

## Model Benchmarking:
The code in this repository allows you to benchmark the outputs of the models based on several metrics:

- Accuracy
- BLEU (Bilingual Evaluation Understudy)
- WER (Word Error Rate)
- Cosine Similarity

You can use regular expressions to analyze and compare the performance of the LLMs with these metrics. The "data" folder also includes ground truth labels for the cases, enabling you to compare model outputs with actual results.

## Error Margins and Confidence Intervals:
You can also calculate error margins by employing a 95% confidence interval. This statistical analysis will provide insights into the reliability of the results obtained from the LLMs. Check the "confidence interval folder" for detailed instructions on how to perform this analysis.

Feel free to explore the code and datasets within this repository to replicate and expand upon our research findings in the field of Nephrology using open-source Large Language Models. You can introduce your own models and fine-tuning strategies, and compare their performance to our baseline results using the provided Nephrology dataset and metrics.
