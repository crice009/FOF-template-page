# FOF-template-page
A simple website template, for anyone (but especially students in MakeHaven's [Foundations of Fabrication](https://sites.google.com/makehaven.org/foundations-of-fabrication/home) class).

## The files that are here:
There are several files and folders here: 

    root-master (folder)
    |
    |---  img (folder)
    |     |  site-wide-example-img.png
    |
    |---  projects (folder)
    |     |---  u0-0 (folder)
    |     |     |---  files (folder)
    |     |     |     |  hello-world.txt
    |     |     |
    |     |     |---  img (folder)
    |     |     |     |  example-img.png
    |     |     |
    |     |     |  index.html
    |     |     |  unit-style.css
    |     |
    |     |---  u1-1 (folder)
    |     |     |---  files (folder)
    |     |     |     |  hello-world.txt
    |     |     |
    |     |     |---  img (folder)
    |     |     |     |  example-img.png
    |     |     |
    |     |     |  index.html
    |     |     |  unit-style.css
    |     |
    |     |  index.html
    |
    |     |---  styles (folder)
    |     |     |  main-styles.css
    |     |     |  mh-icon.png
    |
    |  about-me.html
    |  index.html
    |  license
    |  README.md

## Some commentary of the files & folders above ^

### The root index.html file 
    This is the landing/ home page of this simple website. It has several things linked, and makes use of several assets as examples of this use. [Keep in mind: Any time a web browser is directed to a folder on a server, it will always look for the file called 'index.html' and display that on the browser. That is why the name is used here, and so common among the HTML files used across the whole file tree.]

### The about-me.html file
    This is the well-named 'about me' page for the website. Because it's a second HTML file in the same folder as the landing/ home page, it needs a different file name, and will only be reachable by a direct link that identifies the filename.

### The 'styles' folder
    This contains the shared visual assets every page on the site uses. This includes the main-styles.css file that controls the structure of the pages, and some of the always-available styles for things like monospaced code text styling. The faveicon is also stored in this folder, and it is currently set as the 'mh-icon.png' file. 

### The 'img' folder (that only has the root folder as a parent)
    This folder is intended to store images that will be used on the landing/ home page and the about-me page. The folder could also be considered a central place to store images that will be commonly used across the whole website.

### The 'projects' folder, and index.html directly within
    The projects folder is intended to keep weekly projects organized. It was implemented to contain a collection of weekly project folders, so they can (hopefully) stay organized and in the same folder-level. The index.html file located in this folder is the page intended to be used for navigation to each of the weekly projects. 

### The 'u0-0' folder 
    This is the folder that should be the bare-bones template for each weekly project. Within the folder should be all the tools needed to implement a new project page, with as little extra work as possible. This includes 1) a folder for holding the project's images, 2) a folder for holding the project's design files, 3) an index.html file that will actually be the main webpage for the project, and 4) a unit-style.css file where any CSS styling that may be specific to just that week's page could be isolated. All of this, and the entire u0-0 folder is not going to be linked to by the website. The files and folders are just stored here so they can be copy/pasted to make new project pages. 

### The 'u1-1' folder
    This is the *first real* project folder. It's got all the same things as the u0-0 folder, but it is actually linked to by the project navigation page (in the projeccts folder). Importantly, this folder is a sybling to the u0-0 folder, so all the relative links will work exactly the same - this means that when you copy/paste the u0-0 folder to make the next project all the relative links will just work. In this folder, you should add files and edit everything as necessary to communicte your work on the project.