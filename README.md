# Bootstrap-Responsive
Figma to Html (using Bootstrap Responsive)

------------------------
* Bootstrap 4 breakpoints is applied, link below:
https://getbootstrap.com/docs/4.6/layout/overview/
* Create a new CSS file named media.css and copy-paste the media queries and mixins in it.
* Put the link of Media Query CSS (media.css) file at the end of links in index.html file.
* Open the index.html file in Mozilla Firefox and press ctr+shift+m to get the Responsive view of the web page
* Comment the line below in the header part and Use font awesome icon (bar icon) instead of the "<span>"
  
  (span class="navbar-toggler-icon") (/span)
* Write CSS (at first in the extra small device @media) for the bar icon <i> in the media query file.
* overflow-x:hidden; is written in the Common CSS ( to Remove the scroll bar bottom of the page)
* Also, add "box-sizing: border-box;" in the Common CSS.
* Now, inspect the page and modify the CSS classes (by overwriting them in the media query file) according to the screen size (inside @media)
* Header Part -> To bring the Contact Button in the middle, we need to add the lines below:

  text-align: center;
  display: block;
