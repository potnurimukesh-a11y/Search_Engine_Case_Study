Search Engine Case Study (Python)

📌 Overview

This project is a case study focused on building a basic search engine using Python.
It demonstrates how textual data can be processed, indexed, and searched efficiently using fundamental data structures.

The project is implemented in multiple milestones, gradually improving functionality from basic list operations to a complete searchable index.

---

🎯 Objectives

- To understand text processing and tokenization
- To build an inverted index for efficient searching
- To implement search queries over indexed data
- To explore dictionary-based data structures
- To simulate basic search engine functionality

---

⚙️ Features

- Reads multiple text files from a directory
- Extracts and processes words from files
- Builds an inverted index (word → list of files)
- Supports multi-word search queries
- Returns files containing all query terms
- Displays file titles along with results
- Removes duplicate words and filenames
- Handles punctuation and case normalization

---

🛠️ Technologies Used

- Python
- File handling
- Dictionaries and sets
- String processing

---

🧠 Concepts Applied

- Inverted indexing
- Set operations (intersection)
- Text normalization (lowercasing, punctuation removal)
- Data structures (lists, sets, dictionaries)
- Algorithmic searching

---

📂 Project Structure

Search_Engine_Case_Study/
│
├── Milestone1/
│   └── common_elements.py          # Basic list intersection logic
│
├── Milestone2/
│   └── searchengine.py            # Index creation (inverted index)
│
├── Milestone3/
│   └── searchengine.py            # Search functionality added
│
├── text_files/                    # Input .txt documents
├── README.md

---

▶️ Milestone Breakdown

🔹 Milestone 1: Common Elements

- Implements function to find common elements between two lists
- Uses set intersection
- Builds foundation for search logic

---

🔹 Milestone 2: Index Creation

- Reads ".txt" files from directory
- Extracts words from title and content
- Builds inverted index:
  word → [list of files containing the word]
- Stores file titles

---

🔹 Milestone 3: Search Engine

- Implements search functionality
- Supports multi-word queries
- Uses intersection of file lists to find relevant results
- Displays results with titles

---

▶️ How It Works

1. Read all ".txt" files from a directory
2. Process text:
   - Convert to lowercase
   - Remove punctuation
3. Build inverted index
4. Accept user query
5. Find intersection of files containing all query terms
6. Display matching results

---

▶️ How to Run

1. Place text files inside a folder (e.g., "text_files/")

2. Run the program:

python searchengine.py text_files -s

- "-s" → enables interactive search mode

---

📷 Output

- Displays index (if "-s" not used)
- Interactive search results (if "-s" used)

Example:

Query: apple ball
Results:
1. Title: File 1 Title, File: test1.txt

---

📚 Example Query Logic

- Query: "apple carrot"

- Result: files containing both words

- Query: "apple nope"

- Result: no matches

---

📚 Conclusion

This project demonstrates how a basic search engine can be implemented using core programming concepts. It highlights the importance of indexing and efficient data retrieval techniques.

---

👨‍🏫 Acknowledgement

This case study was developed based on concepts and guidance provided during classroom sessions by the instructor.
