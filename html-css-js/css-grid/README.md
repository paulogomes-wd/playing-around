## Course
CSS Grid Tutorial

## Source
Youtube

## Author
The Net Ninja (Channel)

### Summary
* My humble opinion: CSS Grid is simply awesome and very very useful (specially grid areas)

* My perspective: CSS Grid is a way of slicing the screen into blocks throw the definition of columns and rows

* To "say" to the browser that we are using the CSS Grid system we "just" need to do --> " container-selector { display: grid; }"

* We can define columns through the following commands (note that X, Y and Z can be the same value):
--> grid-template-columns: X% Y% Z%; 
--> grid-template-columns: Xfr Yfr Zfr; /* Where "fr" means a "fraction" of the screen */
--> grid-template-columns: repeat(N, Xfr); /* Define N columns with the "size" of Xfr */

* Grid Rows
--> To force the grid to use a "fixed" size for the row we can use the property "grid-auto-rows: Xpx;"
--> But if you want more flexibility for the size of the rows you can use the "minmax" function "grid-auto-rows: minmax(Xpx, auto);"
--> Analogously to the "grid-template-columns" property we can use the "grid-template-rows" property to define rows for the grid (using the same "logic" as shown in the "columns section")

* Inserting "gaps" through the grid elements
--> grid-column-gap: Xpx;
--> grid-row-gap: Xpx;
--> We can replace the two properties above for the *** "grid-gap: Xpx" ***

* Grid Lines
--> My perspective: Used to define (statically) the exact location of an element inside the grid

* Nesting grids
--> The same "logic" used to create the parent grid and so one

* The span "behavior"
--> grid-column: span X; /* It means: take the grid from its default start point plus X column(s)*/

* Aligning and Justifying Items
--> "align-items" or "align-self" are used to orgarnize vertically and "justify-items" or "justify-self" are used to organize horizontally

* Grid Areas
--> "grid-area: area-alias" allows us to define grid areas and define its positions so we can use it at the "grid-template-areas" property
* grid-template-areas: " ............. " (It is basically used as a "bitmap")

* The lessons 9 and 10 give greats examples of implementing/using grid areas (amazing course)