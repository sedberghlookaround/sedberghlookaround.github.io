Sedbergh & District Lookaround
====================
The 'Lookaround' is a Community Newsletter which serves the population of Sedbergh and the surrounding areas of Cautley, Deepdale, Dent, Frostrow, Firbank, Garsdale, Gawthrop, Howgill, Killington, Middleton & Barbon.  We have a monthly print of between 800 & 1,000 copies.

This is the homepage for the newsletter and it is hosted on github pages.

Please submit suggestions to team members, raise an issue or even make a pull request from a fork.

# How to use

### New Editions
#### PDFs
Upload new editions to './issues'
Name should in the following format

    197 February 2003.pdf
    {Edition Number} {Month} {Year}.pdf

N.B
The last four characters must be the year.  It is this which lets the site group the in year blocks.

PDFs should be optimised for the web.  I recommend [this site.](https://www.wecompress.com/en/)

#### Images
The image used to create a link to the latest edition is found at the following location  './img/current-edition.jpg' Simply replace it to when you upload a new edition.

Extract first page for the website 'cover'.  Print first page to pdf upload here - https://www.ilovepdf.com/pdf_to_jpg

### Copy
The text is largely inside the layout elements.  It should ideally be drawn from datafiles and posts. However, for now suggest text changes to someone happy to edit html.

### Team

Team members and info are in '_config.yml'.
Images are in '/img/team/'.



### Technology Info

#### Template

Forked from Agency theme based on [Agency bootstrap theme.](https://startbootstrap.com/template-overviews/agency/)

#### Content Management - Jekyll

For more details about the templating stack, read the [Jekyll documentation.](http://jekyllrb.com/)

##### Updating Jekyll

Occasionally Jekyll will need updating. Clone or update a version of the site locally.

    git clone git@github.com:sedberghlookaround/sedberghlookaround.github.io.git
    or
    git pull
    
Update via the following command.

    bundle update
    
Commit change and push to githup

    git commit -am "Update Jekyll"
    git push
  
