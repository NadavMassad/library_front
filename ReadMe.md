This repo is the client side of the Library project.

The images folder contains the images for the favicon, home button, and x button.
The styles folder contains all the css files to every html file.

inside each HTML file we start with a bunch of imports.
the JS part contains a few funcions - See description in the file.


We have 4 HTML files.
`index.html` - The home page of the website.
It has few things in it:
1. Instructions on how to loan a book
2. The ruled of the library
3. shows all active loan - book that haven't been retruned yet, and a button to return it.

`customer.html` - the page to displays all the customers.
It also allows to add customers, loan a book by customer, and delete it(deactivate it).
You can search by name/city. and activate a past customer.
When you loan a book, the loan date is set to the current date.

`books.html` - the page to displays all the books.
It also allows to add books, and delete it(deactivate it).
You can search by name/author. and activate a past books.
You can also filter by book type:
type 1 - can be loaned up to 10 days
type 2 - can be loaned up to 5 days
type 3 - can be loaned up to 2 days

`loans.html` - the page to displays all loans.
You can search by book name/ customer name.
You can also filter by loan status:
1. onTime - book returned on time.
2. Late - book returned Late.
3. Pending - Wasn't returned yet.

Theres a return button to return the book on the current date.
