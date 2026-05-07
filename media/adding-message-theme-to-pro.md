---
layout: default
title: Adding Message Theme to ProPresenter
parent: Media
nav_order: 4
---

# Adding Message Theme to ProPresenter
{: .no_toc }
This is for adding a new message theme to be used in a service like Sunday morning or special service like Good Friday, Thanksgiving Eve, etc.

## Table of Contents
{: .no_toc }

1. TOC
{:toc}

# Pre-Notes and Assumptions:
- This assumes that the theme will follow the typical format of our messages and only includes instructions for the main slide types
- Artistic design of the theme slides will be needed to make them look good, but some overall snags and common pitfalls are explained here to help avoid them
- All fonts must be in the font book as a local font. They cannot be Adobe fonts as those will get replaced with default fonts when syncronization happens

# Creating the Theme
The first few steps are critical to be done in a specific order and before the syncronization script runs (otherwise you may have multiple themes)
1. Open Theme Editor
1. Under Theme Selector Choose New Theme at bottom and input the appropriate name (typically the series name)
1. Go back to Show or Edit to stop editing the theme in ProPresenter
1. Open Finder and navigate to Documents > ProPresenter > Themes
1. Move the folder of the theme you just created into the Message Series folder
1. Back in ProPresenter go back to Theme Editor and choose the newly created theme from the dropdown and add slides below

# Adding Slides
The first slide is always a blank slide. This has nothing on it and is useful for adding a new message. For examples you can look at a previous theme.

## Points LT
The next slide is the Points LT slide. This one contains a textbox (usually on the bottom left) and is used for message points. Typically the background from the series is used as the textbox background. Sometimes it is scaled to fit or stretched to fill. Normally the textbox is made to be a lot bigger than the text it will contain and then the background expands to fit the text. 

To make the background expand to fit the text within the box go to the Text tab on the right side of the screen and do the following things:
- Use the gear dropdown to add margin to the top, bottom, right and left sides (maybe 50 each to start)
- Change the scaling to be "Container up or down"
- Check the Lines Only checkbox
  - Change the dropdown to be Max Line Width and then adjust the vertical and horizontal padding to look good around the text within the box

You should try a couple iterations of text in the box to see how it looks. Try a short one with just a couple words or a long point with multiple lines of text and make sure they all look good.

## Scripture / Quote
The next slide is the Scripture/Quote slide. The one contains the reference (or person being quoted), and the scripture or quote. This slide should be setup for the LED Wall as we are not using lower thirds for scripture/quote slides. Typically the reference (or person being quoted) is in a different font, size, or a line is placed below to make a distinction between the two sections. The content of the slide usually has justified text alignment.

## Outline LT
This slide typically has a header type textbox for the top of a list and then a textbox for the list of items. This is not always used so may need to check a couple older themes to find one where it was used.

## Points Wall
This slide will be used to show the point on the LED wall. This slide typically just has one textbox in the center of the screen.

## Outline Wall
This slide will be used to show the ouline or list of points on the LED wall. This slide typically has one textbox near the top for the header or label and then another one that includes the content. One shortcut is to copy and paste the textboxes from the scripture wall slide and tweak them slightly such as making the alignment left instead of justified.

## Updating Looks
Click Screens in the menu and Edit Looks. The following looks need to be edited:
- Speaker-Points: Change Video Wall & Side TVs Presentation Alternate Theme to Points Wall
- Speaker-Outline: Change Video Wall & Side TVs Presentation Alternate Theme to Outline Wall
