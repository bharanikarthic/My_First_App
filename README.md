# firstApp
 it is for learning purpose of daily basis
# What is JSX
What is jsx

Jsx stands for javascript XML. Jsx allows to html in react. Jsx easier to write code at html in react.
Your  component also can't return multiple element.
<fragment />
< />
<div />

# How react work under hood
react maintained a trees as like html. The html has the dom is like a node then it reflect in screen by using react its create virtual dom it does not affect the screen cause it take a snapshort of virtual dom and then it compare with the actual dom the only updated content will reflect.

# What is package.json

The file package.json is an essential part of a Node.js project. It serves multiple purposes and provides important information and functionality. Here are some reasons why we need a package.json file.

# Project info

Info about the 
name,version, description, author, licence

# dependencies

It includes a section where you define the externallibraries and modules the modules such are the node mod

# scripts

it's used for start the app, test the app and build the app

# package-lock.json
whenever you install any library that is required in your project that library you can find it in the dependencies object autommatically

# dependency version locking

it is necessary to lock versions of dependencies and transitive dependencies such that a build with the same inputs will always resolve the same module versions.this quarntees that everyone working on the project uses the same versions of the dep.

# why so many modules under the node moidules

cause each modules have its own dependencies and each dep will have a chid dep it create a dep tree for runing the react app smoothly without error that's why we seen so many mod in node mod folder

# react app runs

# app setup
the first step is setting up the development by installing the dep

# Component rendering

in react the ui is built using comp.comp are in a tree like struct where each comp can contain the child comp.

# Entry point

index.js this file serves as the starting point of the app and is res for rendering the top level component into dom. When the app is loaded the entry point calls the reactdom.render() fun passing the top level component and target dom element where the app should be rendered

# Key folder and files created by react app

# src/folder for your app code

index.js is for rendering the root component and mount it into the dom app.js these files contains component index.css is for styling purpose.

# public/

index.html is loaded in the dom.Then display the structured.

# node modules/

when you install dependencies using a package manager like npm or Yarn

# package.json

Node.js projects as it helps manage dependencies, track versions, define scripts, provide metadata, and facilitate project initialization. It simplifies the development workflow, promotes collaboration, and ensures consistent environments for different users working on the same project.

# npm install

 First, npm install checks the package.json file in the current directory to determine the dependencies required for the project.
 It checks the versions and dependencies of the installed packages to ensure they meet the requirements specified in package.json.
Once the dependencies are resolved, npm install proceeds to download the packages from the npm registry and store them in the node_modules directory in the root of the project.
 If a package-lock.json file exists (which is automatically generated when dependencies are installed or updated).
