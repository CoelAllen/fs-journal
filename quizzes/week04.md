# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
- Synchronous code is top-down.  Only one function can run at a time. While async code runs parallel across several controllers and services.  This allow separate functions to advance without waiting for others to complete.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
- An event listener notes and changes and does an action if there is a change.  We used appState listeners so if the appState changed, the template would be redrawn.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
- Open-closed principle.  This means a class can be extended and used without users being able to modify it. 
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
- It is a function that is passed into another function as an argument.  Like when a function in a controller calls back to a service function.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
- A promise is a way to wrap a function and control its functionality.  Using Try/Catch we wrapped functions so if their call was rejected, rather than continuing with undefined data, they would stop and throw an error.  Under the Catch we used console.error and pop.error to show the error in the function.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
- GET POST PUT
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
- Application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
- Services
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
- It allows you to control what information and functions are accessible to the user of your application.  
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
- 200, and it is a glorious number!!
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
- It is an internal server error. It seems to be if you make a typo or send a wrong parameter in your code.
```