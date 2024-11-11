download ollama
https://ollama.com/download

in terminal type the following command
ollama

pick an llm from the following link recommend Llama 3
https://github.com/ollama/ollama

in the terminal type the following
ollama pull llama3

in VS code type the following to setup the environment
python3 -m venv chatbot

to activate the environment type the following
source chatbot/bin/activate

install the packages:
pip install langchain langchain-ollama ollama pymupdf pandas python-pptx python-docx pytesseract pillow

to run the build type
python3 main.py

to turn off the virtual environment type the following
deactivate
