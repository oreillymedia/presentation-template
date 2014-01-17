# Atlas presentation template

This is a template for a presentation in Atlas.  

## Getting the template into Atlas

In this pre-release version of Atlas, the first step in using the template is to get a fresh copy of it into your GitHub account.  To do this, you'll need to clone the repository to your local machine, like this:

```
$ git clone --shallow https://github.com/oreillymedia/presentation-template.git <your presentation name>
````

(Be sure to use the "--shallow" option so that you don't get the version history.)  Once you download the template, you should create a new project on GitHub, and then add a remote on your local machine to your new presentation.  For example:

```
$ git remote add github git@github.com:aliginedleft/scatteredtoscatterplot.git
$ git push gihub master
```

Once you've pushed the new repo up, you can open it in Atlas.

## Working in Atlas

Every "slide" in Atlas must be wrapped in a "chapter" section.  You can organize your slides by putting each one in it's own file, or putting multipl "chapter" sections together in a single file.  Each slide can can contain any kind of content, such as:

* plain text
* lists
* tables
* hyperlinks
* images
 
You can also use the "Insert Media" button to insert the HTML markup for:
* YouTube or Vimeo videos
* JSBins
* Google form widgets (these are a simple way to have an interactive poll or form for your viewers)
* Arbitratray iframes

The "sample.html" file provides some ideas to try.

## Create a title page

To create a title page, edit the "titlepage.html" file.  This file will automatically be placed at the start of your presentation.

## Creating an index page

Edit the file "index.html" to create a landing page that describes the presentation.  Unlike the other slides in this file, there are no default styles or layont applied to this file, so you can pretty much design it how you like.  We recommend you include:

* A description of the presentation
* A brief bio and photograph
* A brief list of topics covered in the talk

## Viewing the site on your local machine

