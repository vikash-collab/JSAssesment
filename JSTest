/*  
 1. Here we crearted a object library that store the data of the books related.
 2. and  then define a funtion that helps to Adda the books.
 3. then again define funtoin that list the dtata of the library  and at the ebd to taken processors on that.
 4. Better managing data to list getTotalBooks() of BOOks. 
*/

// Create a variable to hold your books
let library = [];

// This function will take in some values as parameters, create a
// book object using the parameters passed to it for, 
// and store it in the variable above.
function addBook(title, author, year, genre) {
    const book = {
        title: title,
        author: author,
        year: year,
        genre: genre
    };
    library.push(book);
    console.log("Added Book: " + title + " by " + author + " (" + year + ")");
}

// Create a "loop" that will go through an "array" of books
// and print their data with console.log()
function Details_of_Books() {
    for(let index = 0; index < library.length; index++) {
        console.log("Book" + (index + 1));
        console.log("Title: " +  library[index].title);
        console.log("Author: " + library[index].author);
        console.log("Year: " + library[index].year);
        console.log("Genre: " + library[index].genre);
        console.log('---');
    };
}

// Print the total number of books we have added 
function getTotalBooks() {
    console.log("Total number of books:" + library.length);
}

// Call your functions below 
addBook("The God of Small Things", "Arundhati Roy", 1997, "Fiction");
addBook("Midnight's Children", "Salman Rushdie", 1981, "Historical Fiction");
addBook("A Suitable Boy", "Vikram Seth", 1993, "Fiction");
addBook("The White Tiger", "Aravind Adiga", 2008, "Fiction");

Details_of_Books();

getTotalBooks();
