Project Overview
This project implements a Natural Language Processing (NLP) pipeline within a Jupyter Notebook (NLP_PBL.ipynb). It showcases key NLP processes, including text preprocessing, tokenization, and language model integration. For a detailed understanding of the project, please refer to the Project Report.

Key Highlights (Refer to Project Report for Details)
Objectives
Efficiently preprocess and tokenize text data using NLP techniques.
Use subword tokenization for optimal vocabulary management.
Integrate transformer-based models for various NLP tasks.
Implement interactive feedback mechanisms using Jupyter widgets during data processing.

Technologies Used
Python 3: Primary programming language.
Jupyter Notebook: Interactive coding and demonstration environment.
Hugging Face Transformers: For model and tokenizer management.
SentencePiece or Similar: Subword tokenization via .spm files.
ipywidgets: For progress bars and interactive elements.
PyTorch or TensorFlow: Deep learning backend (inferred).
Numpy and Pandas: Data manipulation and preprocessing.

Workflow
Data Loading: Loads source.spm and tokenizer_config.json.
Tokenization: Converts text to token IDs using subword units.
Model Integration: Supports transformer-based models.
Progress Monitoring: Uses interactive widgets for real-time feedback.

How to Run
Ensure you have Python 3 installed.
Install the necessary packages:

    bash
    pip install transformers torch ipywidgets numpy pandas
    (Note: Choose either torch or tensorflow based on your model requirements.)

Open NLP_PBL.ipynb in Jupyter Notebook or JupyterLab.
Run the cells sequentially to execute the pipeline.

Additional Information
See the accompanying Project Report for a comprehensive analysis, including results, limitations, and potential future work.
Ensure that all necessary files (source.spm, tokenizer_config.json) are accessible in the correct directories.
For any further inquiries or issues, refer to the contact information provided in the Project Report.
