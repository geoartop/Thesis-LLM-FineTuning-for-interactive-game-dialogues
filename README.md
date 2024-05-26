## This is the repository for my thesis on LLM finetuning for interactive game dialogues
### Author: Giorgos Artopoulos

Below  you will find the following files:
- `README.md`: This file
- `dataset_final_prep.ipynb`: The notebook used to prepare the dataset for the experiments
- `mistral_own_data_finetune.ipynb`: The notebook used to finetune the LLM on the dataset with lora
- `testing_for_error`: Directory containing the json files used to test that the datageneration tokenization work correctly
- `dataset_final_results`: Directory containing the json files with the training testing and validation data
- `testing_excel.xlsx`: The excel containing the dataset used, it was created using the dialogues in the following pages [Skyrim:Generic](https://en.uesp.net/wiki/Skyrim:Generic_Dialogue)
 and [Skyrim:Guard Dialogue](https://en.uesp.net/wiki/Skyrim:Guard_Dialogue)