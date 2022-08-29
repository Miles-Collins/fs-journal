# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
V-Model. When the user types in the input, value gets updated to match the value in input.
When you update value, the input element's content updates to match value.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application 
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
It is no surprise that SPAs consume less bandwidth since they only load web pages once. Besides that, they can also do well in areas with a slow internet connection. Hence, it is convenient for everyone to use, regardless of internet speed.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
The mounted() hook is the most commonly used lifecycle hook in Vue. Vue calls the mounted() hook when your component is added to the DOM. It is most often used to send an HTTP request to fetch data that the component will then render.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
For v-model to work, it expects the element or component in question to receive a prop (default is value ) and also emit an event (default is input ). Vue uses this expansion to handle textarea , select , and some other input types.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
v-on. This directive requires an argument. This directive requires the value to be a Function or a statement.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
The directive v-if is used to conditionally render a block. The block will only be rendered if the directive's expression returns a truthy value.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
If we use v-for it will show all those items based on their index. VueJs doesn't keep track of all those elements. Whenever any changes are made in the items the VueJs will just replaces the positions in dom according to the indexes of items in an array
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Slot is a placeholder inside a web component that you can fill with your own markup, which lets you create separate DOM trees and present them together.
```