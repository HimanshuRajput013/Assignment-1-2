![Screenshot 2025-01-20 094249](https://github.com/user-attachments/assets/08d16961-ede7-4593-a856-7bce7d821a25)

# Chat with PDF 

Project use LlamaParse for document parsing, Langchain for conversational retrieval, and Groq for conversational AI.
The system allows users to upload PDF through a chatbot interface and enables users to ask questions based on the processed content.

## Install Dependencies
```sh
pip install -r requirements.txt
```

## Setup

### Step 1: Install the Required Packages
Create a virtual environment and install the required dependencies:

```sh
python -m venv venv
source venv/bin/activate 
pip install -r requirements.txt
```

### Step 2: Setup the `.env` File
Create a `.env` file in the project root directory with the following content:

```sh
LLAMA_API_KEY=your_llama_api_key
HF_Token = HF_TOKEN
```

Replace `your_llama_api_key` and `your_groq_api_key` with your actual API keys.

### Step 3: Run the Chatbot
Run the chatbot with streamlit:

```sh
streamlit run app.py
```

## Extract Text and Build Vector Store
Upload the PDF file. The system will extract text from the PDF.

## Start the Chat
Once processing is done, you can start interacting with the chatbot. You can query it with questions based on the extracted document.


