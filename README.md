# Revolving-Css-Animations
A general guide to make a simple yet fancy design in html/css.

To start:
git clone 'https://github.com/cdminigun/Revolving-Css-Animations.git'

Then you can view an example after editing your directory strucutre for the link to the css and image. 

From here you can create your own picture, add your own content and play around with the affect. 

Layout: 

First, create an image using your favorite tool that allows for transparency. (I used Gimp.) This will allow you to do a various amount of colors. For instance, in my use case. I utilized a Black (#222) and white theme to create my image as it matched my site layout and design. Feel free to choose the colors that match you website the most.(However, be careful to choose colors close on the color wheel, as you may hit some strange colors utilizing my method (though if you go for scroll effect, you should be able to render whatever color.  

The trick when creating the image is to create an image that has two colors and transparency always between them. This means that when a background color of your first or second color is selected, you'll only see one portion of your image. Allowing you to hide a design from your users and then surprise them (provided they're on the page long enough for the transition to display.) 

The ultimate trick to this design is to be creative and think outside of the box. 


The CSS referenced shows a simple way to do the alternations, applying a background color of what we'll call colorA so that it corresponds to the actual color of colorA, then adding a transition effect in the keyframe that goes from colorA to colorB, making it so that the colorA will slowly start to vanish as colorB appears. In this example the colors will alternate indefinitely, however you could add utilizing the animation-fill-mode to assign an end color, however this will also affect the starting color during delay.
