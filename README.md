# Soma word corpora extractor

Soma is a simple tool, which, when fed with a text, will produce a list of words appearing in that text,
sorted by usage frequency.

## Technical inspiration

The technical breakdown of the project stems from _Think OCaml_, exercise 16.1, Word frequency analysis (Downey & Monje, 2008, p.105).

## To do

- Document background research and references
- Exercise 16.2: Go to Project Gutenberg (gutenberg.net) and download your
  favorite out-ofcopyright book in plain text format. Modify your program from
  the previous exercise to read the book you downloaded, skip over the header
  information at the beginning of the file, and process the rest of the words as
  before
  - Modify the program to count the total number of words in the book, and the
    number of times each word is used. Print the number of different words used
    in the book
- Exercise 16.3: Modify the program from the previous exercise to print the 20
  most frequently-used words in the book
- Exercise 16.4: Modify the previous program to read a word list and then print
  all the words in the book that are not in the word list
  - How many of them are typos?
  - How many of them are common words that should be in the word list, and
  - how many of them are really obscure?

## References

- Downey, A., & Monje, N. (2008). Think OCaml: How to Think Like a Functional Programmer (Version 0.1.1). Green Tea Press; The LATEX source for this book is available from http://www.thinkpython.com. https://greenteapress.com/thinkocaml/thinkocaml.pdf
