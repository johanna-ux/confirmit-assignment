Confirmit – job interview assignment
====================================
This is an assignment that I solved as part as a jobb interview with Confirmit.

Description
------------
The assignment consists of creating a HTML/CSS banner that contains three links and a svg logo. The implementation should be based on [this picture](https://github.com/johanna-ux/confirmit-assignment/blob/master/_doc/assignment_files/Menu.psd).

Details of the implementation
-------------------------------
* I included a favicon. It makes the page look like a more finalized project.
* Dead links do not show well when validating. This is way I made a page for each link in the navigation, besides Home.
* I also included accessibility elements like accesibility navigation, ARIA roles and semantisk HTML and declaring the language of the page.
* For SEO I used schema microdata, a descriptive title, a unique description text for each page and semantic HTML. 
* Regarding the design of the elements: I added a shadow for the whole banner, gradient for the background of the banner, shadow for the text and outer glow when on hover state. The current link have recived an orange color.
* I also added a media query for screen sizes that go under 500px, the size of the banner. On these screens I alo made so that the elements are presented vertically insted of orizontally.
* I used flexbox for layout.
* I chose to include the SVG as an inline URI so it can be cashed as image and work in all major browsers. Besides this still gives the possibility to controll the svg through css and scripting.
* I used svgo to optimize further the svg. This made a reduction of 24.6%.
* I used SASS for processing the CSS
* I used BEM and SMACS for organizing the CSS.
* I used BrowserStack to test for IE11 support. The result can be seen here: [Image of the page view in IE11](https://www.browserstack.com/screenshots/28db36938794cf66abc473fcc39ec388a88c68f8) 
* By Evergreen browser I mean browsers that update to the latest version automatically, in the background, without user interaction. Examples of such browsers are the latest versions of Chrome, Firefox, Internet Explorer, and Safari. 
* The CSS3 elemnts that I used are supported by evergreen browsers (I checked with caniused.com).

