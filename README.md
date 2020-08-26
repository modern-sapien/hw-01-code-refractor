# hw-01-code-refractor Read Me

![This is a screenshot of the home page](assets\images\horiseon_screen.png "This is a screenshot of the homepage.")

* [Assignment](#introduction)
* [CSS](#css)
* [HTML](#html)
* [Git Repo](#gitrep)

## INTRODUCTION
 This was my first homework assignment within the GT FT bootcamp. The assignment was to refractor code for a given HTML & CSS document to better conform to CSS & HTML best practices, increase adherence to accessibility & host within a Github Repo while pushing commits to the project throughout the work.

 After reviewing the original & inspecting the elements & images I noticed a few major issues. This project was aimed helping familiarizing me further with HTML & CSS interactions & how to improve code clarity & web experience of users of projects I create.

Noticeable upon visual inspection of webpage

* The title in the <head> was, "website."
* Multiple sections of the webpage had different background colors, one of which did not meet accessibility guidelines.
* The nav bar had a dead internal link
* The color differential in SEO in Horiseon was very hard to view.
* The was the p element was set to 12px instead which made the text hard to read. 
* There were no alt tags for any of the images

 ## CSS
* The hero class actually had a background image embedded into it. I resolved this by linking the image into CSS and providing an alt tag.
* The benefits classes were redundant as there were three tags for every class, I created a new class "benefit-sec" and replaced all of the individual classes of -lead,-brand, & -cost with "benefit-sec.
* I repeated this step for the individual classes contained within the main content of the webpage. .search-enginge optimization, online-reputation-management & social-media-marketing & their 9 subsequent class selectors & created "main-sec" & reduced that amount of needless code drastically.
* Increased the font-size to 18px
* I changed all of the background colors in the CSS.html document to #0072bb, which greatly increased contrast & improved consistent throughout the page
* I also changed the SEO in Horiseon on the nav bar to a black font & made it capital, so that it pops more on a webpage.

## HTML
* I linked the first main class's content as an id that connects to the "#search-engine-optimization" href in the nav bar.
* I replaced the main divs with semantic HTML elements.
* I embedded an image within the <figure> element, and included an alt text.
* I created alt texts for all images.


 ## GITREP
In order to host this assignment, I created a repo within my githhub titled, "hw-01-code-refractor," that I cloned into a homework folder in my GT folder on my desktop. Throughout the process as I made changes to save or updated the repository, I would issue commits & pushes as appropriate.