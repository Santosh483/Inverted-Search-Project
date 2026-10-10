# Inverted-Search-Project
Inverted Search Project
📌 Project Overview

The Inverted Search Project is a file-processing application developed in C that implements an inverted index using data structures such as a hash table and linked lists.

An inverted index maps each unique word to the list of files in which it appears, along with the number of occurrences of that word in each file. This technique is commonly used in search engines to retrieve information efficiently.

🎯 Objectives
Understand file handling in C.
Implement hash tables and linked lists.
Build an inverted index for multiple text files.
Search for words across indexed files.
Display the frequency of words in each file.
Save and update the index using file operations.
✨ Features
Create Database: Read multiple text files and build an inverted index.
Search Database: Search for a word and identify the files containing it.
Display Database: Display the complete indexed database.
Update Database: Add new files or update the index using a saved database.
Save Database: Store the indexed information in a file for future use.
🛠️ Technologies Used
Programming Language: C
Data Structures: Hash Table, Linked List
Concepts: File Handling, Pointers, Dynamic Memory Allocation, String Processing
📂 Project Structure
Inverted_Search/
├── main.c
├── inverted_search.h
├── create_database.c
├── search_database.c
├── display_database.c
├── save_database.c
├── update_database.c
├── validation.c
├── Makefile
├── input.txt
└── README.md


Note: The file names may vary depending on your implementation.

⚙️ Compilation

Compile the source files using GCC:

gcc *.c -o inverted_search


If your project includes a Makefile, you can compile it using:

make

▶️ Execution

Run the compiled executable:

./inverted_search


On Windows, use:

inverted_search.exe

🔍 How It Works
Accept one or more input text files.
Validate the filenames and ensure the files can be opened.
Read each file and extract individual words.
Calculate a hash index for each word.
Store each unique word in the hash table.
Maintain a list of files containing the word and its occurrence count.
Allow the user to search, display, save, or update the database.
🧪 Sample Input

Suppose the input files contain the following text.

file1.txt

hello world hello


file2.txt

hello c programming

📊 Sample Inverted Index
Word	File Name	Occurrences
hello	file1.txt	2
hello	file2.txt	1
world	file1.txt	1
c	file2.txt	1
programming	file2.txt	1
💻 Sample Output
1. Create Database
2. Display Database
3. Search Database
4. Save Database
5. Update Database
6. Exit

Enter your choice: 3
Enter the word to search: hello

Word: hello
File: file1.txt
Count: 2

File: file2.txt
Count: 1


The menu and output may differ based on your implementation.

📚 Concepts Learned
Hashing and collision handling
Singly linked lists
File input/output operations
Dynamic memory allocation
String tokenization and comparison
Database creation and persistence
Modular programming in C
🚀 Future Enhancements
Support case-insensitive searching.
Implement prefix-based search.
Improve search performance for large datasets.
Add support for more file formats.
Provide ranked search results based on word frequency.
👨‍💻 Author

Name: Your Name

Project: Inverted Search

Language: C

📄 License

This project is intended for educational purposes and can be modified and extended for learning and experimentation.
