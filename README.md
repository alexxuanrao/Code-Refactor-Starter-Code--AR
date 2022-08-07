# Code-Refactor-Starter-Code--AR
Module 1 Challenge
# Code Refactor Starter Code

# User Story

* AS A marketing agency, I WANT a codebase that follows accessibility standards. SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards
* WHEN I view the source code
* THEN I find semantic HTML elements
I input changed the hero div to section <section class="hero"></section>

* WHEN I view the structure of the HTML elements
* THEN I find that the elements follow a logical structure independent of styling and positioning
I conslidated css repetitive styles and renamed them as new classes in html 

* WHEN I view the image elements
* THEN I find accessible alt attributes 
I added alt to all image search such as <img src="./assets/images/search-engine-optimization.jpg" alt class="float-left" />

* WHEN I view the heading attributes
* THEN they fall in sequential order 
I added id= to the following <div id="search-engine-optimization" class="category"> so the navigation link to respondence scetion 

* WHEN I view the title element
* THEN I find a concise, descriptive title - right nect to the title
I input descriptive title 'marketing agency for your brands' in the <title>Horiseon</title> 
