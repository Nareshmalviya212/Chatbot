## Chatbot with file managing
Chatbot with handling files and quick response
I build a chatbot using Basic NLP Technique.

1. File Info: Displays information about a specific file, such as its size and last modification time.
2. Search Files: Searches for files matching a specified keyword within the directory.
3. Rename File: Renames a file in the directory.
4. Copy File: Copies a file from one location to another within the directory.
5. Delete File: Deletes a specified file from the directory.
The main() function prompts the user for a directory path and then enters a loop to receive user commands. It processes each command and provides appropriate responses until the user exits.

![11-Oct-2022-1200x600_SoHY84J](https://github.com/user-attachments/assets/b85ec8d8-88bf-4734-a4d7-09c3fc296f9c)

## Working steps
Directory Interaction: The code interacts with a specified directory where files are located. It prompts the user to input the directory path and verifies its existence.

User Commands: It provides a set of commands that the user can input:
- I took user input and used only those keyword which are required for generate response
- Didn't add any advance technique to process data

Main Loop: The main() function initiates a loop where it continuously prompts the user for input commands until the user decides to exit by typing 'exit'.

Input Processing: The process_input() function processes the user's input command, identifies the action to be performed, and calls the corresponding function.

# Here is sample screenshot of chat
![Screenshot (281)](https://github.com/Nareshmalviya212/Chatbot/assets/79190114/c0655ce2-e617-4d8e-8c2d-09c853c8e2da)

## Chatbot with question answer
### It give you short answer inside of your total corups. for building this Architecture i used Basic and Ground level fundamentals like TF-idf and NLTK.
- Function to Extract Text from PDF: It extracts text from a PDF file using PyPDF2 library.
- Function to Preprocess Text: It preprocesses the extracted text by tokenizing, converting to lowercase, and removing stopwords using NLTK.
- Function to Initialize TF-IDF Vectorizer: It initializes a TF-IDF vectorizer and computes the TF-IDF matrix for the preprocessed text corpus.
- Function to Get Response to User Query: It takes a user query, preprocesses it, transforms it using the TF-IDF vectorizer, calculates cosine similarity between the query and corpus paragraphs, and returns the top matching paragraphs as the response.

Main Function: It demonstrates example usage by extracting text from a PDF, preprocessing it, initializing the TF-IDF vectorizer, and entering a conversation loop where the user can ask questions about the document, and the bot responds based on TF-IDF similarity.

![Screenshot (282)](https://github.com/Nareshmalviya212/Chatbot/assets/79190114/48f8096b-a9eb-4d7d-b39e-702de4d0da02)

