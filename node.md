1. Describe (in plain English) what Array.map() does.<br>
Array.map goes through each item in an array and executes a piece of code on the item that has been declated within the map function. Upon execution the result is returned and the map function goes to the next item in tbe array and executes the code, then returns the result. 

2. Describe (in plain English) what Array.reduce() does.<br>
Array.reduce goes through each item in an array and executes a callback function on it. It takes four arguments, an accumulator (which is the callback function), a currentvalue (which is the current element being processed in the array, or a value that is provided), an index, (which starts from 1 unless otherwise specified), and an array (which is the source array).

3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
    - With normal Promise .then() syntax
    ```
    superagent('https://swapi.dev/api/people1')
      .then( data => {
        people = {
          name: data.body.name
        }
      })
    ```
    - Again with async / await syntax
    ```
    async function getStarWars() {
      let data = await superagent('https://swapi.dev/api/people1')
      people = {
        name: data.body.name
      }
    }
    ```
4. Explain promises as though you were mentoring a Code 301 level student
A promise essentially guarantees that a result will be given to an asynchronous code request; the result can either be fulfilled or rejected. While the promise is waiting to be fulfilled or rejected it is pending. After the asynchronous code request is complete and the promise is fulfilled or rejected, the promise will execute an attached piece of code, the '.then' or '.catch' portion. Upon execution the promise is complete.

5. Are all callback functions considered to be Asynchronous? Why or Why Not?
No. For example, the function Array.forEach() in which the function is executed once per array item is not asynchronous even though it takes a function as an argument. It is only functions which resolve at some point in the future that are asynchronous. 
```
Source: https://bytearcher.com/articles/does-taking-a-callback-make-a-function-asynchronous/
```