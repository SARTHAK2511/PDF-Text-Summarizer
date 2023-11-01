# PDF-Text-Summarizer

PDF Text Summarization Streamlit App using the MBZUAI/LaMini-Flan-T5-248M Model on Hugging Face.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/your_username/your_app_name)

This project is a PDF text summarization tool that leverages the power of the MBZUAI/LaMini-Flan-T5-248M model available on Hugging Face. It provides an easy-to-use interface for summarizing text from PDF documents.

## Installation

To run this project, you need to install the following Python libraries:
Download the model
```
from huggingface_hub import snapshot_download
snapshot_download(repo_id="lysandre/arxiv-nlp")
```

```bash
pip install langchain streamlit torch transformers accelerate sentence_transformers sentencepiece
```
Navigate to the project directory.
```
git clone https://github.com/your_username/PDF-Text-Summarizer.git


cd PDF-Text-Summarizer
Run the Streamlit app.

streamlit run app.py
```

Access the app in your web browser by following the link provided in the terminal.
Usage
Upload your PDF document to the app.
Select the summarization options.
Click the "Summarize" button.
The app will generate a summary of the PDF text using the MBZUAI/LaMini-Flan-T5-248M model.
Acknowledgments
This project makes use of the MBZUAI/LaMini-Flan-T5-248M model from Hugging Face. For more information, check out the model repository.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
Sarthak Bhatore - [Sarthakbhatore637@gmail.com]
