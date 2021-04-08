# Apache Theme

The Apache Theme included here consists two types of html files.

1. Page templates.
  There should be one template for each page type.
3. HTML fragments.
  There are fragments for different common parts of an html file.
  
## Page Templates

1. base.html - there is only one page type.

Change the base page as necessary and add new page types as required.

## HTML Fragments

These common parts of the html file are discussed in the order they are included in pages.

1. meta.html - consists of OpenGraph meta tags for the website. Filled from [pelicanconf.py](../../../pelicanconf.py).
2. styles.html - consists of Apache feather Favicon tags, and Bootstrap and GitHub Markdown Stylesheets. See [Web Developer](../../../DEVELOPER.md).
3. styles.css - consists of custom site CSS overrides. Edit as needed.
4. menu.html - consists of site branding and the top menubar. Edit as needed.
5. footer.html - consists of the page footer including trademarks, licensing, and copyright.
6. scripts.html - consists of Apachecon, JQuery, Bootstrap, and Popper javascript to be included on every page, loaded last. See [Web Developer](../../../DEVELOPER.md).

Each of the above files should be edited as needed for the deployed website.