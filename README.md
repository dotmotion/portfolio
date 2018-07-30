# Project Notes

##Remember
-don't use () when calling a function on an EventListener

-when transforming, the property 'translate' needs a comma between the X and Y values

##Research

-understand the delay (SCSS):

//Delay nav items by 0.1s
@for $x from 1 through 3 {
.nav-item:nth-child(#{$x}) {
transition-delay: $x \* 0.1s;
}
}

-@content within @mixins
