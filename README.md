📘 PDF Insight Engine
Built by Kavya Bhardwaj

The PDF Insight Engine is an AI-powered tool designed to extract valuable insights from PDF documents. It combines advanced embedding models, semantic vector storage, and powerful language-generation APIs to provide interactive and detailed answers based on your uploaded documents.

🚀 What This Tool Does
Given any PDF document, the engine:

📄 Extracts text accurately from PDFs.

🔖 Breaks documents into semantic chunks.

🧠 Generates embeddings using Sentence Transformers.

🔍 Stores and retrieves information efficiently via Pinecone Vectorstore.

✨ Provides refined, detailed answers using Cohere’s generative models.

🧠 Technologies Used
Component	Technology Used
PDF Text Extraction	✅ LangChain (PyPDFLoader)
Semantic Embeddings	✅ SentenceTransformers (all-MiniLM-L6-v2)
Vector Database	✅ Pinecone Vectorstore
Enhanced Responses	✅ Cohere API (command-xlarge)
Text Processing	✅ LangChain Text Splitter, NLTK
OCR (Optional)	✅ Poppler, Tesseract

🧩 Smart Features
✅ Intelligent semantic chunking of text.

✅ Rapid similarity-based search for document querying.

✅ Cohere API integration for contextually refined answers.

✅ Supports fallback and retry logic for robust processing.

📦 How to Run
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Kavya071/PDF-Insight-Engine.git
cd PDF-Insight-Engine
2. Install Dependencies
bash
Copy
Edit
pip install openai==0.27.2 langchain-community sentence_transformers pinecone-client cohere nltk unstructured
sudo apt-get install poppler-utils tesseract-ocr
3. Set Up API Keys
Replace with your actual API keys:

python
Copy
Edit
PINECONE_API_KEY = "your_pinecone_api_key"
COHERE_API_KEY = "your_cohere_api_key"
4. Run the Application
Run the notebook (PDF_Insight.ipynb) in Google Colab or locally:

bash
Copy
Edit
jupyter notebook PDF_Insight.ipynb
Then follow the prompts to upload PDFs and enter queries interactively.

📧 Contact
Feel free to connect:

✉️ bhardwajkavya099@gmail.com

Built with 💡 by Kavya Bhardwaj
