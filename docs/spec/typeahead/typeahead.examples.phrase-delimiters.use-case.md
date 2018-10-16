16.10: Typeahead Phrase delimiters example
====================================
**Primary Actor**: User

**Scope**: Ngx-bootstrap DEMO / BS version 3&4

**Goal**: Show user Phrase delimiters functionality

Main success scenario:
----------------------
1. User open Typeahead demo page
2. User click on Phrase delimiters sub-menu
3. User sees typeahead input and typeahead card with "Model:" text
4. User is able to use "&" and "," to delimit words
5. When user starts to type a name of a State from "states" array and when uses "&" or "," to delimit words and there is no matches the drop-down is hidden. The "Model" is filled with inputted data
6. When there are any matches then a drop-down with a list of States matches is shown
7. Items in the drop-down are clickable
8. Items in the drop-down are clickable. Click on any item auto-fills the "Model" with a selected State

Extensions:
-----------
3a. If there is any data, it could be deleted. While deleting data the drop-down with matches is shown

Variations:
-----------
2*. User scrolls to Phrase delimiters sub-menu
