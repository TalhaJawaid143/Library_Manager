# Library Manager:
The Library Manager is a simple command-line application that allows users to manage their book collection. With this tool, you can add, remove, search, and view your books. It also provides statistics about the books you've read. The application stores your book data in a JSON file for persistence.

# Features
* Add Book:

Enter details such as the title, author, publication year, genre, and reading status (read/unread).

* Remove Book:

Delete a book from your library by title.

* Search Books:

Search for books by title or author.

* Display All Books:

View a list of all books in your library with their details and reading status.

* Statistics:

View the total number of books and the percentage of books you’ve read.

#Technologies Used:
* Streamlit – While the code uses input prompts, you could refactor the input and output to be part of a Streamlit web app for a more user-friendly experience.

* JSON – Used for storing book data.

* Python – The primary programming language.

* Requirements
* Python 3.x

No additional libraries required.

#How to Run:

Clone the repository:
git clone https://github.com/TalhaJawaid143/library-manager.git

Navigate to the project directory:
cd library-manager

Run the script:
python library_manager.py
Follow the prompts in the terminal to manage your library.

#Example Data:
Here’s a sample of how your library could look in the library.txt file:
[
  {
    "title": "A Millionaire in a Blink",
    "author": "Talha Jawaid",
    "year": 2025,
    "genre": "Thriller",
    "status": "Completed"
  }
]
#Contributing:

Feel free to fork the repository, create a new branch, and submit pull requests for improvements.

