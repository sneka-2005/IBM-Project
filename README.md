Smart SDLC


🤖 AI Code Analysis & Generator

An AI-powered application that helps analyze software requirements from PDFs or plain text and generate code in multiple programming languages. Built using Gradio, PyTorch, and IBM Granite LLM.


✨ Features

📄 Requirement Analysis

Upload a PDF or enter text to extract functional requirements, non-functional requirements, and technical specifications.


💻 Code Generation

Generate code snippets in multiple programming language:
Python

📂 History Tracking

Keeps a record of all requirement analyses and generated code.


⬇️ Downloadable History

Export all previous analyses and generated code as a .txt file.


🎨 Interactive UI

Built with Gradio Blocks for a smooth, modern, and user-friendly interface.

🛠️ Installation

1. Clone this repository:

git clone https://github.com/sneka-2005/IBM-Project.git


2. Install dependencies:

pip install -r requirements.txt

requirements.txt should include:

torch
transformers
gradio
PyPDF2


🚀 Usage

1. Run the application:

python app.py


2. The Gradio app will launch automatically. If running locally, open:

http://127.0.0.1:7860


3. Workflow:

Code Analysis Tab

Upload a PDF or enter requirements → Click Analyze → View structured analysis.


Code Generation Tab

Enter requirement + select programming language → Click Generate Code → Copy or download the output.


History Download

Click ⬇️ Download History to save previous results.


🔮 Future Enhancements

🌐 Deploy as a web service with user authentication.

🧠 Add multi-model support (other LLMs like GPT, LLaMA, etc.).

📝 Support for Word documents (.docx) in addition to PDFs.

📊 Export results to Excel/CSV for requirement documentation.

🖼️ Enhanced UI/UX with dark mode.

🧩 Integration with project management tools (Jira, Trello, GitHub Issues).


📚 Tech Stack

Backend Model: IBM Granite LLM (granite-3.2-2b-instruct)

Libraries: PyTorch, Hugging Face Transformers, Gradio, PyPDF2

Frontend: Gradio Blocks (Interactive UI)


🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.


📄 License

This project is licensed under the MIT License.
