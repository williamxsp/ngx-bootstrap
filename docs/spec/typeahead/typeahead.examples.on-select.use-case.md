16.17: Typeahead On select example
==================================
**Primary Actor**: User

**Scope**: Ngx-bootstrap DEMO / BS version 3&4

**Goal**: Show user On select functionality

Main success scenario:
----------------------
1. User open Typeahead demo page
2. User click on Selected sub-menu
3. User sees typeahead input and typeahead card with "Model:" text. User sees typeahead card with "Selected option:" text
4. When user starts to type a name of a State from "states" array and there is no matches the drop-down is hidden. The "Model" is filled with inputted data. The "Selected option" is empty
5. When there are any matches then a drop-down with a list of States matches is shown
6. Items in the drop-down are clickable
7. When user clicks on any item in typeahead drop-down, then typeahead container auto-fills with a selected State and "Selected option" is filled with info about selected object: "id", "name" and "region"

Extensions:
-----------
3a. If there is any data, it could be deleted. While deleting data the drop-down with matches is shown

Variations:
-----------
2*. User scrolls to On selected sub-menu
