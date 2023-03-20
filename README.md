# README

let title = "Harry Potter";
console.log(title);

let author = "J. K. Rowling";
console.log(author);

let year = "1997";
console.log(year);

let characters = ["Snape", "Draco", "Dumbledore", "Hagrid"];
console.log(characters);

let isNewerThan2000 = false;
console.log(isNewerThan2000);

let age = 2023 - year;
console.log(age);

console.log(characters[0, 1])


let title = "Open";
console.log(title);

let author = "Andre Agassi";
console.log(author);

let year = "2009";
console.log(year);

let characters = ["Agassi", "Steffi Graf", "Brad Gilbert", "Nick Bollettieri"];
console.log(characters);

let isNewerThan2000 = true;
console.log(isNewerThan2000);

let age = 2023 - year;
console.log(age);
console.log(characters[0, 1])



let favoriteBook = {
    title: "Harry Potter",
    author: "J. K. Rowling",
    year: 1997,
    isNewerThan2000: false,
    characters: ["Snape", "Draco", "Dumbledore", "Hagrid"]
}
console.log(favoriteBook);
console.log(favoriteBook.author);
console.log(favoriteBook.year);
console.log(favoriteBook.characters[2]);



let favoriteBooks = [
    {
    title: "Harry Potter",
    author: "J. K. Rowling",
    year: 1997,
    isNewerThan2000: false,
    characters: ["Snape", "Draco", "Dumbledore", "Hagrid"]
    },
    {
        title: "Open",
        author: "Andre Agassi",
        year: 2009,
        isNewerThan2000: true,
        characters: ["Agassi", "Steffi Graf", "Brad Gilbert", "Nick Bollettieri"]
    }
]

console.log(favoriteBooks[1].title);
console.log(favoriteBooks[0].characters[0]);


console.log(favoriteBooks[0].year - favoriteBooks[1].year);
