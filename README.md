# LLM-Conversational-Acuity

## Dataset
```PromptDataset.csv``` is the dataset we will be using for fine-tuning the LLM. Download the CSV and save it to the main Google Drive.
```PromptDataset_yourgpt.jsonl``` is the JSONl file version of PromptDataset.csv
```csvjson.json``` is the JSON file version of PromptDataset.csv

## GPT-3.5 Turbo Files
```GPT3_5FineTuned_with_parameters.ipynb``` contains all the fine-tuning with adjusted parameters.

## GPT-4o mini Files

## GPT-4o Files

## Model Comparison
```Text_Comparison.ipynb``` contains the quantitative metrics (cosine similarity, Jaccard similarity, Levenshtein distance) for determining text similarity.


## Gemini model -- We will not be using these files for our experiment
```Gemini.ipynb``` is the Gemini API key applied to a Colab notebook.
```Gemini_w_RL_and_FT (1).ipynb``` is the edited notebook with implementations for RLHF and fine-tuning. We will have to adjust to keep up with our dataset.
```Gemini_w_RL_and_FT (2).ipynb``` is the mopst recent. It contains dataset implementation, as long as the PromptDataset.csv is saved in the main Google Drive. Otherwise, path information will need to be adjusted accordingly.
