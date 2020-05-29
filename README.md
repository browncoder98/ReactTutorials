# React Tutorials:
> *__Starting your React app :     ``` npm init react-app my-app ```__*

#####   *Some text files consisting of various exercises off "freecodecamp" and "Scrimba". Various comments are given inside each text files for the user's convenience.*

#####   *Multiple links to different blog posts are given as well inside "//" as links to be copied and pasted onto the browser.*
 
######   *Each text files consist of divisions for each projects such as "//App.js:", "//index.html" which saves the time of making different text files for each component of the exercise.*
 
## Hosting React Projects onto Github:

> *__Instead of paying upfront for hosting or even using free services such as Google Firebase, some simple steps to host React via Github. Node.js needs to be up to date and installed for this procedure.__*

* Install the command  ``` "C:\Personal\react\todolist>npm install gh-pages --save-dev " ``` via Command Prompt 

* Create a new repository on Github and name the repository according to one's own desire.
* Go to the "package.json" file for the project.
* Include the following onto the current object displayed
  ```javascript
          "homepage": "https://your-github-user-name.github.io/insert-repo-name-here",
  ```

* Scroll down to the "scripts" properties, edit and add the following code.
     ```javascript
	          "scripts" : {
		          "predeploy": "npm run build",
		           "deploy": "gh-pages -d build",
            			} 
      

* Go to the command prompt and terminate whatever is going on
* Redirect your Command prompt to the location of the file
* Paste the following commands if the terminal looks something like this:

   *  ``` C:\Personal\react\todolist> git remote add origin https://your-github-user-name.github.io/insert-repo-name-here ```

   * ``` C:\Personal\react\todolist> git remote set-url origin https://your-github-user-name.github.io/insert-repo-name-here ```

   * ``` C:\Personal\react\todolist> npm run build ```

   * ``` C:\Personal\react\todolist> npm run deploy ```

* Copy the homepage link onto the browser -  ``` "https://your-github-user-name.github.io/insert-repo-name-here" ```

## For more details visit the links below:
 
#### *FreeCodeCamp: https://www.freecodecamp.org/news/*
#### *Scrimba: https://scrimba.com/*
#### *React.js Documentation: https://reactjs.org/docs/getting-started.html*


