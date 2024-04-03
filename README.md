# Inverted-Index
This Java program implements an inverted index, a data structure used in information retrieval to quickly find which documents contain a given term. The program reads multiple text files, builds an index of terms with their corresponding document frequency, and allows users to search for terms in the indexed documents.

How it works
Building the Index: The program reads text files and tokenizes them into words. For each word encountered, it updates the index, storing information about the term's frequency in the collection and its occurrence in each document.

Searching: Users can input a word to search for. The program checks if the term exists in the index and displays the number of documents containing the term along with the document IDs and the number of occurrences of the term in each document.

Main Components
Posting: Represents a posting list entry containing the document ID and the document term frequency.
DictEntry: Represents an entry in the index, containing document frequency, term frequency, and a posting list.
Index: A HashMap storing terms as keys and DictEntry objects as values.
Usage
Compile and run the program.
Input a word to search for.
The program displays the number of documents containing the word and their corresponding document IDs and term frequencies.
Example
Suppose we have a collection of text files file1.txt, file2.txt, ..., file10.txt. Upon searching for a word, the program outputs the number of documents containing the word and their document IDs along with term frequencies.

Note
The program assumes text files are located at specific paths. Adjust the file paths in the filenames array according to your directory structure.
This implementation provides a basic example of an inverted index. Further enhancements could include optimizations for larger datasets and support for more complex queries.

![out put](https://github.com/MagedZarif/Inverted-Index/blob/main/IR.png)

