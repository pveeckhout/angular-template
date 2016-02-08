# Angular Template

#### credit

I have taken the structure and explanation from [here](https://scotch.io/tutorials/angularjs-best-practices-directory-structure)

I thank ADNAN KUKIC ([@kukicadnan](https://twitter.com/kukicadnan)) for this best practices on AngularJS directory structure.

## main folder

An ideal AngularJS app structure should be scalable and maintainable, we modularize the app into very specific functions to achieve this.
We take advantage of the wonderful AngularJS directives to further compartmentalize our apps.

## index.html

The index.html lives at the root of front-end structure. The index.html file will primarily handle loading in all the libraries and Angular elements.

## Assets Folder

The assets folder is also pretty standard. It will contain all the assets needed for your app that are not related your AngularJS code. There are many great ways to organize this directory but the example here is good enough for most apps.

## App Folder

This is where the meat of your AngularJS app will live. We have two subfolders in here and a couple JavaScript files at the root of the folder.