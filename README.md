# incoming-links
Confluence user macro that displays a list of pages that link to the current page.

The macro is user configurable: 
- show title and border (the default),
- choose your own title
- show link to spaces (the default),
- shorten page titles in the list to 100 characters
- sort the list alphabetically (the default)


Possible enhancements:
- Currently the macro does not display incoming links on the target (current) page that are placed in comments on the source page (the page linking to the target page)
- The configuration pane is not multilanguage (yet) and there is no preview shown.



Tested on Confluence Server 7.13.x

More on user macros: https://confluence.atlassian.com/conf713/writing-user-macros-1077914347.html

----

<img width="493" alt="image" src="https://github.com/pdussart/incoming-links/assets/15105142/a1b4a748-6b5a-4480-abc6-1caeb641eb1d">

----

Bubble sort code reused from https://github.com/unidwell/confluence-include-child-pages-macro
