# Skribblio
Python program to create a random skribblio word list



skribblio_masterlist.csv is a list of all possible words to add to the custom word list and is used by skribblio_lister to write the custom word list in the skribblio_list.csv.

if you want to add words to the masterlist.csv, put the word list into the skribblio_checker.py and then run the skribblio_checker program. This will rewrite the new_words.csv list to remove any duplicate words from the words being added to prevent any words being picked more often than other.

skribblio_doublechecker.py will take a word list that is input to the double_remover.csv and will create a new list in the skribblio_list.csv without the duplicate words
