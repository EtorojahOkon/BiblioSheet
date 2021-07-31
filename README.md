# BiblioSheet
A library to get scripture citations

To use, create a new instance of the class BiblioSheet eg var n = new BiblioSheet()

Call the getScripture() method

This method carries an object as parameter

The object parameter has this format 

{'book' : 'Hebrews', 'chapter': "11", "verse" : "1"}

To get a random citation, set the book key to random

Returns an object response in the format 
{
  "book" : "Genesis",
  "chapter" : "1",
  "verse" : "1",
  "text" : "In the beginning God created the heaven and the earth."
}
