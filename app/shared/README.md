# Shared Folder

The shared folder will contain the individual features that your app will have. These features will ideally be directives that you will want to reuse on multiple pages.

Features such as article posts, user comments, sliders, and others should be crafted as AngularJS Directives. Each component here should have it’s own subfolder that contains the directive JavaScript file and the template HTML file.

In some instances, a directive may have it’s own services JavaScript file, and in the case that it does it should also go into this subfolder.

This allows us to have definitive components for our site so that a slider will be a slider across the site. You would probably want to build it so that you could pass in options to extend it.