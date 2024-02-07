# instapage-accordion
Accordions that don't hang off the screen


A common problem in instapage is creating accordions that actually work, a common design pattern for FAQs.

Usage:

Create a or global block in instapage, paste the code in index.html and add the script to footer.

The JavaScript uses the weird DOM structure of Instapage to grab parent elements of parent elements and expand the height of the page dynamically depending on the state of the accordions, not a pretty solution but it works.
