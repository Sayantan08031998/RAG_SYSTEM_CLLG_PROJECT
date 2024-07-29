📄 Document-based Q&A System
This project is a Document-based Question & Answer (Q&A) System that leverages advanced language models and embeddings. Users can upload a document and ask questions, receiving answers based on the content of the uploaded document. The system is built using the following technologies:

Hugging Face Models: For language understanding and generation.
Llama Index: For creating vector store indices and managing embeddings.
Gradio: For creating a user-friendly web interface.
✨ Features
🔐 Login to Hugging Face: The system requires a Hugging Face token for access to models.
📂 Document Loading: Users can upload documents, which are then processed to extract relevant information.
🧠 Language Model Initialization: Utilizes the Llama-2-7b-chat-hf model from Meta Llama, fine-tuned for chat and Q&A tasks.
🔎 Embedding Model: The all-mpnet-base-v2 model from Sentence Transformers is used to create embeddings of the document content.
🔧 Service Context Creation: Sets up the necessary context for querying the language model and embeddings.
📚 Vector Store Index Creation: The document is indexed using vector embeddings, facilitating efficient information retrieval.
❓ Query Processing: Users can ask questions, and the system returns answers based on the indexed document.
⚙️ Setup and Usage
📋 Prerequisites
Python 3.x
Hugging Face Account (with a valid API token)

📥 Installation
Clone this repository: 
git clone https://github.com/yourusername/document-qa-system.git
cd document-qa-system

Install the required packages:
pip install -r requirements.txt

🚀 Running the Application
Replace the placeholder token in process_input with your Hugging Face token:
token = "your_huggingface_token"

Launch the application:
python app.py

Access the web interface via the URL provided in the terminal.

📝 Usage Instructions
📤 Upload Document: Click the "Upload Document" button and select the document you want to query.
💬 Enter Your Question: Type your question in the textbox provided.
📋 Get Answers: The system will process your question and return an answer based on the content of the uploaded document.
📄 License
This project is licensed under the MIT License.

🤝 Contributions
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

🙏 Acknowledgments
Hugging Face
Gradio
Llama Index

