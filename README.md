Confirmit – job interview assignment
====================================
This is an assignment that I solved as part as a job interview with Confirmit.

Description
------------
The assignment consists of creating a HTML/CSS banner that contains three links and a SVG logo. The implementation is based on [this picture](https://github.com/johanna-ux/confirmit-assignment/blob/master/_doc/assignment_files/Menu.psd).

Details of the implementation
-------------------------------
* The project includes the file structure that I usually start with when beginning with a project, even if for example a js folder was not necessary to complete this project. This should not be interpreted like they got there by mistake.
* In both HTML and CSS files I included som extra parts that are not necessary for completing the assignment, but which are illustrative for how I usually think when working with a larger project. This should not be interpreted like they got there by mistake.
* I included accessibility elements like accesibility navigation, ARIA roles and semantisk HTML and declaring the language of the page.
* For SEO I used schema microdata, a descriptive title, a unique description text for each page and semantic HTML. 
* Regarding the design of the elements: I added a shadow for the whole banner, gradient for the background of the banner, shadow for the text and outer glow on hover state. The active link has recived color orange.
* I also added media query for screen sizes that go under 500px, the size of the banner. On these screens I made so that the elements are presented vertically insted of horizontally.
* I used _flexbox_ for layout.
* I chose to include the SVG as an inline URI so it will be cashed by the browser as image. This also makes it work in _evergreen_ browsers. Besides this, it still gives the possibility to controll the SVG through CSS and scripting.
* By Evergreen browser I mean browsers that update to the latest version automatically, in the background, without user interaction. Examples of such browsers are the latest versions of Chrome, Firefox, Internet Explorer, and Safari. 
* I used svgo module for npm to optimize further the SVG. This made a reduction of 24.6%.
* I used SASS for processing the CSS. The SASS files are included in the repository.
* I used BEM and SMACS for organizing the CSS.
* I used BrowserStack to test for IE11 support. The result can be seen here: [Image of the page view in IE11](https://www.browserstack.com/screenshots/28db36938794cf66abc473fcc39ec388a88c68f8) 
* The CSS3 elemnts that I used are supported by evergreen browsers (I checked with caniused.com).
* I included a favicon to make the page look like a more finalized project.
* Dead links do not show well when validating. In consequence, I made a page for each link in the navigation, besides Home.

