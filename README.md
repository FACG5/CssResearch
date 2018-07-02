# CSS With BEM
BEM (stands for Block-Element-Modifier) 
Is a naming convention standard for CSS class names.
useful in writing CSS that is easier to read, understand, and scale.
---
# Why BEM
benefits:
-communicates purpose or function
-communicates component structure
-sets a consistent low-level of specificity for styling selectors

# How It Works
includes up to three parts:

-Block: The outermost parent element of the component is defined as the block.
-Element: Inside of the component may be one or more children called elements.
-Modifier: Either a block or element may have a variation signified by a modifier.
If all three are used in a name it would look something like this

                    [block]__[element]--[modifier]--


---
/* Block component */
.btn {}

/* Element that depends upon the block */ 
.btn__price {}

/* Modifier that changes the style of the block */
.btn--orange {} 
.btn--big {}
---
