# Tabbed Random Choice Picker

![White Elephant Gift Logo](White_Elephant_Logo.png)

This is a nice little bit of code for spinning up a local or remote instance of a random choice picker, and can be used and customized in a multitude of ways to serve lots of quick needs.

I spun it up when I needed a quick script for running a white elephant gift picker for one of my team's recent retros, and I figured sharing the love would be fun and helpful since what I needed wasn't out on the interwebs as a tutorial or general coding exercise.

The scripts are coded in HTML, CSS, and vanilla JavaScript, and are condensed into a single HTML file for ease of use-- you can simply download the HTML files and run them locally! 

If you find any of these scripts helpful and fun, I'm always up for [a coffee](https://buymeacoffee.com/katieravenwood) and it would be greatly appreciated!

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/katieravenwood)


## Basic Random Choice Picker 

- **Single File App in HTML:** [tabbed-random-choice-picker.html](https://github.com/katieravenwood/random-choice-picker-app/blob/22206231d31b47bdd95a69cbcce1d0f36962ab8e/tabbed-random-choice-picker.html)
- **Browser View**: [Basic Random Choice Picker Script](https://htmlpreview.github.io/?https://github.com/katieravenwood/random-choice-picker-app/blob/main/tabbed-random-choice-picker.html)

The basic Tabbed Random Choice Picker script features the following options:

- *Choices tab*
  - Choices are entered via the textarea box, with each new choice being listed on a new line for individual or bulk entry
  - Selection radio button array to indicate whether the list of choices should be displayed on the picker tab before choices are drawn.
  - The ability to delete choices from the choice list or reset the list entirely
- *Picker tab*
  - Choices are displayed in the order they are chosen
    - If choices are displayed on the picker tab, they will be crossed out if choices may not be reused
  - Choices may be deleted from the pick list as needed, and will be returned to the list of available options if choices are not to be reused.
  - Radio buttton array that displays only when all choices have been used that asks if choices may be reused
  - The pick list may be reset from within the picker tab while retaining the list of choices available on the choice list.


## Random Choice Picker with User-Choice Association

- **Single File App In HTML**: [tabbed-random-user-choice-pair-picker.html](https://github.com/katieravenwood/random-choice-picker-app/blob/22206231d31b47bdd95a69cbcce1d0f36962ab8e/tabbed-random-user-choice-pair-picker.html)
- **Browser View**: [Random Choice Picker with User-Choice Pairing](https://htmlpreview.github.io/?https://github.com/katieravenwood/random-choice-picker-app/blob/main/tabbed-random-user-choice-pair-picker.html)


This script is the basis for the white elephant-style picker below, but contains a more generic workflow with the following options:

- *Choices tab*
  - Choices are entered via the textarea box, with each new choice being listed on a new line for individual or bulk entry
    - Selection radio button array to indicate whether the list of choices should be displayed on the picker tab before choices are drawn and crossed off as selections are made if choices cannot be reused
    - The ability to delete choices individually from the list of choice items entered or reset the list entirely
- *Users tab*
  - Users are entered via the textarea box, with each new choice being listed on a new line for individual or bulk entry
    - The ability to delete users from the user list individually or reset the list entirely
    - Selection radio button array to indicate whether the list of users should be displayed on the picker tab before choices are drawn and updated as selections are made
- *Picker tab*
    - User-choice pairs are displayed in the order they are chosen
    - Radio buttton array that displays only when all choices have been used and there are users remaining that asks if choices may be reused
    - User-choice pairs may be deleted from the pick list as needed, and choices will be returned to the list of available options if choices are not to be reused.
    - Choices may be dragged and dropped to a new user to swap choices with that user
    - The pick list may be reset from within the picker tab while retaining the list of choices available on the choice list.


## White Elephant Style Gift Picker

- **Code: Single File App in HTML**: [white-elephant-gift-picker.html](https://github.com/katieravenwood/random-choice-picker-app/blob/22206231d31b47bdd95a69cbcce1d0f36962ab8e/white-elephant-gift-picker.html)
- **Browser View**: [Random Choice Picker with User-Choice Pairing](https://htmlpreview.github.io/?https://github.com/katieravenwood/random-choice-picker-app/blob/main/white-elephant-gift-picker.html)

This script allows the assignment of Gifts to Party Guests, and features a slightly different workflow than the above pickers:
- The first Party Guest chosen automatically is paired with a gift. 
- For each subsequent choice, the user is asked whether to Steal a gift from another user or select a new gift before the new assignment is made. 

## White Elephant Style Gift Picker with Theft Limit

- **Code: Single File App in HTML**: [white-elephant-gif-picker-with-theft-limit.html](https://github.com/katieravenwood/random-choice-picker-app/blob/22206231d31b47bdd95a69cbcce1d0f36962ab8e/white-elephant-gift-picker-with-theft-limit.html)
- **Browser View**: [White Elephant Gift Picker WIth Theft Limit](https://htmlpreview.github.io/?https://github.com/katieravenwood/random-choice-picker-app/blob/main/white-elephant-gift-picker-with-theft-limit.html)

This script allows the assignment of Gifts to Party Guests like the version above, abut limits gift stealing on a per-gift basis to three thefts:
- The first Party Guest chosen automatically is paired with a gift. 
- For each subsequent choice, the user is asked whether to Steal a gift from another user or select a new gift before the new assignment is made. 
- Gifts may only be stolen and reassigned three times maximum, and a Steal Count is listed next to the Gift in the list.*
  - Once a Gift has been stolen three times, its assignment is locked and it cannot be reassigned.