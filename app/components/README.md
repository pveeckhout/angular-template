# Components Folder

The components folder will contain the actual sections for your Angular app. These will be the static views ,directives and services for that specific section of the site (think an admin users section, gallery creation section, etc). Each page should have it’s own subfolder with it’s own controller, services, and HTML files.

Each component here will resemble a mini-MVC application by having a view, controller and potentially services file(s). If the component has multiple related views, it may be a good idea to further separate these files into ‘views’, ‘controllers’, ‘services’ subfolders.

**You could essentially think of the components as multiple mini Angular applications inside of your giant Angular application.**

## further advice
If you are developing a really large application in AngularJS, you will want to go even further and modularize your app. Here are some additional tips on how to accomplish this.

#### Modularize the Header and Footer

A good practice here would be to create a Core subfolder under components, and then a subfolder for the Header and Footer and any additional components that will be shared across many pages.