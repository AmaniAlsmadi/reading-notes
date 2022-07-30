# Reading
 <br>

1. **What is the single responsibility principle and how does it apply to components?**
-  is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

2. **What does it mean to build a ‘static’ version of your application?**
- A static build is a compiled version of a program which has been statically linked against libraries.

3. **Once you have a static application, what do you need to add?**  
-Create a Static Site

4. **What are the three questions you can ask to determine if something is state?**
- Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. **How can you identify where state needs to live?**
- First, add an instance property this.state = {filterText: '', inStockOnly: false} to FilterableProductTable’s constructor to reflect the initial state of your application. Then, pass filterText and inStockOnly to ProductTable and SearchBar as a prop. Finally, use these props to filter the rows in ProductTable and set the values of the form fields in SearchBar.

<br>

______________________________________
<br>

1. **What is a “higher-order function”?**
- Functions that operate on other functions, either by taking them as arguments or by returning them

2. **Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**
- calling an arrow function to compare between 2 values and return a boolean value

3. **Explain how either map or reduce operates, with regards to higher-order functions.**
-  The map function has a single argument which is a closure (a function) that it calls as it loops over the collection. This closure takes the element from the collection as an argument and returns a result. The map function returns these results in an array.

- Use reduce to combine all items in a collection to create a single new value.