# Web-Practical-Assignment_02-

01. use Library
This command switches to (or creates if it doesn't exist) a database named Library.

02. db.createCollection("books")
This creates a new collection called books to store all the book records.

03. db.books.insertMany([...])
This adds 10 sample book records into the books collection all at once.

04. db.books.find()
This displays all the books stored in the books collection.

05. db.books.find({ year_published: { $gt: 1950 } })
This shows only the books that were published after 1950.

06. db.books.find({ title: "The Hobbit" })
This searches and shows the book titled "The Hobbit".

07. Insert and update "The Great Gatsby"
First, it adds "The Great Gatsby" to the collection, then updates its year from 1925 to 1926.

08. Update "Moby-Dick" to available: false
This updates the book "Moby-Dick" to show that it is no longer available.

09. checked_out: false for all books
Adds a new field checked_out and sets it to false for every book.

10. checked_out: true for "Adventure" books
Changes checked_out to true for books that belong to the Adventure genre.

11. Delete "Brave New World"
This removes the book "Brave New World" from the collection.

12. Delete all books published before 1930
This deletes all books that were published before the year 1930.
