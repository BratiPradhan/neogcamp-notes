# BOX SIZING: BORDER BOX | CONTENT BOX | PADDING BOX
We use box-sizing property, because older days web design only contains **content-box** as **box-model**, so there comes the box-sizing property


## BORDER BOX:
 - width/height + padding + border = actual visible/rendered width/height of an element's box
 - this is very useful because the it gives the actual width and not cutting out the width/height
 - this is more responsive or fluid, because you don't have to fix padding and border with some extra pixels unlike **content-box
 
 ## CONTENT-BOX
 - width/height =  actual visible/rendered width/height of an element's box
 - the border and padding values moved inside the the element box, cutting out the width/height of the box
 - this we say as the older **box model** 
 - this may be not so good to use 
 - when you have a parent div and inside it you have different width, padding and border of element, then the element box will go outside your parent div
 - this makes it less responsive when you try to fix that with pixels
 - however at some place it may be useful
 
 ### UNIVERSAL BOX SIZING WITH INHERITANCE
 
 html {
 box-sizing: border-box;
 }
 
 *, *:before, *:after{
 box-sizing: inherit  - by using **inherit** we can use padding-box as well as content-box without worying about universal selectors overiding style
 }
