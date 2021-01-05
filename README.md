# TipCalculator
**TipCalculator** is a tip calculator application for iOS.

Submitted by: **Sara Fryzlewicz**

Time spent: **3** hours spent in total

## User Stories

The following **required** functionality is complete:

* [X] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [X] User can select between tip percentages by tapping different values on the segmented control and the tip value is updated accordingly

The following **optional** features are implemented:

* [X] UI animations
* [X] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [X] Calculating how many people the bill will evenly be split with

## Video Walkthrough

Here's a walkthrough of implemented user stories:

https://giphy.com/gifs/JVacuC6vzSB71N4lZA/html5

<img src='https://giphy.com/gifs/JVacuC6vzSB71N4lZA/html5' title='Video Walkthrough' width='' alt='Video Walkthrough' />



## Notes

Wanting to add a table view to calculate multiple totals for multiple people in a compacted and scrollable options was something that I wanted to do. 
With much trial, error, and redesign, I decided that the app would be cleaner and less complex if a stepper was put in place of the table view. The new design
change is less taxing for the user; the user would only have to input one number and toggle the stepper to calculate how much everyone is paying, instead of 
typing out an itemized bill.

## License

    Copyright [2021] [Sara Barbara Fryzlewicz]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0
