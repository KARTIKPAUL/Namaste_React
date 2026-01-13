1. What is NPM ?
Ans : NPM is a package manager.It's the default package manager for Node.js and is used for install,,share and manage JavaScript code.Think of it as the "App Store" for JavaScript developers. It is the default tool used to share, borrow, and manage code packages (libraries) for Node.js projects.

2.What is `Parcel/Webpack`? Why do we need it?
Ans : Parcel and Webpack are JavaScript bundlers(also known as build tools).They take care of project's source files and turn them into the optimized files that browsers can understand and can run efficiently.

3.What is `.parcel-cache`?
Ans : When we use parcel, it analyzes our file(HTML,CSS,JS etc.).Instead of recprocessing everything every time, Parcel stores the result in a folder called parcel cache.

4.What is `npx` ?
Ans: npx mean package executor.NPM is used for install and manege packages, NPX is used to execute(run) them directly.

5.What is difference between `dependencies` vs `devDependencies` ?
Ans: Dependencies are those required for the app to function in production.Other hand devdependencies required only for the development and testing.

6.What is Tree Shaking?
Ans: Tree Shaking is a process of removing the unwanted code that we do not use while developing the applications.

7.What is Hot Module Replacement?
Ans: It means that parcel will keep a track of all the files which we are updating.
There is a File Watching Algorithm (Writen in C++).It keeps track of all the files which are changing realtime and it tells the server to reload.

8.List down your favourite 5 superpowers of Parcel and describe any 3 of them in your own words ?
Ans: 1. Hot Module Replacement(HMR) : Follow question Number 7
     2. Tree Shaking : Follow question number 6
     3. Image Optimization
     4. Https on Dev
     5.Consistancy Hashing Algorithm.


9.What is `.gitignore`? What should we add and not add into it?
Ans : When we have a file listed in .gitignore , Git will not track changes to it, will not add it to be the staging area and will not upload in github.

10.What is the difference between `package.json` and `package-lock.json` ?
Ans: package.json => This file lists the minimal compatible versions our project needs.
     package-lock.json => This files locks down the exact version of every package that was actually installed.

11.Why should we not modify `package-lock.json`?  
Ans : Modifying package.lock.json manually is a bad practice because it defeats the file's entire purpose, guaranteeing consistancy and security.

12.What is `node_modules` ? Is it a good idea to push that on git? 
Ans: node_modules is the folder where NPM actually stores the code for all the libraries(packages) we downloaded.

13.What is the `dist` folder?
Ans : It keeps the files minified for us.This dist folder contains the minimized and optimized version the source code.
     
14.What is `browserlists`?
Ans: Browserlist is a configuration tools that tells our project which web browsers do we need to support.