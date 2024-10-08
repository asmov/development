# asmov / dev / templates

## format

All find-and-replace templating is done using `%{..}%` blocks.  
Template variable and category names are alphanumeric and underscore only in all-caps.  
Template categories and sub-categories use dot-walking.  
There must be at least one category.

Example: `%{SOME_CATEGORY.SOME_VALUE}%`

RegEx: `/%{[A-Z0-9_]+\.[A-Z0-9_]+}%/`

## common template variables

- `%{PROJECT.NAME}%`
- `%{PROJECT.DESCRIPTION}%`
- `%{COPYRIGHT.YEAR}%`