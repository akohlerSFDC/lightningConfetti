# lightningConfetti
We all love the OOTB confetti effect available on the Sales Path. Ever had a client ask for a confetti effect in a different scenario? Well, here it is: a customizable confetti effect that can be fired through code, with the ability to customize the confetti color, direction and more! 

This repo contains the basis of what you'll need in either Aura Component or LWC format, as well as the static resource file that makes the magic happen. 

This particular version creates a confetti effect on the screen of an opportunity record page when the sales path is completed through code, based on condition of opportunity stage name and if the page has loaded once (in case the stage is already completed, so it doesn't fire on page load).

I plan to make this more generic, with instructions as to how to manipulate it for general use cases. 
