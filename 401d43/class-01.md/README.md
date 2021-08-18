# Readings: Node Ecosystem, TDD, CI/CD
------------------------------------------

### Review, Research, and Discussion

1. Describe (in plain English) what Array.map() does

  Array.map() loops through an existing array and performs a function on each element inside the array. It then returns a new array, populated with the results of the function.

2. Describe (in plain English) what Array.reduce() does

  Array.reduce() loops through an existing array, and performs a user-supplied function on each element of the array. It passes the result of this function on to the next element in the array. At the end of the function it will return one value, representing the cumulative result of the function on the array.

3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
  - With normal Promise .then() syntax

    superagent.get(`http://www.someAPI.com/giveMeStuff`)
      .then( result => {
        console.log(result)
      })

  - Again with async / await syntax

    async function getStuff () {
      let results = await superagent.get(`http://www.someAPI.com/giveMeStuff`)
      console.log(results)
    }

4. Explain promises as though you were mentoring a Code 301 level student

  A promis is exactly what it sounds like. It is a promise from another function or service that it will return some data to you at some point in the future. A promis is basically a function saying 'Let me look in to that and call you back later'.

5. Are all callback functions considered to be Asynchronous? Why or Why Not?

  Not all callbacks are asynchronous. Callbacks are just regular functions that can be executed synchronously (in-order) or asynchronously (out-of-order). It depends on the specific callback function itself.
  

