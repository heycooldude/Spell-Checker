SpellChecker
=============

This program is an effort to create a fast spell check as and when a user types in. It automatically shpws the most logical words.
In this we have used a pre populated list of words from where it is checking the characters.

There are total 3 files. 
One is a text file in which all the words are stored. 
Other is a python file which creates and populates a bitmap with all words. It then takes text from standard input. The text is first striped of punctuation and set to lowercase. Then each word is spell checked and output to standard output with the result. 
Last is bimap python file which contains bitmap converter and hash function.
