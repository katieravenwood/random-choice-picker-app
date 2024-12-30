# Tabbed Random Choice Picker

This is a nice little bit of code for spinning up a local or remote instance of a random choice picker, and can be used and customized in a multitude of ways to serve lots of quick needs.

I spun it up when I needed a quick script for running a white elephant gift picker for one of my team's recent retros, and I figured sharing the love would be fun and helpful since what I needed wasn't out on the interwebs as a tutorial or general coding exercise. If you find the basic script or even the included White Elephant Retro Gift Picker script helpful, I'm always up for [a coffee](https://buymeacoffee.com/katieravenwood) and it would be greatly appreciated!

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/katieravenwood)


## Random Choice Picker basic script

The basic Random Choice Picker script features the following options:

- *Choices tab*
  - Choices are entered via the textarea box, with each new choice being listed on a new line for individual or bulk entry
  - Selection radio button array to indicate whether the list of choices should be displayed on the picker tab before choices are drawn.
  - Selection radio array to indicate whether choices may be reused
  - The ability to delete choices from the choice list or reset the list entirely
- *Picker tab*
  - Choices are displayed in the order they are chosen
    - If choices are displayed on the picker tab, they can be highlighted or crossed out based on whether choices may be reused
  - Choices may be deleted from the pick list as needed, and will be returned to the list of available options if choices are not to be reused.
  - The pick list may be reset from within the picker tab while retaining the list of choices available on the choice list.

## Random Choice Picker with User-Choice Association

This script is the basis for the white elephant-style picker below, but contains a more generic workflow with the following options:

- *Choices tab*
  - Choices are entered via the textarea box, with each new choice being listed on a new line for individual or bulk entry
    - The ability to delete choices individually from the list of choice items entered or reset the list entirely
- *Users tab*
  - Users are entered via the textarea box, with each new choice being listed on a new line for individual or bulk entry
    - The ability to delete users from the user list individually or reset the list entirely
- *Picker tab*
    - User-choice pairs are displayed in the order they are chosen
    - User-choice pairs may be deleted from the pick list as needed, and choices will be returned to the list of available options if choices are not to be reused.
    - Choices may be dragged and dropped to a new user to swap choices with that user
    - The pick list may be reset from within the picker tab while retaining the list of choices available on the choice list.
