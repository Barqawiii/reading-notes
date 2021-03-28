# Images
through CSS when can control images size and we can play with how it will affect our presentation.

# Controlling sizes of Images in CSS
You can control the size of an image using the width and height properties in CSS, just like you can for any other box.
you can use percentages or pixels to define images width and height

# Aligning images Using CSS
developers uses float property to control the alignment of images nowadays, and align property is forsaken

# Centering images Using CSS
to to make an image at the center you need to display it first as a block element using the display : block rule set, then assigning the margin to auto
# Background Images
to use an image as a background, you can attach an image URL to the background-image property 

# Background Position
When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed. This property has the following values:

left top
left center
left bottom
center top
center center
center bottom
right top
right center
right bottom
you either choose 2 values (one for vertical and one for horizontal) or choose one and the second one will be default to center


# Audio
I think we've taught you enough in this article. The HTMLMediaElement API makes a wealth of functionality available for creating simple video and audio players, and that's only the tip of the iceberg. See the "See also" section below for links to more complex and interesting functionality.

Here are some suggestions for ways you could enhance the existing example we've built up:

The time display currently breaks if the video is an hour long or more (well, it won't display hours; just minutes and seconds). Can you figure out how to change the example to make it display hours?

Because elements have the same HTMLMediaElement functionality available to them, you could easily get this player to work for an element too. Try doing so.

Can you work out a way to turn the timer inner

element into a true seek bar/scrobbler — i.e., when you click somewhere on the bar* it jumps to that relative position in the video playback? As a hint, you can find out the X and Y values of the element's left/right and top/bottom sides via the getBoundingClientRect() method, and you can find the coordinates of a mouse click via the event object of the click event, called on the Document object.