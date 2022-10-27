Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Collaboration:
* rmo1: helped me figure out how to download Gutenberg pages (including the images) from the site. Also gave me tips on how to improve my good.html
* ianta: clarifying questions about the assignment, and showed me how to add images through CSS instead of HTML
* landberg: gave me suggestions on how to improve my good.html (provided links to sites that might help me, given in readme.md)
* natnail: Gave me advice on my bad and good html
  
Gutenberg.css changes:
* change the font family of captions, h1 to h3, div, table rows and columns 
and paragraphs. As well as text inside the table (table captions, etc.).
* change background colors of all pages to Old Paper Color.
* I filter all images in all pages that contain images to that sepia is at
100% (makes them look more faded and blend better into the background).
* Aligned all elements with .letter class, as well as table rows/columns and
any elements with .contents class so that the text is aligned to the left (originally
center).
* Made the font style of divs, table rows/column, paragraphs as well as the caption
("part 1" in Little women) to be italic.  
* Change the margins of various tables and unique elements (more specifically the elements
from Little women) so that they were more aligned with the other elements (more center,
more towards the left, etc.)

Gutenberg code: 
* all fonts found in gutenberg.css was taken from: https://www.tutorialbrain.com/css_tutorial/css_font_family_list/
* color "Old paper Color" found from: https://www.color-name.com/old-paper.color

Homepage code:
* Creating a top navbar code came from this source: https://www.w3schools.com/howto/howto_js_topnav.asp
* The following links how the source urls of most images (all other images not metion are original):
  * https://danbooru.donmai.us/posts/316966 (link)
  * https://jaejohns.com/how-to-paint-a-galaxy/ (badBG)
  * https://www.netsolutions.com/insights/most-popular-programming-languages/ (programming.png)
  * https://www.hugo.team/blog/one-on-one-meeting-template-questions (badpics/talking.png)
  * https://cindyfriedman.org/office-hours/ (goodpics/talking.png)
* adding shadow to text (provided by landberg): https://fonts.google.com/. 
* Importing custome fonts (provided by landberg):  https://stackoverflow.com/questions/4772906/css-is-it-possible-to-add-a-black-outline-around-each-character-in-text.