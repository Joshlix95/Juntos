###### Juntos Assignment
###### Author: Josuel Musambaghani
###### Email: <joshlixmus@gmail.com>
===

## Contents 
- **Project Title: Concordance**
- **Overview**
A 'concordance' is an alphabetical list of the words present in a text with a count of how often each word appears and citations of where each word appears in the text (e.g. page number).

- **Example usage**
A concordance is used in books to show how many times each word occurs, and the specific location where the word may be found.
- **Getting Started**
The main language used in this project is ***Python***. The repository (on GitHub) containing the code for the project is called **Juntos** and the python file itself in the repository is called `JosuelJuntos.py`. 
- **Design Goals**
The goal of our project is to write a code that will be  able to get input from one file (in my case, I used a `.txt` file), to read and manipulate data from the input, and at the end, the code must write, in an empty file, an ordered (sorted) list of words that shows the number of occurences and the specific location of the word at each occurence.  
- **Detailed Usage**
In this project, we assumed that data from the input file are simple; they only contain punctuation marks and spaces. 
As talking about punctuations, it is to be noted that a library called `nltk` had to prealably be installed in the directory for our python compiler to deal with punctuation marks.  

## Formatting
The program (the code itself) is structured into three parts: 
1. Part1: *** Getting data from the user *** (From the first file)
After importing the necessary modules (`nltk` and `string`), this part prompts the user to enter a file name from which data should be read. 
Once data are accessed, the operation `nltk.sent_tokenize(text)` breaks the data into elements with resect to punctuations marks. The output here is a list of strings, each string representing a sentence from the input file. 
2. Part2: *** Manipulating data ***
3. Part3: Results: *** Writing ouptput to the second file.***
## Supporting documentation
The project mainly used `for` loops. Outside documentations did not apply. 
However, some materials were helpful to double-check some skills that may have been forgotten about libraries and modules. We have:
* ***Think Python***: a book by Allen B. Downey 
    - Link: <http://www.greenteapress.com/thinkpython/>
* Notes from my Python Class
    - Link <http://glassy-filament-680.appspot.com/> 


