# KenSho
*LLM based dream interpretation for better diagnosis of patients with psychological disorders and trauma.*
![KenSho](dream_logo.png)

o Due to memory complication we were not able to attach the final fine tuned model weights into the github repo.

For INNOVERSE 12 HACKATHON, we are building a LLM based dream interpretation for better diagnosis of patients with psychological disorders. 

The dataset is in the textual format with the name: Dataset.txt which contains 64 dreams and their corresponding interpretations. We built this textual file manually as we were not able to find any dataset with the same (Dream - Interpretation)

The requirments.txt file encompasses all the libraries and tech stack needs to be used. 

app.py is a streamlit based user interface program, where given a dream description, it will provide the interpretation. 

dream_logo.png would consists of the logo for our model. 

eval.py contains the code for evaluating scores (specifically 4 dreams and their interpretations). We used BERT model to encode the interpretations and used Cosine Similarity for finding the scores between predicted and actual interpretation. 

finetuned_llama_model.zip contains all the finetuned model tokenizers and model requirements. (note: it doesn't contain model weights, we were not able to attach the same due to memory constraints.)

interpretation.ipynb contains code for fine-tuning the llama 2 - 7b parameter model with out 64 dreams dataset.
