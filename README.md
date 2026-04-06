# PSR-Pred
To make predictions, follow these steps:

Clone the PSR-Pred repository using command: git clone https://github.com/bioplusAI/PSR-Pred.git
Launch a command-line interface (e.g., Command Prompt or Terminal).
Navigate to the cloned repository using the command: cd PSR-Pred
Create the conda environment by executing: conda env create -f environment/environment.yml
Activate the newly created environment: conda activate PSR-Pred
First download the Nuclotide transformer using this link https://huggingface.co/InstaDeepAI/nucleotide-transformer-v2-500m-multi-species
Start Jupyter Notebook by running: jupyter notebook
Fine tune the Nucleotide transformer using source code, first adjuust the paths for downloaded nucleotide transformer and dataset, and then run the code
Save the fine-tuned model
Insert your query protein sequences (in FASTA format) into the Input_sequences.txt file located within the repository Input_sequences.
Open the predictor.ipynb notebook from the pridictor directory in Jupyter Notebook and execute the code.
Note: The initial fine tuning may require several minutes to complete, subsequent predictions will be executed within seconds. The fine-tuned model is > 25MB which exceed the guithub uploading filer size limit for tthat we have provide source code to first fine tune the model and then use it to make predictions.
