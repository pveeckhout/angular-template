# App folder

We have two subfolders in here and a couple JavaScript files at the root of the folder. The app.module.js file will handle the setup of your app, load in AngularJS dependencies and so on. The app.route.js file will handle all the routes and the route configuration.

## further advice

#### Modularize the Routes

In the structure above we didn’t do this, but another good practice for very large apps is to separate the routes into separate files. For example you might add a blogRoutes.js file in the /views/blog/ subfolder and there include only the routes relevant to the blog such as /blog/:slug, /blog/:slug/edit, blog/tags:/tags, etc.