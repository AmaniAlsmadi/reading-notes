# Reading
 <br>

1. **What does .map() return?**
- value
2. **If I want to loop through an array and display each value in JSX,how do I do that in React?**
-  const elements = [] //..some array<br>
const items = []<br>
for (const [index, value] of elements.entries()) {<br>
  items.push(<Element key={index} />)<br>
}<br>

3. **Each list item needs a unique**  key .

<br>

4. **What is the purpose of a key?**
-  Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

<br>
________________________________________________________
<br>
<br>
<br>


1. **What is the spread operator?**
- It takes in an iterable (e.g an array) and expands it into individual elements.(also using ...)

2. **List 4 things that the spread operator can do.**
- Copying an array
- Using Math functions
- Using an array as arguments
- Adding an item to a list

3. **Give an example of using the spread operator to combine two arrays.**
- const cars = ['🚗', '🚙'];<br>
const trucks = ['🚚', '🚛'];<br>
const combined2 = [...cars, ...trucks];<br>

4. **Give an example of using the spread operator to add a new item to an array.**
- const fewFruit = ['🍏','🍊','🍌']<br>
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]<br>

5. **Give an example of using the spread operator to combine two objects into one.**
- const objectOne = {hello: "🤪"}<br>
const objectTwo = {world: "🐻"}<br>
const objectThree = {...objectOne, ...objectTwo}<br>

<br>

# Videos

<br>

1. **In the video, what is the first step that the developer does to pass functions between components?**
- create the action in the parent component
2. **In your own words, what does the increment function do?**
- pass through the object then if the input equal name, if true increment one => counted how many time we click on button
3. **How can you pass a method from a parent component into a child component?**
- The method is passed as a prop to a child component.
4. **How does the child component invoke a method that was passed to it from a parent component?**
- The child component then invokes the prop.<br>
- The parent function is then called, usually changing something.