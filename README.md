# Code Refactor Homework

This week we were given an application with code that needed cleaning up (or refactoring). There was quite a bit of looking over both of the files and seeing how I could help improve it  

## Semantic Structure
One of the first things needed was to apply semantic structure to the application so that it was easier to understand what everything was. For instance, the heading was using a < div > tag with an id of "heading", when it could have simply been assigned a < heading > tag.

## Consolidation
Next was using these semantic tags to consolidate the CSS file. An example was that all three of the section articles were given the same individual CSS instructions. The same thing could be accomplished by grouping them all together in one element in CSS.

## Additional Cleaning Up
There were some additional items that needed cleaning up. The cover picture was inserted inside the CSS file instead of the HTML file. The navigation bar wasnt fully working. The "Search Engine Optimization" tag wasnt going to the coresponding article because the article was missing the id tag, which was corrected.