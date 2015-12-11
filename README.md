# Serious Eats Thanksgiving Promo

## Workflow:
 - I started by drawing some rough wireframes of the promo image to get an idea of how the DOM elements would fit together.
 - To plan the general dimensions of the dom elements, I used the Image Tool Chrome extension to measure how far apart
   things were in the example jpg.
 - To find the right typeface and colors to use, I dug into a few pages on Serious Eats with the Chrome dev tools to look
   at the styling of relevant DOM elements; I was able to find the name of the typeface and the red-orange, gold, and grey
   colors used across most of Serious Eats.
 - At this point I found a copy of the Brandon Grotesque font, from which I generated a webfont kit with FontSquirrel.
 - Next, I wrote elements I thought I'd need into index.html and styled them to get the dimensions mostly right - I
   ignored the background image initially because I wanted to get the DOM elements fitting together the way I wanted.
 - When I was happy enough with the layout, I took Image Tool measurements from the provided jpg and the larger background
   image and determined that it needed to be scaled to about 4/9 of its original size; from there I estimated and adjusted
   the wrapper div's background-position attribute to get it positioned correctly.
 - At this point I went back to to Serious Eats and examined some of the elements that matched the "GO" rectangle, and
   used the same transition styles under its hover pseudo selector
   
## Issues:
 - I had some issues lining up the text that I think were ultimately due to Chrome and Firefox not playing nicely with the
   display on my MacBook - I tried playing with some Chrome settings to see if I could get text to come out sharper and
   also tried using Chrome Canary, but no matter what I did it always looked sharper in Safari.
 
 
## Testing:
 - Since I'm using a gh-pages branch, I just navigated to it on Chrome, Firefox, Safari, and IE and confirmed it looked
   like it was supposed to.
  
