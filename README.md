# ArXivSearch

Tool to find and save information about research papers from arXiv. You type a topic (like "AI" or "machine learning"), and it fetches up to 5 papers, saving their details (title, authors, summary, etc.) in a JSON file. You can also ask for details about a specific paper using its ID.

After running all cells, enter a query like "Search for papers on AI" or "Extract info for paper 1310.7911v2" in the chat loop. Make sure you have a Groq API key in a .env file and install required packages (arxiv, groq, python-dotenv). The results are saved in a papers folder.
