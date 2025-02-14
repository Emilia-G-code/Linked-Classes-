# Linked-Classes-
class Book:
    def __init__(self, name="Book"):
        self.name = name

class Library:
    def __init__(self):
        self.books = []

    def add_books(self, Book):
        self.books.append(Book)

    def print_books_names(self):
        if self.books!= []:
            print("Names of books in the Digital Library:")
            for books in self.books:
                print(books.name)
        else:
            print(f"There are no books in the Digital Library at the moment.")

Harry_Potter = Book("Harry Potter")
Lord_of_The_Rings = Book("Lord of the Rings")
Sherlock_Holmes = Book("Sherlock Holmes")
Lib= Library("Digital Library")

Lib.add_books(Harry_Potter)
Lib.add_books(Lord_of_The_Rings)
Lib.add_books(Sherlock_Holmes)
Lib.print_books_names()
