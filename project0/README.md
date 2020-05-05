# Project 0

Web Programming with Python and JavaScript

For Project 0, I chose to create a website about a hobby of mine: birding (birdwatching) in the time of COVID-19. The four pages and accompanying stylesheets are as follows:

index.html - Home page with an intro and photos, content layout using a table, with responsive @media query to remove certain cells for mobile or other devices to avoid crowding on a small screen. The top navbar to navigate between pages, I created using Bootstrap's grid model with columns.

yardlist.html - A page with an ordered list, numbering the bird species I've seen/heard from my yard (45). I  applied :hover selectors to highlight the scientific names on mouseover of any species through a combination of interspersed span tags with various conditional .classes to achieve my desired results. I also used the ::before pseudoelement to make labeling Orders and Families easier. Upon reaching the bottom of the page, I used the #id tag to link viewers back to the top navbar.

photos.html - A page with more detailed metadata about some high quality photos, content laid out in a table, with the :hover selector applied, and links to open in a new tab via the thumbnails, sending viewers to an online photo database where the high res versions are stored. I also used the Bootstrap component alert here as a notification line for most recent photo upload.

hotspots.html - A page with an unordered list of top birding spots, alphabetized. As a user friendly search function, I used the Bootstrap flexbox grid to link to #id tags by letter throughout the page.

birdstyle.css - This is my base stylesheet across the website. It encompasses attributes I want to define site-wide, including #id tags that are ubiquitous across all pages, various responsive @media queries, a great number of selectors including descendants and children (>), and lots of properties.

buttons.scss - This is my SASS stylesheet where I define all selectors and properties for buttons. Any page with buttons has this stylesheet (translated to a .css file) applied. Within it, I use inheritance (%message) to apply the same attributes to different .classes of button. I also use nesting to apply some attributes to certain descendants.

table.scss - This is my SASS stylesheet where I define all selectors and properties for tables. Any page with tables has this stylesheet (translated to a .css file) applied. Within it, I use a $variable to indicate a desired element for all tables. I also use some significant nesting to efficiently tweak the descendants of two different .classes of table.

images folder - All .png photo thumbnails are stored here.
