# Book-Names
Basic Java project that stores different book objects in an array
The 'Books' class:  declares reference to books object, declares variables, getters and setters were declared, three different book objects were declared to store in an array.  Method 'Books' within this class states what 'Books' information is contained.
'BookMain' extends the 'Books' class & implements interfaces': bookName, bookAuthorName, & bookGenre.  There are calls within the main method:  'bks.Books()' calls a method that is within the 'Books' class; 'bk1.AssignBook1Values()' calls a method within the 'Book1' class, which sets BookName, BookAuthorName, & BookGenre for Book1; 'bk2.AssignBook2Values()' calls a method within the 'Book2' class, which sets BookName, BookAuthorName, & BookGenre for Book2; 'bk3.AssignBook3Values()' calls a method within the 'Book3' class, which sets BookName, BookAuthorName, & BookGenre for Book3. The values for each of these three books is then stored within an array (also happening within the 'main' method, within the 'BookMain' class).  Finally, there are a series of 'for' loops which output the names of the books, the books' authors, and the books' genres.
