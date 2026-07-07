/*
Object oriented programming Lab 3 question 2

Complete the Book class by
1.	Declaring the String title instance variable
2.	Declaring the String author instance variable
3.	Writing a constructor method to initialise Book objects, with input parameters for title and author
Complete the main method by
1.	Using new to create an instance of Book with constructor input "Pride and Prejudice" and "Jane Austen"
2.	Printing the Book instance variables using the standard ouput formatting (See example output)






For example:
Test	Result
Book.main(new String[]{})	Title = Pride and Prejudice
Author = Jane Austen

Book p = new Book("X","Y");
System.out.println(p.title);	X

Book p = new Book("X","Y");
System.out.println(p.author);	Y








public class Book {
    
    // Declare instance variables here
    
    
    //write constructor with input parameters for title and author
    
    
    public static void main(String[] args) {
        // Create an instance of Book with constructor inputs
    
        
        // Print Book instance variables in standard output format
    }
}
*/
public class Book {
    // Declare instance variables
    String title;
    String author;

    // Constructor method to initialize Book objects
    public Book(String title, String author) {
        this.title = title;
        this.author = author;
    }

    public static void main(String[] args) {
        // Create an instance of Book with constructor inputs
        Book myBook = new Book("Pride and Prejudice", "Jane Austen");

        // Print Book instance variables in standard output format
        System.out.println("Title = " + myBook.title);
        System.out.println("Author = " + myBook.author);
    }
}
