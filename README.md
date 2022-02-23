# Challenge Module 01 Layout

This was a fun one! I had to copy the interface of a well known tv platform.

## Final result
You can visit website [here](https://01-layout-challenge-dmak2daq4-ramonrp.vercel.app/)!

## Stack

I only use html and plain CSS for this challenge.

## Learnings and explanation

### Desktop First Approach

I follow a desktop first approach.
I use in total 3 breakpoints. Only to change to display:none or change content.

### Fluid typography and logo

Title, logo and buttons from header follow a fluid typography. They change their sizes base on viewport using clamp. Not base in media queries.

### Flexbox

The rest of images change size or line wrap with flexbox. I added some constrains min and max to all elements.

### Action driven animations

1. Different transititions time for diferent actions (hover, not hovering, active).
2. Transition delay when hover on a poster show / movie. Only active transform in case is clear that the user want to.
