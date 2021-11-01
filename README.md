# Golang_CardDeck
Minor CardDeck functions to learn the basics of GoLang :

1. newDeck - Create and retrun a list of playing cards. Essentially an array of strings (slice of strings)
2. print - a "method" that log out the contents of a deck of cards
3. shuffle - shuffle randomly all the cards in a deck
4. deal - creates a  'hand' of cards
5. saveToFile - save a list of cards to a file on a local machine
6. newDeckFromFile - load a list of cards from the local machince based on the function saveToFile

Tests : 

1. TestNewDeck - tests the length of the cards, the first card value and the last card value.
2. TestSaveToDeckAndNewDeckTestFromFile - tests the saveFile and newDeckFromFile function that save and load a file form the local machine
