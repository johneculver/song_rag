# Song Finder RAG (Retrieval-Augmented Generation)

# Requirements
- Local Python installation
- Local Jupyter Notebooks installation either in Terminal or VSCode
- Local qdrant-client==1.4.0 
- Download and run a .llamafile LLM locally, such as phi-2
- Local sentence-transformers==2.2.2
- Local pandas==1.3.5
- Local ipykernel
- Local ipywidgets
- Local openai==1.11.1

# Recommended Tools
I have found that running this in Jupyter Notebooks through Visual Studio Code was the simplest way to run and iterate on this project.

# Installation 
Open in Jupyter Notebooks either in a browser or VSCode

# Configuration
These are the items that might be changed if you want to use a different LLM or dataset:
- collection-name
- encoder.encode(doc["primaryGenreName"]): "primaryGenreName" represents a column in the CSV file. This will vary with different datasets
- user-prompt
- Role user content and Role system content

# Observations
While going through this project, I was surprised by how much I had to install and concurrently run to make this work. I'm looking forward to building more local GenAI tools.

One snag I hit while working on this was the Base URL. The v1 path was not visible when running the LLM in my browser, but was essential to access the correct libraries to complete the chat complete function. 

