# About
This is a template for your extension to have a page to then add it on turbowarp or penguinmod, or any scratch mod where you can upload or use custom extensions.
# What can you edit
> What can you edit if you are making an extension page with [Github Pages](https://pages.github.com/) for the [GGJB-site-extensions Organization](https://github.com/GGJB-Site-extensions/)?

if You are making an extension page with this template, you can edit this part under this text.
``` html
<img src="image.png" alt="extension banner">
  <h1>about {EXTENSION NAME HERE}</h1>
  <p>{EXTENSION NAME HERE} is made to {continue here !}</p>
```
1. here, i will guide you through this block of html.
``` html
<img src="image.png" alt="extension banner">
```
as you can see, when you run it, it will show your extension banner. in this case, "image.png" is your extension banner. you can swap the example banner with your extension banner. it needs to be 601x370 in size(not in data) and needs to have the same name (image.png).

2. 1 down, 2 more to go.
``` html
<h1>about {EXTENSION NAME HERE}</h1>
```
this is the header for our index page. AKA `index.html`. you can swap `{EXTENSION NAME HERE}` with your extension's name.

3. 2 down, and the last one to go.
``` html
<p>{EXTENSION NAME HERE} is made to {continue here !}</p>
```
`{EXTENSION NAME HERE}` is the same with number 2 in 'you can swap `{EXTENSION NAME HERE}` with your extension's name.'. and with `{Continue here !}`, you continue the description about your extension.

4.(This readme was updated since i added a extension folder) and now we got the Extension folder. inside this folder is a file called ".gitignore". .gitignore is a file for git to ignore files. inside Extension, you need to add your extension. it needs to be a JS file (.js) since Javascript(JS) works on the web and extensions on any scratch mod(and vanilla scratch) is made with javascript(JS). if its not a .js file, your extension sadly won't run :(
