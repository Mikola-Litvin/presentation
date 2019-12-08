### CSS Grid Layout

Hi, gays!

My name is Nikolai and now I am going to tell you about CSS Grid Layout.
As World Wide Web Consortium says, Grid Layout is a new layout model
for CSS that has powerful abilities to control the sizing and positioning of boxes and their contents. 
Unlike Flexible Box Layout, which is single-axis–oriented, Grid Layout is optimized for 2-dimensional layouts: 
those in which alignment of content is desired in both dimensions.

The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design 
web pages without having to use floats and positioning.

## Browser Support

The grid properties are supported in all modern browsers.

## Grid Elements

Now let’s talk about a concept of Grid Layout.

Grid Layout consists of a parent element, which includes one or more child elements.
The parent grid element is called a container. The child elements are called grid items.

## Display property

An HTML element becomes a grid container when its display property is set to grid or inline-grid.
All direct children of the grid container automatically become grid items.

## Grid Layout Concepts

Other Grid Layout concepts are grid columns, grid rows, grid gaps, grid cells, grid areas and grid lines.

## Grid Columns

The grid columns are vertical lines of grid items.

## Grid Rows

The grid rows are horizontal lines of grid items.

## Grid Gaps

The grid gaps are spaces between each column or row.
We can adjust the gap size by using one of the following properties: grid-column-gap, grid-row-gap, grid-gap.

## Grid cell

The grid cell is the intersection of a grid row and a grid column. 
It is the smallest unit of the grid that can be referenced when positioning grid items.

## Grid area

The grid area is the logical space used to lay out one or more grid items. 
The grid area consists of one or more adjacent grid cells.

## Grid Lines

Now it needs to say several words about grid lines.

The lines between grid columns are called column lines.
The lines between grid rows are called row lines.
 
Grid lines can be referred to by numerical index, or by an author-specified name. 
A grid item references the grid lines to determine its position 
within the grid using the grid-placement properties.

## Grid Container’s properties

Now let’s talk about grid elements’ properties and begin with the main grid element 
which is called a container. As mentioned above, an HTML element becomes a grid container 
when its display property is set to grid or inline-grid.
The grid container has several CSS properties.

One of them is the __grid-template-columns property.
It defines the number of columns in grid layout and can define the width of each column.

## Grid-template-rows property

This property defines the height of each row.

## Justify-content property

The justify-content property allows to align the whole grid inside the container.
The grid's total width has to be less than the container's width for the justify-content property to have any effect.
This property has following values: start, end, center, space-evenly, space-between and space-around.

## Align-content property

The align-content property allows to vertically align the whole grid inside the container.
The grid's total height has to be less than the container's height for the align-content property to have any effect.
This property has the same values like the justify-content property.

## Grid Item’s properties

That is all about container’s properties. Now let’s talk about grid item’s properties and begin with the __grid-column property.
This property defines on which column to place an item. With this property, we define where the item will start, and where the item will end.
To place an item, we can refer to line numbers, or use the keyword "span" to define how many columns the item will span.
The grid-column property is a shorthand property for the grid-column-start and the grid-column-end properties.

## Grid-row property

This property defines on which row to place an item.
The grid-row property is a shorthand property for the grid-row-start and the grid-row-end properties.
To place an item, we can refer to line numbers, or use the keyword "span" to define how many rows the item will span.

## Grid-area Property

This property can be used as a shorthand property for the grid-row-start, grid-column-start, grid-row-end and the grid-column-end properties.

## Naming Grid Items
The grid-area property can also be used to assign names to grid items.
Named grid items can be referred to by the grid-template-areas property of the grid container.

## The Order of the Items
The Grid Layout allows us to position the items anywhere we like.
The first item in the HTML code does not have to appear as the first item in the grid.
We can re-arrange the order for certain screen sizes, by using media queries.

## That is it. Thank you for your attention

