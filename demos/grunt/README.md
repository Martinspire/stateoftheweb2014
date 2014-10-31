# Grunt demo

This is a simple demo which shows how grunt works and what it can do.

# What?

1. Open a terminal here
2. Run command "npm install -g grunt-cli"
3. Run command "npm install"
4. Look at the files inside this folder. Notice there is no style.css but there is a style.scss. Open it to see whats inside.
5. Run command "grunt"
6. Notice there is a style.css file inside this folder.

Look at the config on how it is implemented. We have downloaded the Grunt-Sass module and converted the SASS file to a CSS file with minification and resolving of variables.

One thing to note: most projects are using Grunt-Contrib-Sass instead of Grunt-SASS. The contrib version uses Ruby and the SASS gem to compile the SCSS file. This Ruby gem is newer and contains more features than the Grunt-Sass variant. So why use that? Well, it is made with C++ and based on the LibSass project which is node-based. It is currently up par with Sass 3.2 (instead of 3.4 the latest), but works for most projects just as nice. Bonus is that your project doesn't require Ruby or the Gem so its faster to install and use. 