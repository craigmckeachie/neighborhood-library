# Neighborhood Library

This is a Java project that helps manage a library.

## Interesting Code

I was proud of this method name because I used the words of the business from the requirements to name it.

```java
    public static void enterBookToCheckOut(){
        System.out.print("Enter the id of the book you want to checkout:");
        int id = scanner.nextInt();
        scanner.nextLine(); //eats the carriage return

        Book bookToBeCheckedOut = null;
        for (Book book : books) {
            if ((book.getId() == id)) {
                bookToBeCheckedOut = book;
                break;
            }
        }

```


