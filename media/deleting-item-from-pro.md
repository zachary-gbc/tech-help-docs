---
layout: default
title: Deleting Item From ProPresenter
parent: Media
nav_order: 5
---

# Deleting Item From ProPresenter
{: .no_toc }
Because items are syncronized between machines, if an item is deleted from ProPresenter it must be done in a special way otherwise it will come back the next time the syncronization runs.

## Table of Contents
{: .no_toc }

1. Open Finder
1. Navigate to Documents > Scripts and double click pro7adddelete.command
  - This should open a teminal window with the prompt: *Please add file or folder to be deleted:*
1. Open ProPresenter and navigate to the item within the library you would like to delete
1. Right click on the item and choose *Show in Finder*
1. Drag the file into the terminal window opened above
  - It should show the path, something like: /Users/username/Documents/ProPresenter/Libraries/Other/item.pro
1. Press enter to add the item to the list of deleted items
1. You can add another item and press enter to add another item
1. Quit terminal when completed
