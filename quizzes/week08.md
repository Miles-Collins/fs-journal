# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
All npm packages contain a file, usually in the project root, called package. json - this file holds various metadata relevant to the project. This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
As you create more complex Node.js projects, managing your metadata and dependencies with the package.json file will provide you with more predictable builds, since all external dependencies are kept the same. The file will keep track of this information automatically; while you may change the file directly to update your project’s metadata, you will seldom need to interact with it directly to manage modules.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Connection String
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can view logs with the Heroku CLI, the dashboard, your logging add-on, or in your log drain.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Here's a quick guide on how to update an app that you've already deployed.
Clone the repository from GitHub to your local device: git clone <YOUR HTTPS URL FROM GITHUB>
Make your changes, and commit them to GitHub: ...
Login to your Heroku account: ...
Set remote for your project: ...
Push to Heroku master to deploy updates:
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Version control branching allows teams to develop and deploy software. But to effectively manage projects with multiple developers and releases, you need a branching strategy. This organizes your branches and development resources, allowing you to release on time.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code reviews should happen after automated checks (tests, style, other CI) have completed successfully, but before the code merges to the repository's mainline branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Git Merge is a way of putting back two previously branched lines of development together. When one branch (source) is merged with another branch (destination), all the changes made to the source branch are integrated into the destination branch. Such integration creates a new commit provided the modifications don’t overlap.

The branch merge, usually, takes two commit pointers (branch tips) to identify a common base commit. And when Git identifies a common base commit between the two commit pointers, it creates a new “merge commit”.
```