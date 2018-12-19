!> ***Feature List*** enables users to quickly have an overview of content.

# Standard implementation
It's a list, without links. Each element of the list shows a title and description.

![Feature List](featureList.png) 

This _list_ will include a:
 - Static picture for the entire list or a picture for each element
 - A title
 - A description
 
## Mobile
The basic implementation for small screens includes a horizontal scrolling if it has more than one element in the list

## Tablet
## Desktop


## CSS implementation
```code
 .foo {
    -webkit-overflow-scrolling: touch; // has to be included
 }
```