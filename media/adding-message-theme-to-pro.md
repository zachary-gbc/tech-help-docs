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
- This assumes that the message will use a theme already created, see separate instructions for creating a theme in Pro7
- Some messages are in Sermonary, some in PPT, some as word documents, but all go into Pro7 the same way
- This assumes the message is for the main service on Sunday morning (or another main service like Good Friday, Thanksgiving Eve, etc.)
  - If the service is for another event or another location some pieces may differ, but the main instructions are the same

# Gathering Content:
- If there are images, they should be placed within a folder for the current date (yyyy-mm-dd) within the Sanctuary_Service_Graphics folder
  - For example, in Finder the folder would be /users/&ltusername&gt/Sync/ProPresenter_Shared_Content/Sanctuary_Service_Graphics/2026-01-01
  - Usually images are gathered first but that is not required
  - Graphics added to this folder will automatically show up in the ProPresenter media bin

# Starting the Presentation
One of the easiest ways to start a presentation is to duplicate the one from the previous week and then rename it. Presentations are named by date of message (yyyy-mm-dd) and then speaker name, for example 2026-01-01-Zak. This keeps them in order but also tells you who the speaker is. Messages should be placed in the correct library for the year of the message.

The first slide is typically for the timer and to reset certain settings. The slide should have the following components:
- Macro called Speaker Start which includes the following items:
  - Clear All
  - Set Stage Display to Live with Timer
  - Set Audience Look to Nothing to Lower Thirds
- A Timer set to the correct time (using main timer and setting it to count down a certain amount or count down to a specific time, depending on the speaker’s preferences)
- A slide label that says Timer Starts Here or &ltFirst/Second/Etc.&gt Service Timer (if different timers per service)

The first few slides contains the series background with the audience look Nothing to Broadcast and then the background for the message.

# Building the Presentation
If the presentation was duplicated you can reuse slides as you are able, just remember some may have been altered so sometimes it is best to just start fresh. It is usually easier to make edits using the Edit screen rather than in Show or Reflow because then you can make box and text size adjustments as needed (see below).

To add a slide in edit, click the plus symbol on the top left of the screen, choose the theme from “Message Series”, and then choose the slide you want to add. Once you have chosen the theme, it will pop up by default when you click the plus symbol. Almost always add a slide that is for lower thirds, not one for the wall. Our looks convert slides for lower thirds to one for the wall. There are some exceptions, but this is the general rule.

## Adding a Point Slide
Once the slide is added copy and paste the point into the text box. After copying, use Command + Option + Shift + V to paste without formatting. This will allow you to use the formatting within the textbox. If you just paste and the formatting is messed up best to undo and try again or re-apply the theme by right clicking on the slide and choosing themes and then pick the correct theme slide.

When adding a point, if it will be more than one line you may need to manually add a line break to allow it to wrap nicely and look good on the lower thirds and the wall. Best to keep multiple lines the same ish width if possible or break in a logical space like a comma. On some occasions if the point is long might want to speak with the speaker about shortening it or putting the longer point into the Scripture/Quote slide and removing the reference (see below).

## Adding a Scripture/Quote Slide
Similar to above add the slide using the current theme, and then copy/paste the verse (or quote) and reference (or person who said the quote) into the slide. It is best to have the reference (or person) on the slide before continuing. Once both are added go through the scripture (or quote) and remove numbers, reference markers, etc. that are not needed for displaying on the screen before fitting the content.

When fitting the content, typically there are only three lines to a lower thirds slide. Any more than that and it may be too long or hard to find your place if there is a pause. Sometimes a fourth line is added to keep things together but often then it may be split into two two line slides. To split content into multiple slides, edit the text box with the content and look for places to make a break, usually at commas, periods, or pauses in the content. Add two line breaks to test it out and see how it will look for all slides. Once you know where the breaks will be, go to the break and press Option + Enter. This will move the content below the cursor to the next slide and copy the reference using the same theme slide. You can do this multiple times to copy all content onto as many slides as needed.

Once all are done, add a blank slide to the presentation so the operator can know when they are at the end of the scripture or quote.

## Adding an Outline Slide
Similar to above add the slide using the current theme, then add in the content and heading to the text boxes. Pull the right side of the text box with the content until the box is the width of the largest item in the list. Then pull the heading textbox to match the content textbox. 

To make a list build out, make the full list slide, then duplicate it as many times as needed and remove the lower items so the first slide only has the first item, then the second slide has the first and second, etc. until the last slide has all the items in the list.

## Adding an Image
Go to the show view to add images. Drag them from the media bin into the presentation and then right click and convert the media to a slide element. All images can be done at once if by selecting them all and then right click on one and convert to slide elements.

Switch to the edit view and if the image does not fill the screen it can be enlarged it to fill the screen or a black box can be added behind the image to block out the background and show the image on the screen. Do this by adding a square shape, expand it to fill the entire screen, set the color to black, and then on the bottom left move the box down so the image is above it.

# Audience Looks
Once all slides are added, switch to the show view. Select all the point slides and then right click on one, choose Add Action > Audience Look > Speaker-Points. Then choose all the verses and add the look Speaker-Scripture/Quote. For the outline slides choose Speaker-Outline. For all the images add the Nothing to Broadcast look and also add a label “Nothing to Broadcast” in red (it is a saved label).

# Testing
Click through all slides and test them to make sure all look good on the wall, broadcast, and the stage display. Correct any issues as they arise and then test again.

# Speaker Review
After finishing the presentation it should be reviewed with the speaker. That may be done in person if they are available or the presentation can be printed to PDF and sent to them.

To print the presentation to PDF click the presentation name in the library, then choose File > Print. Choose two columns, no notes, and then on the bottom left chose PDF and save the file and send it to the speaker for them to review and ensure nothing was missed or incorrect.
