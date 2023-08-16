# Un.titled Front End Developer test project

## Objectives


You need to setup Drupal and install the site and modules using composer, then using configuration management sync the current configuration.
In your codebase you will see a theme called “Pippip” – please do your theme work inside this folder.

Once finished please zip up your theme directory email to [robert.lambert@un.titled.co.uk](robert.lambert@un.titled.co.uk)[robert.lambert@un.titled.co.uk](robert.lambert@un.titled.co.uk)

##Spec

Your site contains two content types:
•	Homepage
•	Page

The Page content type has 2 fields along with its title:
•	Banner Image
•	Body

The Homepage content type has 2 fields along with its title:
•	Page references – An entity reference to the Page content type
•	Page reference title – As shown in the design above (Shop by activity)

Your developer task is on Homepage to display the Page entity references like above, as well as use the Page reference title – Each Page entity is using a “Signpost” view mode which currently is showing all 3 fields in the configuration.
Each Signpost will need to contain:
•	The banner image
•	The title of the entity
•	The entire card will need linking to the entity
 
The design does not have to exactly match what is given above but try and style the above design to follow these guidelines:
•	The font family does not matter, you can choose one of your liking
•	The title has a font size of 24px and a margin bottom of 40px
•	Width of all three cards combined should be 1450px with a gap of 25px in between each card
•	Each card should be approximately 468px in width and the title should be 18px with a margin top of 15px
•	The entire block should sit in the middle of the page with a background.
•	The background it is sitting on has the hex code #eeeeee
•	On mobile device could all these cards please stack into one column
•	The image for the view mode is not using an image style, this is not required for your task, but make sure the image isn’t stretched.

You are not required to style the full view mode of the individual page content type themselves – The full view mode of the page should still show the following:
•	Title	
•	Body
•	Banner Image

Please ensure that if body copy is added, that it only appears on the full view mode and not on the signpost teaser.
A basic css file and templates are in the theme but feel free to introduce a CSS preprocessor and any templates to complete your task.

Good luck!

