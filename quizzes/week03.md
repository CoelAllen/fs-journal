# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
- Abstraction, encapsulation, inheritance and ploymorphism.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
- staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
- Encapsulation is bundling data and methods into classes.  So you have objects that have variables, functions and methods. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
- Single responsibility principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
- The class is like the blueprint to make a house and an instance of a class is the actual house.  the instance is the object that is created from the class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
- It is an object that you use in place of an original object.  But the proxy can change or add functions and variables of the object. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
- The MVC patterns organize your code into discrete chunks that are all responsible for only thing.  This simplifies your code and allows you to change sections individually rather than working on one huge file.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
- The controller is what controls user interactions with your app.  It takes in events from the window and then applies it to the logic of the model.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
- Services contain methods to perform operations with the model. It can add extra steps of functions to the model. 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
- The model is the actual object that holds the values and logic.
```
