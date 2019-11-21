# Week 1 day 5. JS Object lab1

### Lab: The Reading List

Keep track of which books you read and which books you want to read!

- Create an array of objects, where each object describes a book and has properties for the title (a string), author (a string), and alreadyRead (a boolean indicating if you read it yet).
- Iterate through the array of books. For each book, log the book title and book author like so: "The Hobbit by J.R.R. Tolkien".
- Now use an if/else statement to change the output depending on whether you read it yet or not. If you read it, log a string like 'You already read "The Hobbit" by J.R.R. Tolkien', and if not, log a string like 'You still need to read "The Lord of the Rings" by J.R.R. Tolkien.'


//

var books = [
  
 {
    title : "got",
    author: "A",
    alreadyread: true
    
  },
  
  {
    title : "book2",
    author: "B",
    alreadyread: false
  
  },
  
  
  {
    title : "book3",
    author: "C",
    alreadyread: true
    
  }]; 


for (let i=0; i<books.length; i++){
  console.log("the " +books[i].title + " by  " + books[i].author);
  
  
}



### Lab: The Movie Database

It's like IMDB, but much much smaller!

- Create an object to store the following information about your favorite movie: title (a string), duration (a number), and stars (an array of strings).
- Print out the movie information like so: "Puff the Magic Dragon lasts for 30 minutes. Stars: Puff, Jackie, Living Sneezes."

///


var movie = {

  taitle : " baby boss" ,
  duration : 120 ,
  stars :["AAA","aaa","EEE"],

}
console.log(movie.taitle + " last for " + movie.duration+" minutes stars :" + movie.stars )



  
  
  - Maybe the [join](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join) method will be helpful here
