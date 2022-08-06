# Horiseon
Module 1 Challenge
## Aout the App:
Horiseon is a application for marketing agency where they can access the site for SEO, ORM and SMM. 
## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our site is optimized for search engines
## Acceptance Criteria

GIVEN a webpage that meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## Issue
When user click on Search Engine optimization, it was not navigating to content section on the home page.
### Fix
search-engine-optimization was missing id attribute that was part was Search Engine optimization navigation unorder list. So I added id attribute to over come the navigation issue 
![Link Fixed](../Horiseon/Develop/assets/images/FixedImg/WebscreenFix.png)


## Other improvemant 
### 1 
I saw lot of duplicated code in css style so I grouped the items by class based on common style vaules
![CssStyleScreen code](../Horiseon/Develop/assets/images/FixedImg/CssStyleScreen.png)

### 2 
I added specifies an alternate text for an image
![imgAlt code](../Horiseon/Develop/assets/images/FixedImg/imgAlt.png)

### 3
I added nav tag for section that provide navigation links, either within the current document or to other documents.
![headerNav code](../Horiseon/Develop/assets/images/FixedImg/headerNav.png)

