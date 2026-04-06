# PSR-Pred
To make predictions, follow these steps:

Clone the Repository
Clone the PSR-Pred repository using the following command:

git clone https://github.com/bioplusAI/PSR-Pred.git
Open Command-Line Interface
Launch a command-line interface such as Command Prompt (Windows) or Terminal (Linux/macOS).

Navigate to the Repository Directory
Move into the cloned repository folder:

cd PSR-Pred

Create the Conda Environment
Create the required environment using the provided configuration file:

conda env create -f environment/environment.yml

Activate the Environment
Activate the newly created environment:

conda activate PSR-Pred
Download the Pre-trained Nucleotide Transformer
Download the model from the following link:
https://huggingface.co/InstaDeepAI/nucleotide-transformer-v2-500m-multi-species
Save the downloaded files in directory name it model.

Download the Fine-tuned Model Weights
Download the fine-tuned weights from:
https://huggingface.co/bioplusAI/fine-tuned-nucleotide-transformer-for-phase-separating-rnas
Place the files in the directry name it weights.

Prepare Input Sequences
Insert your query RNA sequences in FASTA format into the Input_sequences.txt file located in the Input_sequences directory.

Launch Jupyter Notebook
Start Jupyter Notebook by executing:

jupyter notebook
Run the Prediction Pipeline
Open the sorce-code.ipynb notebook from the Source-code directory and execute all cells to perform predictions.
