# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
Every module has an entry point: the object/function/constructor that we get when it's required elsewhere using the require keyword.
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
Both folders are basically the same since they both hold components, but the aesthetic of Vue is that components that will function as pages (routed to like page for navigation) are kept in the /views folder, while reusable components like form fields are kept in the /components folder.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
You can use the v-repeat directive to repeat a template element based on an Array of objects on the ViewModel.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
Template, source, style
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle

```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
router-link
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
That means any component, anywhere in the app can access it (kind of like a database) so long as they hook into it. Component state however, lives within that specific component. As such, it can only be updated within that component and passed down to its children via props.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Your duties will include taking part in daily scrums, writing and developing modules for existing Vue applications, integrating Vue into existing projects, writing code and tests for code, taking part in code review sessions, and using version control software to push and pull code for testing and deployment.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The newly created Vue project has the following folders and files: src : the sources of your project. public : all the content that will be directly put at the root of the web server, without going through Webpack. package.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
style, the class tag
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
computed
```