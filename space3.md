6/3/2023:
we misunderstood what width values were.

treated the style layering so that the base case is from the codepen codebase
and the desktop style changes were a media query when screen size was > 1280px
essentially set an upper bound change and a lower bound change and anything in between (very likely just tablets)
is defaulting to the regular css styling/style sheet.

there was also a missing property that needed to be added to the mobile phone category for the media queries:
needed to add a display: flex property for some reason to make sure that the mobile phone media query displayed
properly for screen sizes of the specified width.

resources in case i need them again:
https://codepen.io/Russell-Villase-or/pen/yLRmEqq

https://docs.google.com/document/d/1Hij2NmstSRQZ0wiqqfw5ZjnAZkTO2v-uftbqxGFrRzo/edit

https://docs.google.com/document/d/1CyNqGmi7d_65oHQNnA6E_8zYHoUOkKLdHyNiLrqn97E/edit
