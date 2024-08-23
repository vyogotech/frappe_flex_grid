# frappe_flex_grid
Fix to allow more than 10 columns for child tables in Frappe

## description

1. Copy the frappe folder to the core frappe application root folder or manually replace grid_row.js and grid.js to the correct folder. 
2.  Run `bench build`

## Changes

1. Move from Bootstrap's grid layout to Flex layout 
2. Remove 10 column validation 

## Known issues/ Nice to have


1. Minor CSS alignments 
