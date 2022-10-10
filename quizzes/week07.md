# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
- There is style and class binding.  Style binding links your css file to certain elements of your Vue object.  Class binding links elements to certain class values.  For instance you can bind a class to be active when the variable is true and inactive when it is false.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
- Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
- You can reuse components, they use less processing and they can be easier to develop.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
- OnMounted loads the data called in the functions after the components have been mounted to the page.  Basically run these functions after the components have been loaded to the DOM.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
- It links an action or input on your DOM to a template in a component.  This is so you can add different info to the same template rendering several versions of the component;s template with different information.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
- Calling a specific function with an action.  The one I used the most was @click.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
- V-if and v-else render elements with conditionals similar to an if statement.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
- The key attribute is to tell which reference Vue should look for to uniquely identify which item to render.  
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
- The slot element is used as a placeholder in your HTML.  You can then us it to pass down template from one component to another.
```