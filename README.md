# BioAgents: Fine-Tuning Phi-3 with Retrieval-Augmented Generation (RAG)

## Project Overview

This project was developed during my internship at IIITDM Kurnool.

The objective is to improve biomedical question answering by fine-tuning Microsoft's Phi-3 Mini model and integrating it with a Retrieval-Augmented Generation (RAG) pipeline using FAISS for efficient document retrieval.

## Features

- Fine-tuned Microsoft Phi-3 Mini 4K Instruct model
- Retrieval-Augmented Generation (RAG)
- FAISS vector database for semantic search
- LoRA/PEFT fine-tuning
- Biomedical document retrieval
- Model evaluation and result generation

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- TRL
- FAISS
- Sentence Transformers
- Pandas
- NumPy
- Kaggle Notebook

## Project Workflow

1. Clone the Bioinformagus repository
2. Prepare biomedical datasets
3. Fine-tune Phi-3 Mini using LoRA
4. Build FAISS vector index
5. Retrieve relevant biomedical documents
6. Generate answers using the fine-tuned model
7. Evaluate model performance

## Project Structure

```
BioAgents/
│── notebook.ipynb
│── README.md
│── requirements.txt
│── phi3_bioagent_adapter/
│── faiss_index.bin
│── chunks.pkl
└── bioagents_evaluation_results.csv
```

## Installation

```bash
git clone https://github.com/yourusername/BioAgents.git
cd BioAgents
pip install -r requirements.txt
```

## Results

- Successfully fine-tuned the Phi-3 Mini model.
- Built a FAISS-based retrieval system.
- Generated biomedical responses using RAG.
- Saved evaluation results for performance analysis.

## Future Improvements

- Use larger biomedical datasets.
- Improve retrieval accuracy.
- Deploy as a web application.
- Add support for multiple LLMs.

## Author

**Naveen Kumar**

M.Tech (Computer Science & Engineering)

Intern – IIITDM Kurnool
